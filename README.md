# Best Choice Uniform website

Static, dependency-free website build prepared from the supplied Best Choice Uniform website specification.

## Deploy to Vercel
1. Upload this folder to a GitHub repository.
2. Import the repository into Vercel.
3. Framework preset: Other.
4. Build command: leave empty.
5. Output directory: `.`.
6. Deploy.

The site is plain HTML, CSS and vanilla JS, so there is no npm install or build step.

## Before launch
The source specification contains client-supplied placeholders. Replace/confirm:
- Establishment year
- Trade licence number and issuing authority
- VAT TRN
- Founder and team names/photos/bios
- Client logos and permissions
- Real testimonials
- Real case study numbers
- MOQ by category
- Standard production lead times
- Delivery terms/charges
- Exact showroom address and map pin
- Opening hours
- Real facility and finished-uniform photography

The current build deliberately avoids inventing those facts.

## Forms
Forms are styled and functional as a front-end demo only. Connect the submit handler to the client's CRM, Google Sheet/database, email and WhatsApp workflow before launch.

## Images
The `assets/` folder contains original lightweight SVG editorial illustrations used as temporary generated visuals. The supplied specification explicitly requires real client photography for the facility, team, showroom and finished uniforms when available.

## SEO
Included:
- `robots.txt`
- `sitemap.xml`
- `llms.txt`
- Semantic headings
- Crawlable FAQ content
- Descriptive image alt text
- Responsive layout
- Reduced-motion support
- Lightweight vanilla JS
