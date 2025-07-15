# Frontend Mentor - Blog Preview Card Solution

This is my solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS).  
It helped me improve my HTML and CSS layout skills by building a responsive card component.

---

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

---

## Overview

### The challenge

Users should be able to:

- View the blog preview card and its content
- See hover and focus states for interactive elements
- View the layout correctly on mobile and desktop screens

---

### Screenshot

![Blog preview card screenshot](./preview.jpg)

> 📸 Save your screenshot as `screenshot.jpg` in the same folder as this `README.md`

---

### Links

- 🔗 **Solution URL:** [My GitHub Repo](https://github.com/alexx021dev/Blog-Card))
- 🔗 **Live Site URL:** [Live Demo](https://alexx021dev.github.io/Blog-Card/)

---

## My process

### Built with

- Semantic HTML5
- CSS custom properties
- Flexbox
- Media queries (mobile-first approach)
- Modern CSS functions like `min()`, `max()`

---

### What I learned

I learned how to:

- Center containers both vertically and horizontally using Flexbox

- Use `min()`, `max()`, and `border-radius` to build a responsive, clean UI

- Handle responsive layout using media queries

- Use `box-shadow` and color to add depth and contrast

```css
.container {
  width: min(90%, 400px);
  margin: auto;
  padding: 1.2rem;
  border-radius: 1rem;
  box-shadow: 5px 10px 0 black;
}
