# Frontend Mentor - Order summary card solution

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview
Building Order summary card using HTML and CSS only.

### The challenge

Users should be able to:

- See hover states for interactive elements


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS variables
- CSS pseudo

### What I learned

Adding button with active sulotion 

To see how you can add code snippets, see below:

```html
<div class="button">
     <button type="button" class="pay">Proceed to Payment</button>
</div>
```
```css
..button{
    display: flex;
    justify-content: center;
}

.pay{
    font-weight: 900;
    color: var(--Pale-blue);
    background-color: var(--Bright-blue);
    padding: 13px 65px;
    border-color: var(--Bright-blue);
    border-radius: 10px;
    -webkit-border-radius: 10px;
    -moz-border-radius: 10px;
    -ms-border-radius: 10px;
    -o-border-radius: 10px;
    
}

.pay:hover{
    background-color: hsla(245, 75%, 52%, 60%);
    border-color: hsla(245, 75%, 52%, 60%);
    cursor: pointer;
}
```
## Useful resources

- [google fonts](https://www.googlefonts.com) - This helped me choose the right font and wight for this solution.
- [w3schools](https://www.w3schools.com) - This is an amazing library that i go back always to get the right coding and solutions for my projects.

## Author

- Frontend Mentor - [@zinahzwayen](https://www.frontendmentor.io/profile/zinahzwayen)


