# Offset Studio

A responsive, multi-page website for a creative studio. Built with HTML and CSS, with an emphasis on typography, color, motion and straightforward navigation.

**Live site:** https://marcribeiroweb.github.io/offset-studio/

## Pages

- **Home** — introduction, featured work and services
- **Work** — portfolio grid with category filters and project previews
- **Services** — overview of services and a project-stage selector
- **Studio** — studio information and frequently asked questions
- **Contact** — enquiry form layout
- **Looma / FWD Finance** — project case studies with CSS-based galleries

## Features

- Responsive layouts for mobile and desktop
- Mobile navigation
- Light and dark appearance toggle
- CSS animations and hover effects
- Portfolio filters, expandable sections and project galleries
- Shared stylesheet across all pages

## Run locally

Clone the repository or download the files, then open `index.html` in a browser. There are no dependencies or build steps.

## Project structure

```text
offset-studio/
├── index.html
├── work.html
├── services.html
├── studio.html
├── contact.html
├── project-looma.html
├── project-fwd.html
└── style.css
```

## Notes

The pages are organized as standalone HTML files, with shared colours and layout rules in one stylesheet. The filters, mobile menu and galleries use native HTML controls and CSS.

The appearance toggle resets when moving between pages. The contact form is a front-end example with a placeholder email destination; it isn't connected to a form-processing service. Portfolio projects and studio details are concept content.

Colours, typography and layout styles can be adjusted in `style.css`, with the main colour variables defined near the top of the file.
