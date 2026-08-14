# Teddy Caulton Website

This project is a lightweight static personal website built with plain HTML and CSS.

## Structure

- `index.html` — home page with intro, projects, blog links, photos, and downloads
- `styles.css` — shared dark theme, layout, and responsive styling
- `website_resume.pdf` — downloadable resume
- `images/` — site images and photography
- `blogs/` — blog article pages kept at their current URLs for compatibility

## How to add new blog posts

- Create a new HTML file in `blogs/`.
- Use the same page structure as the existing article files.
- Include a link to it from the home page blog list.
- Keep the filename stable if you want to preserve previously shared links.

## How to add images

- Save the image in `images/`.
- Reference it using a relative path from the page, for example `images/my-image.jpg`.
- Update the relevant gallery or article page to display it.

## Notes

- This is intentionally static: no backend, no framework, and no build step required.
- Existing file and URL names are preserved where possible so already-shared links remain valid.
- To preview locally, open `index.html` in a browser or serve the folder with a simple static HTTP server.
