# Personal Homepage Redesign

## Objective

Redesign the existing personal homepage as a single-page academic website. The page should feel clean, layered, and Berkeley-aligned while preserving the lightweight static-site setup.

## Scope

The implementation will keep all primary content in `index.html`. The top navigation will link to same-page anchors:

- `About me`
- `CV`
- `Publications`
- `Blogs`
- `Service`

No separate pages will be added for this iteration.

## Visual Direction

Use a classic academic homepage layout inspired by the provided references:

- Top identity/navigation bar.
- Profile and contact block near the top.
- Full-width content sections below.
- Minimal decorative styling.
- Strong readability on desktop and mobile.

Use UC Berkeley-aligned colors:

- Berkeley Blue: `#002676`
- California Gold: `#FDB515`
- White background with restrained blue headings, gold accent rules, and neutral body text.

## Content Structure

### Header

The header will show:

- Sheng-An (Samuel) Xu / Samuel Xu.
- PhD student role.
- Department of Industrial Engineering & Operations Research.
- University of California, Berkeley.
- Email contact.
- Existing portrait image.

### About me

This section will include:

- Short personal introduction.
- Chinese name.
- Current PhD affiliation.
- Research interests, including online learning, sequential decision making, sampling and optimization, and high-dimensional statistics.

### CV

This section will group CV-like material from the provided text:

- Education.
- Research experience.
- Professional experience.
- Honors & Awards.
- Skills.

The CV section should be scannable, using dates aligned consistently with entries.

### Publications

This section will list the current publication:

- Generalized Linear Bandits: Almost Optimal Regret with One-Pass Update.
- Include authors, venue/status, year, and arXiv link.

### Blogs

Add a lightweight section with the exact text: "Blog posts will be added soon." The section should be ready for later post links.

### Service

Add a lightweight section for academic or community service with the exact text: "Service entries will be added soon." Do not invent service entries.

## Technical Constraints

- Keep the site static and simple: HTML and CSS only.
- Preserve existing assets under `Samuel@files/`.
- Avoid adding JavaScript unless necessary for navigation; anchor links are sufficient.
- Make the layout responsive using CSS media queries.
- Do not disturb unrelated tracked changes such as the existing `.DS_Store` modification.

## Verification

Before completion:

- Open the page locally in a browser.
- Check desktop and mobile widths.
- Verify all top navigation links jump to the correct same-page sections.
- Confirm the portrait renders.
- Confirm the Berkeley blue/gold palette is applied without reducing readability.
- Review `git diff` to ensure changes are limited to the homepage redesign and necessary supporting files.
