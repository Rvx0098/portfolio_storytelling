# Rishit Verma Portfolio Storytelling

![Portfolio status](https://img.shields.io/badge/status-live-brightgreen)
![Project type](https://img.shields.io/badge/type-static%20portfolio-blue)
![Frontend](https://img.shields.io/badge/frontend-HTML%20%7C%20CSS%20%7C%20JavaScript-orange)
![3D](https://img.shields.io/badge/3D-Three.js-black)
![License](https://img.shields.io/badge/license-MIT-green)

> A cinematic personal portfolio built as a premium interactive storytelling experience for design, development, AI, branding, and analytics work.

## Banner Concept

Use a wide preview image or GIF that captures the hero animation, 3D profile frame, certification cards, and dark-mode transitions. Suggested file path:

```text
media/portfolio-preview.gif
```

## Overview

`portfolio_storytelling` is a single-page portfolio website for Rishit Verma. It presents professional work, skills, certifications, and contact links through a visually polished static frontend with custom animation, WebGL effects, responsive sections, and media-rich project storytelling.

The project is designed for recruiters, hiring managers, collaborators, and portfolio reviewers who need to quickly understand the creator's technical range across frontend development, UI/UX, branding, generative AI, data analytics, and visual design.

## Key Features

- Premium animated hero section with profile imagery and portfolio calls to action
- Smooth one-page navigation across About, Experience, Work, Skills, Certifications, and Contact
- Three.js-powered 3D visual layers, animated particles, torus knots, and section-specific WebGL scenes
- Responsive project cards for selected work, portfolio links, brand decks, and analytics projects
- Certificate gallery with modal previews for verified learning milestones
- Custom cursor, loading animation, scroll progress indicator, and reveal-on-scroll interactions
- Dark-mode visual transition behavior based on scroll context
- Static deployment-friendly architecture for GitHub Pages, Netlify, Vercel, or any CDN

## Tech Stack

| Area | Technology |
| --- | --- |
| Frontend | HTML5, CSS3, JavaScript |
| 3D / Motion | Three.js, CSS animations, Intersection Observer |
| Typography | Google Fonts: Sora, Manrope |
| Media | Local images, certificates, MP4 background video |
| Hosting | GitHub Pages-ready static site |
| Tooling | Git, GitHub |

## Project Structure

```bash
portfolio_storytelling/
+-- index.html              # Main static portfolio page with styles and scripts
+-- media/                  # Profile image, certificates, videos, and visual assets
+-- .github/                # Issue and pull request templates
+-- .env.example            # Optional environment variable reference
+-- .gitignore              # Local, build, cache, and secret exclusions
+-- CHANGELOG.md            # Project release history
+-- CODE_OF_CONDUCT.md      # Community behavior standards
+-- CONTRIBUTING.md         # Contribution workflow
+-- LICENSE                 # MIT license
+-- README.md               # Project documentation
+-- SECURITY.md             # Security policy and reporting guidance
```

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Rvx0098/portfolio_storytelling.git
cd portfolio_storytelling
```

### 2. Run Locally

Because this is a static site, no package installation is required.

Open `index.html` directly in a browser, or serve it locally:

```bash
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

### 3. Deploy

Recommended deployment options:

| Platform | Notes |
| --- | --- |
| GitHub Pages | Best fit for this repository's static structure |
| Netlify | Drag-and-drop or Git-connected deployment |
| Vercel | Static project deployment with CDN caching |

For GitHub Pages, set the publishing source to the repository root on the default branch.

## Screenshots

Add visual previews here to make the repository stronger for recruiters and portfolio reviewers.

| Section | Suggested Preview |
| --- | --- |
| Hero | Animated hero with profile frame |
| Work | Project card grid |
| Certifications | Certificate modal preview |
| Contact | Final CTA and social links |

```markdown
![Hero Preview](media/portfolio-preview.png)
```

## Security

This project does not require backend credentials or API keys. Security best practices still apply:

- Keep private notes, credentials, and `.env` files out of Git
- Store deploy-time values in the hosting provider's environment settings
- Avoid committing personal identity documents or private certificate links
- Validate any future contact form input on the server side before sending email or storing data
- Review third-party CDN usage before adding new external scripts

A full security policy is available in [SECURITY.md](SECURITY.md).

## Performance Notes

- Static HTML keeps hosting simple and fast
- Local media assets avoid runtime API calls
- Three.js renderers cap pixel ratio to reduce GPU cost
- `prefers-reduced-motion` checks reduce heavy motion for users who request it
- Preconnected Google Fonts improve font loading behavior

Recommended next optimizations:

- Compress large MP4 files in `media/`
- Add responsive image variants for certificates and profile media
- Lazy-load below-the-fold certificate images
- Add Lighthouse-based performance checks before major releases

## Roadmap

- Add a live screenshot or GIF preview to the README
- Split CSS and JavaScript into dedicated files for maintainability
- Add Open Graph metadata and a share preview image
- Replace placeholder certificate links with verified credential URLs
- Add automated HTML validation and accessibility checks
- Add a deployment guide for GitHub Pages

## API Documentation

This repository is a static frontend and does not expose backend API endpoints.

If a future contact form, analytics service, or AI assistant API is added, document:

- Endpoint paths
- Required environment variables
- Request and response examples
- Authentication and rate-limiting behavior
- Error handling expectations

## Contributing

Contributions are welcome for accessibility, performance, responsive design, documentation, and maintainability improvements. See [CONTRIBUTING.md](CONTRIBUTING.md) for the full workflow.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

## Suggested GitHub Description

Modern cinematic portfolio website built with HTML, CSS, JavaScript, and Three.js for interactive personal storytelling.
