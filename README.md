# Code: Advanced CSS and SASS Flexbox Grid Animations and More!

This README will be acting as short & speedy notes for the above-mentioned course. The notes which you can see below are being prepared by myself & [Vedant](https://github.com/MarkVed17). Feel free to create a PR to add new notes if these notes get deprecated. Thank you! 😇

---

## Building the Header - Part 1

- [box-sizing: border-box](https://developer.mozilla.org/en-US/docs/Web/CSS/box-sizing);
- [background-image: linear-gradient(
  to right bottom,
  rgba(126, 213, 111, 0.8),
  rgba(40, 180, 131, 0.8)
  ),
  url(../img/hero.jpg);](<https://developer.mozilla.org/en-US/docs/Web/CSS/gradient/linear-gradient()>)
- [background-size: cover;](https://developer.mozilla.org/en-US/docs/Web/CSS/background-size)
- [background-position: top;](https://developer.mozilla.org/en-US/docs/Web/CSS/background-position)
- [clip-path: polygon(0 0, 100% 0, 100% 75vh, 0 100%);](https://developer.mozilla.org/en-US/docs/Web/CSS/clip-path)

---

## Building the Header - Part 2

The easiest way to transorm anything with the `transform, top and left` properties.

- [`absolute` & `relative` positioning](https://developer.mozilla.org/en-US/docs/Web/CSS/position)

- [block level elements](https://developer.mozilla.org/en-US/docs/Web/HTML/Block-level_elements)

- span is by default an inline element

- [display: block;](https://developer.mozilla.org/en-US/docs/Web/CSS/display)

- [text-transform: uppercase;](https://developer.mozilla.org/en-US/docs/Web/CSS/text-transform)

- [letter-spacing: 35px;](https://developer.mozilla.org/en-US/docs/Web/CSS/letter-spacing)

- [transform: translate(-50%, -50%);](https://developer.mozilla.org/en-US/docs/Web/CSS/transform)

---

## Creating Cool CSS Animations

- [animation](https://developer.mozilla.org/en-US/docs/Web/CSS/animation)

- animation-name: moveInLeft;

- animation-duration: 2s;

- animation-delay: 3s;

- animation-iteration-count: 3;

- animation-timing-function: ease-out;

- All combined

  animation: moveInRight 1s ease-out;

- backface-visibility: hidden;

---

## Building a Complex Animated Button - Part 1

- [pseudo class in CSS](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes)

---

## Building a Complex Animated Button - Part 2

---
## How CSS Works : A Look Behind The Scenes

### Three Pillars of Writing Good HTML and CSS

- Responsive design

  - Fluid layouts
  - Media queries
  - Responsive images
  - Correct units
  - Desktop-first vs mobile-first

- Maintainable and scalable code

  - Clean
  - Easy-to-understand
  - Growth
  - Reusable
  - How to organize files
  - How to name classes
  - How to structure HTML

- Web performance
  - Less HTTP requests
  - Less code
  - Compress code
  - Use a CSS preprocessor
  - Less images
  - Compress images

---

## How CSS Works Behind The Scenes: An Overview

### What happens to CSS when we load up a webpage?

![css-behind the  scenes](images-README\css-behind-the-scenes.png)

### Things to note:

Visual Formatting Model

---

## How CSS is Parsed. Part 1: The Cascade and Specificity

![css-terminology](images-README\css-terminology.png)
![css-cascade](images-README\css-cascade-1.png)
![css-cascade](images-README\css-cascade-2.png)
![css-cascade](images-README\css-cascade-3.png)
![css-cascade-takeaway](images-README\css-cascade-takeaway.png)

Author declaration: CSS by the coder or developer

User declaration: CSS by the user. Example, when user changes default browser font-size.

Browser (user agent) declaration: CSS by the browser. Example, anchor tag in HTML has deafult color purple and an underline.

---
## Specificity in practice


---

## How CSS is Parsed. Part 2: Value Processing

---

## How CSS is Parsed. Part 3: Inheritance

---

# resources

http://codingheroes.io/resources/