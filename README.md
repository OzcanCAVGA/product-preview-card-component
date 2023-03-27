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
- [Author](#author)

## Overview

In this project, the task was to design a product preview card component. The card was designed using HTML, CSS, and JavaScript and the user experience was optimized for both mobile and desktop devices.

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

**Desktop Version**
![desktop](./screenshot/desktop.png)

**Mobile Version**

![mobile](./screenshot/mobile.png)



### Links

- Live Site URL: [Add live site URL here](https://product-preview-card-component-jet-mu.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow




### What I learned

While designing this project, I learned the use of max-width, combining `flexbox` and `grid` and using `overflow: hidden;` to prevent images from overflowing outside their container.


`overflow`
```css
.box{
overflow:hidden;
}
```
`flexbox`
```css
.main-content {
    display: flex;
    flex-direction: column;
    margin: 2rem;

}
```
`grid`
```css
.box {
    display: grid;
    grid-template-columns: 1fr 1fr;
}
```


## Author


- Frontend Mentor - [@OzcanCAVGA](https://www.frontendmentor.io/profile/OzcanCAVGA)
- Twitter - [@OzcanCAVGA](https://www.twitter.com/ozcanCAVGA)
- LinkedIn - [@ozcancavga](https://www.linkedin.com/in/ozcancavga/)


