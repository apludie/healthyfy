# Goodstead

A responsive, client-rendered wellness education prototype built with Vite and plain JavaScript. The project has no backend, accounts, analytics, external search, email submission, booking, payment, or operational phone support.

## Run locally

1. Install Node.js 20.19+ or 22.12+.
2. Run `npm install`.
3. Run `npm run start` and open the local URL printed by Vite.
4. Run `npm run build` to create the production bundle in `dist/`.
5. Run `npm run preview` to preview that bundle.

Deploy to a static host configured to serve `index.html` for application routes. Replace `https://goodstead.example` in `src/config/site.js`, `public/robots.txt`, and `public/sitemap.xml` with the production domain. Keep the sitemap in sync with published routes.

## Structure

- `src/config/site.js`: centralized brand, domain, and contact placeholder configuration.
- `src/main.js`: route catalog, reusable page layouts, search, and all 19 client-side calculators.
- `src/style.css`: responsive design system and page styles.
- `public/`: crawl directives and a starter sitemap.

The phone display `+1-888-MY-HEALTH` is an unverified placeholder rendered as text. It has no telephone link. The site content is prototype educational copy and marked for qualified source and medical review before publication. No authors or credentials are represented as real people. Newsletter, programs, contact operations, and dietitian services require external implementation.

Calculator entries are processed in the browser. The weight tracker uses browser local storage and can be cleared from its result panel. Meal and recipe estimates use only values entered by the visitor; no food database is connected.
