# Midnight Bouquet

An animated bouquet drawn with plain HTML, CSS, SVG and JavaScript. Stems draw themselves in, then each petal opens one by one.

**Flowers:** sunflower, rose, tulip, daisy, cosmos, lavender, baby's breath.

## How it works
- Every shape is created in JavaScript with `document.createElementNS` and SVG paths.
- Lines are "drawn" by animating `stroke-dashoffset` from the path length to 0.
- Petals fade and scale in, each on its own timer, so the flowers bloom in order.
- Sunflower seeds follow the golden angle (137.5°), like real seed heads.
- No libraries and no build step. Open `index.html` in a browser.

## Run it
Open `index.html` in any browser, or visit the GitHub Pages link.
