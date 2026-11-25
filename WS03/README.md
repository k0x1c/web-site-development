# Workshop 3 – Advanced CSS Techniques

Advanced CSS techniques added to the page from Workshops 1–2: transitions, animations, pseudo-classes, filters and pseudo-elements.

## Objectives

- Change a style smoothly with a CSS transition
- Create continuous movement with `@keyframes` and the `animation` property
- Style elements by their position or state with pseudo-classes
- Change how an image looks with CSS filters
- Add decorative content with pseudo-elements

## Prerequisites

- Workshop 1: an HTML page with a heading, a paragraph, a picture, lists, a link, a table and a form
- Workshop 2: the same page styled with inline, internal and external CSS
- Visual Studio Code and a web browser

The page starts from the Workshop 2 page (as the workshop instructions ask) and adds the five advanced CSS tasks on top of it.

## Files

| File | Contents |
| --- | --- |
| `index.html` | The workshop page: one section per task, plus the base page from Workshops 1–2 |
| `styles.css` | External stylesheet; each task has its own commented block |
| `images/sunset.svg` | Illustration used in the filter task |
| `images/avatar.svg` | Profile picture in the base page |

## Tasks

- [x] **Task 1 – CSS Transitions:** `.transition-button` changes from light blue to light coral over 0.3 s on hover
- [x] **Task 2 – CSS Animations:** `.animation-box` moves 100px to the right and back continuously (`@keyframes move`, 2 s, `infinite alternate`)
- [x] **Task 3 – CSS Pseudo-classes:** `.pseudo-list` uses `:nth-child(odd)` and `:nth-child(even)` for alternating background colours
- [x] **Task 4 – CSS Filters:** `.filter-image` is grayscale and returns to full colour on hover
- [x] **Task 5 – CSS Pseudo-elements:** `.quote::before` adds a decorative quotation mark in front of the blockquote

## Viewing the page

Open `index.html` in a browser, or visit the workshop's GitHub Pages address (`.../WS03/`). Hover over the button and the image to see the transition and the filter.
