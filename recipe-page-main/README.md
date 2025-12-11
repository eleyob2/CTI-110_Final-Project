# CTI-110 Final Project - Simple Omelette Recipe Page

## Table of contents

- [Overview](#overview)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Challenges & Solutions](#challenges--solutions)
- [Author](#author)

## Overview

A responsive recipe page for a Simple Omelette Recipe built with semantic HTML5 and CSS. The page features a clean, modern design with proper typography, color scheme, and layout that adapts to different screen sizes.

### Links

- Repository URL: [CTI-110_Final-Project](https://github.com/eleyob2/CTI-110_Final-Project)
- Live Site: Open `index.html` in your browser

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties and variables
- Flexbox for layout
- CSS Grid for the nutrition table
- Google Fonts (Young Serif & Outfit)
- Responsive design principles

### What I learned

This project reinforced several key web development concepts:

**Semantic HTML Structure:**
```html
<section id="nutrition">
  <h2>Nutrition</h2>
  <div class="table">
    <div class="row">
      <span class="label">Calories</span>
      <span class="value">277kcal</span>
    </div>
  </div>
</section>
```
Using proper semantic elements like `<main>`, `<section>`, and structured lists improves accessibility and SEO.

**CSS Styling for Typography:**
```css
h1 {
    font-family: 'Merriweather', serif;
    font-weight: 900;
    color: black;
}

p, li {
    font-family: "Outfit", sans-serif;
    font-size: 15px;
    line-height: 1.5;
}
```
Proper font selection and line-height creates better readability and visual hierarchy.

**Styling List Markers:**
```css
#prep-time ul li::marker {
  color: hsl(332, 51%, 32%);
}
```
Using the `::marker` pseudo-element allows for custom styling of list item markers.

### Challenges & Solutions

- **Custom color scheme:** Implemented HSL color values for consistent and accessible color choices throughout the design
- **Typography balance:** Combined serif fonts for headings with sans-serif for body text to create visual interest while maintaining readability
- **Content organization:** Used semantic sections and proper heading hierarchy to structure recipe information logically

## Author

- **Elnatan Teaghes** - CTI-110 Final Project
- GitHub: [@eleyob2](https://github.com/eleyob2)
