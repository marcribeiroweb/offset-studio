# OFFSET. — Multi-page HTML + CSS website

A fully offline-friendly fictional design agency demo with **7 HTML pages** and one shared CSS file. No JavaScript, frameworks, photo libraries or external fonts.

## Pages
- index.html — homepage with animated artwork and featured projects
- work.html — all projects, interactive category filters and CSS-only project popups
- services.html — services and interactive project-stage selector
- studio.html — about the fictional studio and expandable FAQ
- contact.html — validated native HTML form (see limitation below)
- project-looma.html — portfolio case study with interactive 3-panel CSS gallery
- project-fwd.html — second case study with interactive 3-panel CSS gallery
- style.css — every style, animation, and interaction

## Open the website locally
Extract the ZIP and open `index.html` in Chrome, Safari, Firefox or Edge. Keep all files together in the same folder. Navigation links connect the pages.

## Publish to GitHub Pages
1. Create a new **public** GitHub repository, e.g. `offset-studio`.
2. Upload all **eight files** directly into the repository root (not a nested folder).
3. Go to **Settings → Pages → Build and deployment**.
4. Choose **Deploy from a branch**, branch **main**, folder **/(root)**, then Save.
5. The URL will normally be `https://YOUR-USERNAME.github.io/offset-studio/`.

## Important HTML/CSS-only limitations
- Category filters, menus, appearance toggle, accordions, animations, overlays, and gallery tabs work without JavaScript in modern browsers.
- The appearance switch resets when navigating between pages; persistence requires JavaScript or server logic.
- Contact form uses browser validation and an illustrative `mailto:hello@example.com` target. The address is a placeholder. Opening an email app is browser/device dependent. HTML/CSS cannot reliably send or store messages. Use a form service/backend for real form handling.
- All business names, portfolio projects, and marketing copy are fictional examples. Replace before deploying as a real business.
- CSS selectors `:has()` require a modern browser (current Safari, Firefox or Chrome).

## Customise
Change wording in each HTML file. Change fonts, colours and layout in `style.css`; the `:root` block contains the main palette. No build step required.