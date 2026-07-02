# peregrine-ui

UI assets (HTML/CSS/JS) for Adobe's AI-powered content generation tools. Assets are served directly from GitHub via jsDelivr CDN and embedded as external includes in generated pages.

## Structure

- `libs/scripts/` — JS widgets, organized by feature
- `libs/styles/` — CSS for each widget
- `libs/components/`, `libs/configs`, `libs/utils/` — shared building blocks
- `instructions/` — usage/authoring notes per feature
- `blog-wizard.html` — entry point for the Blog Wizard widget

## Blog Wizard

A four-step guided flow for AI-assisted blog page generation: article proposal, skills review, brief generation, and page creation. Implemented in `libs/scripts/blog/blog-wizard.js` and `libs/styles/blog/blog-wizard.css`, mounted into a `#bw-root` container.
