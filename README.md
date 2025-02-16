# HTML & CSSLearning Guide

## Introduction
This repository serves as a comprehensive guide to learning HTML & CSS, covering all essential topics from basic structure to advanced concepts like forms, APIs, and accessibility.

## HTML Topics Covered

### 1. HTML Basics
- What is HTML?
- Structure of an HTML document (`<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`)
- HTML Tags and Elements
- Attributes in HTML
- HTML Comments (`<!-- Comment -->`)

### 2. HTML Text Formatting
- Headings (`<h1>` to `<h6>`)
- Paragraphs (`<p>`)
- Line Breaks (`<br>`)
- Horizontal Rule (`<hr>`)
- Bold (`<b>`), Italic (`<i>`), Underline (`<u>`)
- Strong (`<strong>`) and Emphasized (`<em>`)
- Subscript (`<sub>`) and Superscript (`<sup>`)

### 3. HTML Links & Anchors
- Creating Links (`<a href="URL">`)
- Opening links in a new tab (`target="_blank"`)
- Email Links (`mailto:`)
- Phone Links (`tel:`)
- Internal & External Links

### 4. HTML Images
- Adding Images (`<img src="URL" alt="description">`)
- Image Attributes (`width`, `height`, `alt`)
- Responsive Images (`<picture>` and `<srcset>`)

### 5. HTML Lists
- Ordered List (`<ol>`)
- Unordered List (`<ul>`)
- List Items (`<li>`)
- Nested Lists
- Definition Lists (`<dl>`, `<dt>`, `<dd>`)

### 6. HTML Tables
- Creating Tables (`<table>`)
- Table Rows (`<tr>`)
- Table Headers (`<th>`)
- Table Data (`<td>`)
- Merging Cells (`colspan`, `rowspan`)
- Table Styling

### 7. HTML Forms & Input
- Creating Forms (`<form>`)
- Form Elements (`<input>`, `<textarea>`, `<button>`, `<select>`, `<option>`)
- Input Types (`text`, `email`, `password`, `number`, `checkbox`, `radio`, `file`, `date`)
- Labels (`<label>`)
- Fieldset and Legend (`<fieldset>`, `<legend>`)
- Form Validation (Required fields, pattern, min/max values)

### 8. HTML Multimedia
- Embedding Audio (`<audio>` tag)
- Embedding Video (`<video>` tag)
- Using `<source>` for multiple formats
- Adding YouTube videos (`<iframe>`)

### 9. HTML Semantic Elements
- `<header>`, `<nav>`, `<section>`, `<article>`, `<aside>`, `<footer>`, `<main>`, `<figure>`, `<figcaption>`
- Importance of semantic HTML

### 10. HTML Block & Inline Elements
- Block-level elements (`<div>`, `<p>`, `<h1>`-`<h6>`, `<section>`)
- Inline elements (`<span>`, `<a>`, `<strong>`, `<em>`)

### 11. HTML Forms with Advanced Features
- Hidden Inputs
- Autofocus & Placeholder
- HTML5 Form Validation
- Datalist (`<datalist>`)
- Disabled & Readonly attributes

### 12. HTML Meta Tags & SEO
- `<meta charset="UTF-8">`
- `<meta name="viewport">`
- `<meta name="description">`
- `<meta name="keywords">`
- `<meta name="author">`
- Open Graph Meta Tags (For social media sharing)

### 13. HTML Entities & Symbols
- `&nbsp;` (Non-breaking space)
- `&lt;` `<`, `&gt;` `>`
- `&amp;` `&`
- `&copy;`, `&reg;` (Copyright, Registered)
- `&euro;`, `&yen;`, `&pound;` (Currency symbols)

### 14. HTML Iframes
- Embedding websites (`<iframe src="URL">`)
- Iframe Attributes (`width`, `height`, `frameborder`, `allowfullscreen`)

### 15. HTML Canvas & SVG
- Drawing with `<canvas>` (JavaScript required)
- Scalable Vector Graphics (`<svg>`)

### 16. HTML Web Storage
- Local Storage (`localStorage`)
- Session Storage (`sessionStorage`)

### 17. HTML APIs
- Geolocation API
- Drag & Drop API
- Web Workers
- WebSockets
- Fetch API

