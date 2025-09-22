# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![A screenshot of my social links profile page](./assets/images/screenshot-social-links-profile.png)

### Links

- Solution [here](https://github.com/odunlemi/social-links-profile)
- Live Site [here](https://odunlemi.github.io/social-links-profile/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


### What I learned

I wrote better code with this challenge as it's very similar to the [blog preview challenge](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). It's designed mobile-first and responsive across various screen sizes. I learnt to use local font files with `@font-face`, vars for the colors instead of pasting the hsl colors into every rule and learnt a new way of grouping media queries.

```css
@font-face {
    font-family: "Inter";
    src: url(./assets/fonts/Inter-VariableFont_slnt\,wght.ttf) format("truetype");
}
```
```css
:root {
    --green: hsl(75, 94%, 57%);
    --white: hsl(0, 0%, 100%);
    --grey-700: hsl(0, 0%, 20%);
    --grey-800: hsl(0, 0%, 12%);
    --grey-900: hsl(0, 0%, 8%)
}
```
```css
@media screen and (min-width: 600px) and (max-width: 699px), (min-width: 700px) {
  /* Larger screen styles here */
}
```

### Continued development

- ~~The social links are `a` tags in `div`s, it works but you'd have to hover over the text to click them. Change them to be `a` tags surrounding the whole `div`~~

- ~~Delete the font import tag, already using local font files~~ 

Now done

### Useful resources

- [CSS Variables - The var() Function](https://www.w3schools.com/css/css3_variables.asp) - This helped me set vars for color values

## Author

- Website - [Abiodun Longe](https://odunlemi.github.io/)
- Frontend Mentor - [@odunlemi](https://www.frontendmentor.io/profile/odunlemi)
- Twitter - [@odunlemi](https://www.x.com/odunlemi)