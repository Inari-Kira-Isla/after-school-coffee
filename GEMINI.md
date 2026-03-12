# After School Coffee (放學咖啡)

## Overview
AEO-optimized brand website for a Macau specialty takeaway coffee shop. Focuses on structured data (Schema.org) and AI discoverability (llms.txt).

## Tech Stack
- **Core**: HTML5, CSS3, Vanilla JavaScript
- **Hosting**: GitHub Pages
- **SEO/AEO**: Schema.org (JSON-LD), llms.txt

## Architecture
- `/`: Root contains `index.html` and `llms.txt`.
- **Structured Data**: Implementation of `Organization`, `CafeOrCoffeeShop`, and `FAQPage` schemas.
- **Assets**: CSS and images in standard root directories.

## Commands
- **Development**: Open `index.html` in browser or use a local static server (e.g., `npx serve`).
- **Deployment**: Push changes to the `main` branch. GitHub Pages handles deployment automatically.

## Coding Style
- Semantic HTML5 tags for accessibility and SEO.
- Minimal client-side JavaScript; prioritize performance.
- Ensure all images have alt text.

## Important Rules
- **Do Not Remove**: The `llms.txt` file or any Schema.org JSON-LD scripts.
- **Maintain Structure**: Keep the FAQ section structured correctly for search engines.
- **Accessibility**: Ensure high contrast and WCAG compliance for the "Macau specialty" branding.