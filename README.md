# Ditherium

**Live:** https://genz000.github.io/Ditherium/ · editor: https://genz000.github.io/Ditherium/editor.html

A browser-based dithering tool. It turns an image or a video into a pattern of dots or shapes, with tone controls and export to still and animated formats. Everything runs in the browser; files are not uploaded.

## What it does

- **Sources:** JPG, PNG, GIF, MP4 and WebM. Drop a file onto the canvas or pick one.
- **Dithering:** Threshold, Ordered (Bayer), Floyd–Steinberg and Atkinson, with adjustable levels, threshold and contrast.
- **Grid:** set columns and rows, or link rows to columns.
- **Shapes:** circle, square, triangle, diamond, or your own SVG shape. Shapes can scale with tone, and both tones and shape scale can be inverted.
- **Framing:** original, free, 1:1, 4:3, 3:4, 16:9 or 9:16.
- **Export:** PNG, JPEG, WebP or SVG for images; animated GIF or WebM for videos. Set quality and output size.

## Run locally

The tool is plain HTML. Serve the folder with any static server, for example:

```bash
npx serve .
```

Then open `index.html` (landing page) or `editor.html` (the tool).

## Author

Made by Nader Boulaich — [naderboulaich.net](https://naderboulaich.net).
