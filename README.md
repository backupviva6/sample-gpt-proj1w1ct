# Brightside Landing Page

A modern, responsive startup landing page for a fictional team productivity
platform. The project uses semantic HTML and plain CSS, so it is easy to read,
customize, and deploy without a build step.

## Features

- Responsive startup-style hero section
- CSS-only product dashboard illustration
- Clear calls to action and product benefit cards
- Trusted-company row and conversion-focused footer
- Entrance, floating, pulse, progress, and hover animations
- Mobile and tablet layouts
- Reduced-motion support for accessibility
- No JavaScript, frameworks, or package installation

## Project structure

```text
.
├── index.html   # Page content and semantic structure
├── style.css    # Layout, colors, responsive styles, and animations
└── README.md    # Project documentation
```

## Run locally

No installation is required. Clone the repository and open `index.html` in a
browser:

```bash
git clone https://github.com/backupviva6/sample-gpt-proj1w1ct.git
cd sample-gpt-proj1w1ct
```

You can also serve the directory with any static file server. For example, if
Python is installed:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Customize

- Edit text, navigation links, and calls to action in `index.html`.
- Change the color variables near the top of `style.css` to update the theme.
- Replace `hello@example.com` with the real contact address before publishing.
- Update the fictional company names and product metrics with real content.

The page loads DM Sans and Manrope from Google Fonts. Replace the `@import` in
`style.css` with local fonts or a system font stack if the site must work fully
offline.

## Accessibility

The page uses semantic sections, labelled navigation, descriptive headings, and
a `prefers-reduced-motion` fallback. The dashboard preview is decorative and is
hidden from assistive technology so it does not expose nonfunctional controls.

## Deployment

This is a static site and can be deployed directly with GitHub Pages, Netlify,
Vercel, Cloudflare Pages, or any standard web server. Set the publish directory
to the repository root; no build command is needed.
