# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

Thanks for checking out this front-end coding challenge.

[Frontend Mentor](https://www.frontendmentor.io) challenges help you improve your coding skills by building realistic projects.

### The challenge

challenge is to build out this order summary card component and get it looking as close to the design as possible.

Users should be able to:

- See hover states for interactive elements

### Screenshot

![](./screenshot.jpg)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I made this project so i could keep practicing my flexbox skills and improve my workflow but, based in a feedback from a previous project i learned a better way to reduce the code while using border-radius with an image.

To see how you can add code snippets, see below:

```html
<div class="container">
    <img id="hero" src="images/illustration-hero.svg" alt="illustration hero">
```
```css
.container{
    position:relative;
    background-color: var(--Very-pale-blue);
    width:90%;
    max-width:500px ;
    margin:auto;
    padding-bottom:2.5em;
    border-radius:10px;
    overflow: hidden; /*used overflow so I don't have to edit the borders of the image with border-top-left/right-radius */
}
```

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.


### Useful resources

- (https://html-css-js.com/css/generator/box-shadow/) - Since I don't use box-shadow that much, I still need to practice it and memorize the values that it takes, anyway, this site is a faster way to design the shadow at the moment.
- (https://css-tricks.com/) - This is an amazing article which helped me finally understand flexbox. I'd recommend it to anyone still learning this concept.


## Author

- Website - [Alejandro Villaescusa Henriquez](https://www.facebook.com/alejandro.villaescusahenriquez/)
- Frontend Mentor - [@alexvillhen](https://www.frontendmentor.io/profile/alexvillhen)
- Twitter - [@Alexvillhen](https://www.twitter.com/Alexvillhen)


