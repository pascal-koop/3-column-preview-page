# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  
 
- [Author](#author)


**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements



### Links


- Live Site URL: [Add live site URL here](https://pascale-cheddar.github.io/3-column-preview-page/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- [Styled Components](https://styled-components.com/) - For styles



### What I learned



I learned to use custom properties to fasten design changes if needed.


```css
.:root {
  --background-sedans: hsl(31, 77%, 52%);
  --svg-sedans-color: hsl(42, 100%, 73%);
  --background-suvs: hsl(184, 100%, 22%);
  --svg-suvs-color: hsl(184, 67%, 45%);
  --background-luxury: hsl(179, 100%, 13%);
  --svg-luxury-color: hsl(170, 76%, 41%);
}

.cards .luxury-color path {
  fill: var(--svg-luxury-color);
}
.luxury {
  background-color: var(--background-luxury);
  border-radius: 0 0 2.5em 2.5em;
}
```







## Author

- Website - [Pascale](https://github.com/Pascale-Cheddar/Pascale-Cheddar)
- Frontend Mentor - [@Pascale-Cheddar](https://www.frontendmentor.io/profile/Pascale-Cheddar)