### 18. HTML Accessibility (A11Y)
- ARIA Attributes (`role`, `aria-label`, `aria-hidden`)
- Keyboard Navigation
- Screen Reader Support

### 19. HTML Responsive Design
- Viewport Meta Tag
- Using CSS Media Queries
- Responsive Images
- Flexbox & Grid Layout

### 20. HTML Best Practices
- Clean Code Formatting
- Proper Use of Semantic Tags
- Accessibility Considerations
- SEO Optimization
- Performance Optimization (Lazy Loading, Minification)

### 21. HTML5 New Features
- New Form Elements (`<datalist>`, `<output>`)
- New Input Types (`email`, `number`, `range`, `date`)
- New Multimedia Elements (`<audio>`, `<video>`, `<source>`)
- Native Drag and Drop
- Web Storage & Local Storage

## Getting Started
To start learning HTML, you can:
1. Clone this repository:
   ```sh
   https://github.com/hasibulhimu49/HTML-CSS.git
   ```
2. Open the files in a browser or code editor (VS Code recommended).

## Resources
- [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [W3Schools](https://www.w3schools.com/html/)



  

# CSS Complete Guide

## Overview
CSS (Cascading Style Sheets) is used to style HTML elements and control the layout of web pages. This guide covers all essential CSS topics.


## CSS Topics Covered

## 1. Basics of CSS
- What is CSS?
- Types of CSS (Inline, Internal, External)
- CSS Syntax & Selectors
- CSS Comments

## 2. CSS Selectors
- Universal Selector (`*`)
- Element Selector (`p, h1, div`)
- ID Selector (`#id`)
- Class Selector (`.class`)
- Grouping Selector (`h1, p, div`)
- Attribute Selectors (`[type="text"]`, `[href^="https"]`)
- Pseudo-classes (`:hover`, `:focus`, `:nth-child(n)`)
- Pseudo-elements (`::before`, `::after`)

## 3. CSS Properties
### Text & Font Properties
- `color`, `font-size`, `font-family`, `font-weight`
- `letter-spacing`, `word-spacing`, `line-height`
- `text-align`, `text-decoration`, `text-transform`

### Box Model
- `width`, `height`, `max-width`, `max-height`
- `margin`, `padding`, `border`, `outline`
- `box-sizing`, `display`, `visibility`

### Backgrounds & Borders
- `background-color`, `background-image`, `background-position`
- `background-repeat`, `background-size`, `background-attachment`
- `border-style`, `border-width`, `border-color`
- `border-radius`, `box-shadow`

## 4. CSS Layout & Positioning
- `display` (block, inline, inline-block, flex, grid)
- `position` (static, relative, absolute, fixed, sticky)
- `top`, `bottom`, `left`, `right`
- `z-index`

## 5. CSS Flexbox
- `display: flex`
- `flex-direction`, `flex-wrap`, `flex-flow`
- `justify-content`, `align-items`, `align-content`
- `order`, `flex-grow`, `flex-shrink`, `flex-basis`

## 6. CSS Grid
- `display: grid`
- `grid-template-columns`, `grid-template-rows`
- `grid-gap`, `grid-auto-rows`, `grid-auto-columns`
- `align-items`, `justify-items`, `place-items`

## 7. CSS Transforms & Animations
- `transform` (rotate, scale, translate, skew)
- `transition` (duration, delay, timing-function)
- `animation` (keyframes, duration, iteration, easing)

## 8. CSS Responsive Design
- `media queries` (`@media screen and (max-width: 600px)`)
- `viewport meta tag` (`<meta name="viewport" content="width=device-width, initial-scale=1">`)
- `rem`, `em`, `vh`, `vw`, `%` units
- `flexbox` & `grid` for responsiveness

## 9. Advanced CSS Concepts
- CSS Variables (`--primary-color`)
- CSS Preprocessors (SASS, LESS)
- CSS Custom Properties
- CSS Clipping & Masking
- CSS Scroll Snap
- CSS Subgrid

## 10. CSS Frameworks & Libraries
- Bootstrap
- Tailwind CSS
- Materialize
- Bulma

## Conclusion
This guide provides a structured approach to mastering CSS. Keep practicing and experimenting with different styles to enhance your web development skills!


