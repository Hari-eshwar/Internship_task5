# Full-Stack Deployment & Project Architecture

Northstar Objects is a production-style e-commerce product catalog prototype. It demonstrates modular client-side routing, reusable product data and components, persistent cart state, responsive layouts, metadata, and a deployment-friendly static architecture.

## Run
Open `index.html` directly, or serve the folder with any static server: `python3 -m http.server 8080`.

## Routes
- `#/` — editorial home page
- `#/shop` — catalog
- `#/product/:id` — product details
- `#/about` — brand story
- `#/bag` — persistent shopping bag

## Production notes
This is a front-end capstone with a demo checkout. A production deployment can be published to Vercel, Netlify, or Render as a static site, with a real payment provider and server-side inventory added behind the existing route structure.
