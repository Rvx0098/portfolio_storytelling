# Contributing

Thank you for helping improve this portfolio project. Contributions should keep the site polished, fast, accessible, and easy to maintain.

## Good First Contributions

- Improve accessibility labels, keyboard behavior, or reduced-motion support
- Compress media assets without reducing visible quality
- Refine responsive layout issues on mobile and tablet viewports
- Add verified project screenshots or a README preview GIF
- Split large inline CSS or JavaScript into maintainable files
- Improve documentation clarity

## Local Workflow

```bash
git clone https://github.com/Rvx0098/portfolio_storytelling.git
cd portfolio_storytelling
python -m http.server 8000
```

Open `http://localhost:8000` and verify the page visually before opening a pull request.

## Pull Request Guidelines

- Keep changes focused and easy to review
- Include before/after screenshots for visual changes
- Test desktop and mobile widths
- Confirm links, images, modals, and animations still work
- Avoid committing private files, credentials, or unrelated generated artifacts

## Code Style

- Use semantic HTML where possible
- Prefer descriptive class names
- Keep animation logic readable and avoid unnecessary global state
- Respect `prefers-reduced-motion`
- Optimize images and videos before committing

## Review Checklist

- The page loads without console errors
- Navigation links scroll to the correct sections
- Certificate previews work as expected
- External links open safely in a new tab
- Media files are reasonably compressed
- Documentation reflects the actual project
