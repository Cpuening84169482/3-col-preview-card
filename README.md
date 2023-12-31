# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![Desktop View](images/desktop_view.PNG)


### Links

- Live Site URL: [3 column preview card](https://cpuening84169482.github.io/3-col-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow

### What I learned

I reinforced my knowledge of using CSS Grid, and line heights.

```css
.cyan{
    background-color: hsl(0, 0%, 95%);
    color: hsl(184, 100%, 22%);
    padding: 6%;
    border: solid 2px hsl(0, 0%, 95%);
    text-align: center;
    margin: 3%;
    border-radius: 30px;
    width: 60%;
    font-size: 15px;
    transition-duration: 0.1s;
    font-family: "Lexend Deca";

}

.cyan:hover{
    cursor: pointer;
    color: hsl(0, 0%, 95%);
    border: 2px solid hsl(0, 0%, 95%);
    background-color: hsl(184, 100%, 22%);
    padding: 6%;
    text-align: center;
    margin: 3%;
    border-radius: 30px;
    width: 60%;
    font-size: 15px;
    transition-duration: 0.1s;
    font-family: "Lexend Deca";

}
```

### Useful resources

- [W3Schools](https://www.w3schools.com/html/html_css.asp) - This website is a good reference for learning CSS and HTML. I reference it quite frequently when I forget certain things.

## Author

- Frontend Mentor - [@Cpuening84169482](https://www.frontendmentor.io/profile/Cpuening84169482)
