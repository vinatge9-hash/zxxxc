# Savory Haven - Restaurant Website

A complete 3-page static website built with Tailwind CSS (via CDN), designed for a modern, warm, restaurant brand.

Files included:
- index.html  (Home with hero, menu highlights, and footer)
- about.html  (Our story, sourcing, and team)
- contact.html (Reservation form and location)

Design decisions
- Category: Restaurant
- Colors: Warm earth tones (primary #8B4513 saddle brown, secondary #CD853F peru, background #FDF6E3)
- Typography: Primary font Playfair Display for headings, Inter for body text (applied via Tailwind font-[...] classes)
- Background imagery: Hero uses a restaurant dining room backdrop via placeholder syntax
- Accessibility: semantic HTML5 elements, descriptive alt text for images, legible contrast

How to run
- Open the three HTML files directly in a browser or serve them via a simple static server.
- The site uses Tailwind CSS CDN for styling. No build step required.

Notes
- All pages are linked together with a consistent navigation. Internal anchors (e.g., #menu) provide quick access within the homepage.
- Font imports and category-based styling are assumed to be provided by your site processor (refer to font-[primary-font] and color placeholders in the templates).