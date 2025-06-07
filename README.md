# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](/testimonial-grid-screenshot.png)

## My process

I started by anaylzing the design. I noticed that a grid layout for the large screen size would be optimal. I then proceeded with mobile design first then updated media query as the screen increased.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

Writing the HTML markup had me a little confused with trying to position the elemtents within each individual card. After realzing that I needed a "container" for the header within the testimonial cards, the layout played nicely.

```html
<div class="testimonialCard">
  <div class="testimonialHeader">
    <img />
    <div>
      <p class="userDetails">
        User Name<br />
        <span>Verified Graduate</span>
      </p>
    </div>
  </div>
  <p class="testimonial">Lorem Ipsum</p>
  <p>“ Add quote here. ”</p>
</div>
```

## Author

- Frontend Mentor - [@pheight-89](https://www.frontendmentor.io/profile/pheight-89)
