# Pixel Atlas Gallery

A responsive image gallery built with plain HTML, CSS and JavaScript. No frameworks or build step.

## Features
- Responsive CSS Grid layout (tall and wide tiles, two columns on phones)
- Lightbox viewer with next/previous buttons, image counter and captions
- Keyboard controls (Left/Right arrows, Esc) and swipe on touch screens
- Hover effects and smooth transitions
- Category filters (Landscapes, Cities, Abstract)
- Light and dark mode, keyboard focus styles, reduced-motion support
- Images are generated as inline SVG, so no image files are needed

## Run it
Open `index.html` in a browser.

## Use your own images
In `index.html`, edit the `DATA` array in the `<script>` block. Replace each `u:` value with an image path or URL:

```js
{t:'My photo', c:'Landscapes', s:'tall', u:'images/photo1.jpg'}
```

`t` is the title, `c` the category, `s` the tile shape (`''`, `'tall'` or `'wide'`).

## Deploy with GitHub Pages
Settings > Pages > Deploy from a branch > `main` / root > Save.

## License
MIT
