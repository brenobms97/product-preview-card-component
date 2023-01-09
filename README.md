# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

#### Mobile
![](screenshot/mobile.png)

#### Desktop
![](screenshot/desktop.png)


### Links

- Live Site URL: [Product preview card component](https://effortless-kleicha-56689a.netlify.app)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

The major learning that I had was the media query property from CSS.

```css
.card {
    background-color: var(--white-n);
    border-radius: 0.6rem;
    overflow: hidden;
    max-width: 343px;
  }

  @media (min-width: 600px) {
    .card {
        display: grid;
        grid-template-columns: 1fr 1fr;
        max-width: 600px;
    }
  }
```

### Useful resources

- [Custom CSS Reset](https://www.joshwcomeau.com/css/custom-css-reset/) - This tutorial show step-by-step a better way to reset the CSS.

## Author

- Frontend Mentor - [@brenobms97](https://www.frontendmentor.io/profile/brenobms97)


## Acknowledgments

I would like to thank [Kevin Powell](https://www.youtube.com/watch?v=B2WL6KkqhLQ&ab_channel=KevinPowell) for the wonderful and explanatory video he made about the challenge. 
