# Copilot Instructions for ajrhind.github.io

## Project Overview
This is a personal portfolio website, primarily static, built with HTML and CSS. The site is organized into several main pages (`index.html`, `bdi.html`, `mdi.html`, `oth.html`, etc.) and uses a single stylesheet (`style.css`). Images are stored in the `imgs/` directory, with further subfolders for organization.

## Key Files and Structure
- `index.html`, `bdi.html`, `mdi.html`, `oth.html`: Main navigation pages. Each page uses a similar structure and links to each other.
- `style.css`: Central stylesheet for all pages. Responsive design is implemented for screens under 600px width.
- `javascript.js`: Reserved for any future interactivity (currently not referenced in HTML).
- `imgs/`: Contains all images, including subfolders for specific categories (e.g., `imgs/ai/`).

## Patterns and Conventions
- **Navigation**: The `.menuSelect` div in each HTML file provides navigation between sections. Use consistent class names and structure for new pages.
- **Styling**: All styling is handled in `style.css`. Media queries are used for mobile responsiveness. Avoid inline styles.
- **Image Usage**: Reference images with relative paths (e.g., `imgs/ai/armadillo.jpeg`).
- **No Build Step**: This is a static site—no build tools or frameworks are used. Simply edit HTML/CSS and refresh the browser to see changes.

## Developer Workflow
- Edit HTML/CSS files directly.
- To add a new section, duplicate an existing HTML file, update content, and add a link in the navigation menu.
- Place new images in the appropriate `imgs/` subfolder and reference them with a relative path.
- Test changes by opening the HTML file in a browser.

## Project-Specific Notes
- The site is designed for simplicity and clarity. Avoid adding unnecessary JavaScript or external dependencies unless required.
- Keep navigation and layout consistent across all pages.
- If adding interactivity, update `javascript.js` and ensure it is referenced in all relevant HTML files.

## Example: Adding a New Portfolio Section
1. Copy `bdi.html` to `newsection.html`.
2. Update the content and navigation links in `newsection.html`.
3. Add a link to `newsection.html` in the `.menuSelect` of all other pages.
4. Add any new images to `imgs/` and reference them as needed.

## References
- See `README.md` for the project intent.
- All images: `imgs/` directory.
- Main stylesheet: `style.css`.

---
For questions or major changes, consult the project owner.
