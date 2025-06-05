# Frontend Mentor - Recipe Page Solution

This is my solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). The goal was to recreate a responsive recipe page layout based on a provided design. It includes a hero image, ingredients list, step-by-step instructions, and nutrition information – a great exercise for practicing semantic HTML, modern CSS, and layout structuring.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### Screenshot

![Screenshot of the recipe page](/assets/images/screenshot.png)

### Links

- Solution URL: [Frontend Mentor solution](https://www.frontendmentor.io/solutions/responsive-recipe-page-with-modern-css-no-media-queries-example-link)
- Live Site URL: [Live demo](https://your-live-demo-url.com)

## My process

### Built with

- Semantic HTML5
- Modern CSS (no framework)
- Flexbox
- CSS `max-width` layout
- Google Fonts (Young Serif & Outfit)
- No media queries – responsive by design
- Design token color values using HSL

### What I learned

This challenge helped me deepen my understanding of:

- Structuring clean, semantic HTML for content-heavy pages
- Using `box-sizing: border-box` and `max-width` for predictable, flexible layouts
- Styling ordered and unordered lists with custom `::marker` colors
- Creating visually subtle section dividers with borders
- Managing responsiveness **without media queries** by leaning on flexible units like `%`, `max-width`, and `auto`

```css
.white-box {
  max-width: 650px;
  width: 100%;
  margin: 0 auto;
  padding: 32px;
  background-color: white;
  border-radius: 20px;
}
```
