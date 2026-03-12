# After School Coffee (放學咖啡)

## Project
AEO-optimized static website for Macau specialty takeaway coffee shop. Built with vanilla HTML/CSS/JS, deployed via GitHub Pages.

## Architecture
- Static site deployment via GitHub Pages from main branch
- Schema.org structured data: Organization, CafeOrCoffeeShop, FAQPage
- llms.txt at site root for LLM discovery
- FAQPage schema for AEO optimization

## Conventions
- Use semantic HTML5 elements
- Keep CSS modular and responsive
- Minimize JavaScript; prefer vanilla over frameworks
- Include proper meta tags and structured data

## Naming
- Use lowercase with hyphens for file names (e.g., `about-us.html`)
- Use semantic class names (e.g., `.coffee-menu`, `.store-info`)

## Commands
- Push to main branch triggers automatic GitHub Pages deployment
- No build process required

## Do Not
- Do not add unnecessary client-side frameworks (React, Vue, etc.)
- Do not remove or modify AEO schema markup
- Do not change deployment branch from main
- Do not add complex build tools if not needed