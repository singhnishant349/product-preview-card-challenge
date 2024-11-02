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


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

- DESKTOP

![](./design/desktop-design.jpg)

- MOBILE

![](./design/mobile-design.jpg)

- HOVER

![](./design/active-states.jpg)


### Links

- Live Site URL: [Click Here...](https://singhnishant349.github.io/product-preview-card-challenge/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

This project includes text elements specifically designed to enhance accessibility for visually impaired users. These elements are not intended to be seen visually but are included to provide additional context and support for screen readers, ensuring a more inclusive user experience.

To see how you can add code snippets, see below:

```html
    <div class="product__price">
      <p class="product__new-price font-size_family"><span class="visually-hidden">Current Price</span>$149.99</p>
      <p class="product__original-price "><span class="visually-hidden">Original Price</span><s>$169.99</s></p>
    </div>
```
```css
.visually-hidden:not(:focus):not(:active) {
  clip: rect(0 0 0 0);
  clip-path: inset(50%);
  height: 1px;
  overflow: hidden;
  position: absolute;
  white-space: nowrap;
  width: 1px;
}
```

### Useful resources

- [Joshwcomeau.com](https://www.joshwcomeau.com/css/custom-css-reset/) - This helped me for custom-css-rest. I really liked this pattern and will use it going forward.

## Author

- Website - [Nishant Singh](https://singhnishant349.github.io/craftedbynish/)
- Frontend Mentor - [@singhnishant349](https://www.frontendmentor.io/profile/singhnishant349)



