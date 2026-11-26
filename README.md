# CSS Art Gallery

A single-page gallery of CSS art, starting with a Dragon Ball illustration made from HTML elements and CSS.

## Current artwork

The page displays seven orange Dragon Balls with red stars, highlights, and shading against a blue background. The balls are arranged inside a responsive, bordered frame. The shapes and visual effects are created with CSS, including rounded elements, pseudo-elements, shadows, transforms, and `clip-path` shapes.

## Run locally

Open `index.html` in a modern web browser. No build tools or dependencies are required.

## Project files

- `index.html` — page structure and the Dragon Ball artwork elements.
- `style.css` — layout, colors, positioning, highlights, shading, and star shapes.

## Adding more artwork

Add the markup for a new piece to `index.html` and its styles to `style.css`. Keep each artwork inside the gallery container and give it its own frame and CSS classes.

## Browser support

The star shapes use the CSS `clip-path: shape()` function. Use a browser that supports this feature for the stars to render as intended.
