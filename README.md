# Impossible Colors

A single-page gallery of 47 animated color swatches inspired by "impossible colors": colors like reddish green or bluish yellow that the eye's opponent-color system normally can't perceive. It's a creative coding project in plain HTML, CSS and JavaScript, with no build step and no dependencies.

A screen can't literally show an impossible color. These swatches use animated CSS gradients, pulsing, glowing and spinning effects to suggest them, and to play with afterimages if you stare at one in fullscreen.

## Try it

Open `impossiblecolorsv2.html` in any modern browser. Either:

- download the file (or clone the repo) and double-click it, or
- if GitHub Pages is turned on for this repo, visit the Pages URL. `index.html` forwards to the gallery.

## What's in it

| Category | Swatches | Effect |
| --- | --- | --- |
| Stygian | 11 | Saturated color glowing out of black |
| Hyperbolic | 10 | Supersaturated colors in spinning conic gradients |
| Opponent | 8 | Fine alternating stripes of opponent pairs, such as red and green |
| Self-Luminous | 7 | Colors that seem to glow brighter than their surroundings |
| Mathematical | 5 | Playful "colors outside the spectrum", like Hyper Green and Negative Red |
| Composite | 4 | Paradox swatches, like Chromatic Gray and Vantablack-White |
| Pastel | 2 | Soft pastel takes, Pastel Pistachio and Seafoam Vortex |

## Features

- **Random Mix:** eight random swatches, reshuffled with Generate Mix
- **Category pages** for opponent and spinning colors, plus an All Colors page
- **Fullscreen view:** click any swatch, press Esc to close
- **Surprise Me:** opens a random color fullscreen
- **Favorites:** saved in your browser's localStorage
- **Copy** a color's name to the clipboard
- Responsive grid that works on phones and desktops

## The science, briefly

Human color vision compares signals in opponent pairs: red against green, blue against yellow, light against dark. That's why a single patch of light normally can't look reddish green. Researchers have produced "chimerical" colors by fatiguing the eye with one color and then showing another, so the afterimage combines with what you see. This project is an artistic riff on those ideas, not a scientific demonstration.

## Built with

HTML5, CSS3 (radial and conic gradients, keyframe animations) and vanilla JavaScript.

## License

MIT. See [license](license).
