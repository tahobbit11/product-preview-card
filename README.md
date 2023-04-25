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
  - [Continued development](#continued-development)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./images/Screenshot%202023-04-25%20162134.png)

### Links

- Solution URL: [https://www.frontendmentor.io/solutions/productpreviewcard-3iZpvZyLDv](https://www.frontendmentor.io/solutions/productpreviewcard-3iZpvZyLDv)
- Live Site URL: [https://tahobbit11.github.io/product-preview-card/](https://tahobbit11.github.io/product-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

I learned how to use display: grid; to break apart the mobile design into the the desktop design.

To see how you can add code snippets, see below:

```html
<div class="product-price">
          <h2 class="sale-price">$149.99</h2><span class="original-price">$169.99</span>
        </div>
```
```css
    .content-wrapper {
      grid-template-rows:0;
      grid-template-columns: repeat(2, 1fr);
      width: 600px;
      height: 450px;
      margin-left: auto;
      margin-right: auto;
      margin-top: 150px;
      margin-bottom: auto;
    }
```

### Continued development

I want to continue to learn how to use a grid display for later uses in my projects


## Author

- Frontend Mentor - [@tahobbit11](https://www.frontendmentor.io/profile/tahobbit11)

