# Table of Contents

- [Table of Contents](#table-of-contents)
- [1. Table of Contents](#1-table-of-contents)
  - [Markdown all in one](#markdown-all-in-one)
  - [Manual](#manual)
- [2. LaTeX](#2-latex)
- [3. Keyboard Symbols](#3-keyboard-symbols)
- [4. Aligning Images](#4-aligning-images)
- [5. Animated SVGs](#5-animated-svgs)
- [6. File Trees](#6-file-trees)

# 1. Table of Contents

## [Markdown all in one](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)

The best option for creating a TOC with VSCode is the [Markdown all in one](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one) plugin. <kbd>CTRL</kbd>+<kbd>SHIFT</kbd>+<kbd>p</kbd> > `Markdown all in one: Create table of contents`

## Manual

To manually create a table of contents, you can use an ordered or unordered list of links pointing to the heading 1's.

- [Table of Contents](#table-of-contents)
- [1. Table of Contents](#1-table-of-contents)
  - [Markdown all in one](#markdown-all-in-one)
  - [Manual](#manual)
- [2. LaTeX](#2-latex)
- [3. Keyboard Symbols](#3-keyboard-symbols)
- [4. Aligning Images](#4-aligning-images)
- [5. Animated SVGs](#5-animated-svgs)
- [6. File Trees](#6-file-trees)

```md
- [Table of Contents](#table-of-contents)
- [1. Table of Contents](#1-table-of-contents)
  - [Markdown all in one](#markdown-all-in-one)
  - [Manual](#manual)
- [2. LaTeX](#2-latex)
- [3. Keyboard Symbols](#3-keyboard-symbols)
- [4. Aligning Images](#4-aligning-images)
- [5. Animated SVGs](#5-animated-svgs)
- [6. File Trees](#6-file-trees)
```

# 2. LaTeX

Using LaTeX in GFM (Github Flavored Markdown) is very simple, surround your expression in `$$`.

$$
y = x^2 + 2x + \frac{8}{3}
$$

```md
$$
y = x^2 + 2x + \frac{8}{3}
$$
```

Or inline expressions with single `$`: $y = x^2 + 2x + \frac{8}{3}$.

```md
Or inline expressions: $y = x^2 + 2x + \frac{8}{3}$.
```

The last option is rendering images of the equations and displaing them as images.

# 3. Keyboard Symbols

You can create keyboard symbols with the `<kbd>` HTML tag.

Just press <kbd>CTRL</kbd>+<kbd>ALT</kbd>+<kbd>DEL</kbd>.

```html
Just press <kbd>CTRL</kbd>+<kbd>ALT</kbd>+<kbd>DEL</kbd>.
```

# 4. Aligning Images

Using HTML you can choose how to align your images

<p align="left">
  <img src="assets/images/markdown.png">
</p>

<p align="center">
  <img src="assets/images/markdown.png">
</p>

<p align="right">
  <img src="assets/images/markdown.png">
</p>

```md
<p align="left">
  <img src="assets/images/markdown.png">
</p>

<p align="center">
  <img src="assets/images/markdown.png">
</p>

<p align="right">
  <img src="assets/images/markdown.png">
</p>
```

# 5. Animated SVGs

You can animate SVGs and add them to markdown documents. **This doesn't work on Gtihub.**

<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" style="margin:auto;background:#fff;display:block;" width="200px" height="200px" viewBox="0 0 100 100" preserveAspectRatio="xMidYMid">
<g transform="translate(50 42)">
  <g transform="scale(0.8)">
    <g transform="translate(-50 -50)">
      <polygon fill="#e15b64" points="72.5 50 50 11 27.5 50 50 50">
        <animateTransform attributeName="transform" type="rotate" repeatCount="indefinite" dur="1s" values="0 50 38.5;360 50 38.5" keyTimes="0;1"></animateTransform>
      </polygon>
      <polygon fill="#f8b26a" points="5 89 50 89 27.5 50">
        <animateTransform attributeName="transform" type="rotate" repeatCount="indefinite" dur="1s" values="0 27.5 77.5;360 27.5 77.5" keyTimes="0;1"></animateTransform>
      </polygon>
      <polygon fill="#abbd81" points="72.5 50 50 89 95 89">
        <animateTransform attributeName="transform" type="rotate" repeatCount="indefinite" dur="1s" values="0 72.5 77.5;360 72 77.5" keyTimes="0;1"></animateTransform>
      </polygon>
    </g>
  </g>
</g>
</svg>

You can create your own animations with software such as https://www.svgator.com/ or websites like https://svgartista.net/.

# 6. File Trees

Using the `graphql` syntax highlighting.

```graphql
# Code & components for pages
./src/*
  ├─ src/assets - # Minified images, fonts, icon files
  ├─ src/components - # Individual smaller components
  ├─ src/fragments - # Larger chunks of a page composed of multiple components
  ├─ src/layouts - # Page layouts used for different types of pages composed of components and fragments
  ├─ src/page - # Custom pages or pages composed of layouts with hardcoded data components, fragments, & layouts
  ├─ src/pages/* - # Next.js file based routing
  │  ├─ _app.js - # next.js app entry point
  │  ├─ _document.js - # next.js document wrapper
  │  ├─ global.css - #  Global CSS styles
  │  └─ Everything else... - # File based routing
  └─ src/utils - # Utility functions used in various places
```
