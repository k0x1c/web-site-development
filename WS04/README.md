# Workshop 4 – Page Layout Techniques

Basic page layout techniques: semantic HTML elements, CSS Grid, Flexbox and media queries.

## Objectives

- Structure a page with semantic elements (`header`, `nav`, `main`, `section`, `footer`)
- Build a layout with two rows and three columns using CSS Grid
- Line up boxes horizontally using Flexbox
- Change styles based on the screen width using media queries
- Validate the HTML and CSS with the W3C validator

## Prerequisites

- Workshops 1–3 (HTML basics, CSS fundamentals, advanced CSS)
- Visual Studio Code with the W3C Validation extension (needs Java 8 or later installed)

## Files

| File | Contents |
| --- | --- |
| `index.html` | The workshop page, with one section per task |
| `styles.css` | All styles; each task has its own commented block |

## Tasks

- [x] **Task 1 – Semantic elements:** `header` with the title and a `nav` menu, `main` with one `section` per task, and a `footer`
- [x] **Task 2 – Grid layout:** `.grid-container` uses `grid-template-columns: repeat(3, 1fr)` to place six items in two rows of three
- [x] **Task 3 – Flexbox layout:** `.flex-container` puts three boxes in a row with `justify-content: space-around` and `align-items: center`
- [x] **Task 4 – Media queries:** `.responsive-box` is light coral at 600px or narrower and light sea green at 601px or wider
- [x] **Task 5 – Validation:** `index.html` and `styles.css` pass the W3C validator with no errors or warnings

## Viewing the page

Open `index.html` in a browser, or visit the workshop's GitHub Pages address (`.../WS04/`). Resize the window, or use the browser's device toolbar (F12), to see the media query change the box colour.
