# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

<p>
  <img src="images/Testimonials Grid Section (desktop).png" height="300" hspace="15">
  <img src="images/Testimonials Grid Section (mobile).png" height="300" hspace="15">
</p>

### Links

- [Solution URL](https://www.frontendmentor.io/solutions/using-grid-to-position-layout-uIU_rvKf1S)
- [Live Site URL](https://retroape.github.io/testimonials-grid-section-main/)

## My process

- Think about the layout, choices I should make when choosing HTML elements
- Think about the possible solutions to the layout
- Research Grid
- Started with Desktop; tried to match the layout as much as possible
  - Did the same for the font size as well, margins too
- When the overall layout was done, next step was to match the details
- Did the same for mobile layout
- Went back and forth between the design and my current status to match the details as much as possible

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Desktop-first workflow

### What I learned

- How to better use Grid
  - It seems that specifying rows is not necessary for the grid layout, which is why it is commented out

```css
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    /* grid-template-rows: 1fr 1fr; */
    grid-template-areas: 
        'a a b e'
        'c d d e';
    column-gap: 1.875rem;
    row-gap: 1.5rem;
```

## Author

- Frontend Mentor - [@RetroApe](https://www.frontendmentor.io/profile/RetroApe)
- LinkedIn - [@tomislavsuto81](https://www.linkedin.com/in/tomislavsuto81)

