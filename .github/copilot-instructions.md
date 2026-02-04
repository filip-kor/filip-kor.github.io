# AI Coding Agent Instructions for filip-kor.github.io

## Project Overview
This is a static HTML portfolio website hosted on GitHub Pages. The site consists of multiple HTML pages with inline CSS styling, no build process or external dependencies.

## Architecture
- **Structure**: Each page is a standalone HTML file (e.g., `index.html`, `ai_projects.html`)
- **Styling**: Inline CSS within `<style>` tags in the `<head>`
- **Navigation**: Simple HTML links between pages
- **Hosting**: Automatic deployment via GitHub Pages from the `main` branch

## Key Patterns
- **HTML Template**: Start with standard DOCTYPE, `<html lang="en">`, meta charset and viewport
- **Layout**: Use `<div class="main">` for centered content with max-width 640px
- **Typography**: 'Courier New' monospace font, dark text on light background (#fdfdf0)
- **Responsiveness**: Include media queries for mobile breakpoints (768px, 480px)
- **Links**: Unstyled anchor tags with hover effects (underline on hover)

## Example Page Structure
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Page Title</title>
    <style>
        /* Inline styles here */
    </style>
</head>
<body>
    <div class="main">
        <!-- Content -->
    </div>
</body>
</html>
```

## Development Workflow
- Edit HTML files directly in VS Code
- Commit changes to `main` branch for automatic GitHub Pages deployment
- No build commands or testing required

## Conventions
- Maintain consistent styling across pages (see `index.html` for reference)
- Use semantic HTML elements where appropriate
- Keep CSS inline and page-specific
- Follow responsive design patterns from existing pages