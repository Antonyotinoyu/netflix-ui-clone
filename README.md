# Netflix UI Clone

## Description
A dynamic and responsive representation of the Netflix web user interface, built completely from scratch using HTML, CSS, and Vanilla JavaScript. This project heavily utilizes DOM manipulation to construct the interface dynamically by generating rows, categories, and movie cards through nested loops.

## Features
- **Dynamic DOM Rendering:** The entire application interface is painted onto a completely empty HTML container using JavaScript `document.createElement()` and `appendChild()` methods.
- **Nested Iteration Logic:** Organized categorizations and rows populated efficiently through nested `for` loops.
- **Responsive Movie Cards:** Implements modern `flexbox` CSS styling and `object-fit` logic so that all thumbnails scale and crop responsively regardless of aspect ratio differences.
- **Dynamic Tagging:** Conditional rendering logic automatically appends a 'Recently Added' badge to specific movie thumbnails based on inner data structures.
- **Netflix Theme:** Features the classic Netflix dark theme, including pagination indicators and hover scaling animations.

## Technologies Used
- HTML5
- CSS3 (Flexbox, Hover Transitions, Aspect Ratios)
- Vanilla JavaScript (DOM Structure Injection, Data Modeling)

## Installation & Setup
1. Clone this repository or download the source code locally.
2. Ensure you have downloaded the entire layout, especially the `img/` directory, which contains all locally hosted movie covers.
3. Open `index.html` in any web browser (Google Chrome, Firefox, Safari, Edge).
4. Hover over the movie cards to view the interactive scaling effects!

## Project Structure
```text
/
├── index.html        # Main template and inline scripts/styles
└── img/              # Directory containing the provided movie thumbnail images
```
