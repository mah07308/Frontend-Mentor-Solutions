# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

![](./Screenshot%202023-05-26.png)

### Links

- Solution URL: [https://www.frontendmentor.io/solutions/responsive-nft-preview-card-component-BiEIcz-T31](https://www.frontendmentor.io/solutions/responsive-nft-preview-card-component-BiEIcz-T31)
- Live Site URL: [https://mah07308.github.io/FM-NFT-Preview-Card-Component/](https://mah07308.github.io/FM-NFT-Preview-Card-Component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

-To create an hover overlay over an image.

```html
<div class="image">
  <img src="" alt="" />
  <div class="overlay"></div>
</div>
```

```css
.image {
  position: relative;
}

.overlay {
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  height: 100%;
  width: 100%;
  opacity: 0;
  transition: 0.5s ease;
  background-color: hsla(178, 100%, 50%, 0.5);
  background-image: url('./images/icon-view.svg');
  background-repeat: no-repeat;
  background-position: center center;
  border-radius: 0.5rem;
}

.overlay:hover,
.overlay:active {
  opacity: 1;
  cursor: pointer;
}
```

- How to change color of hr element

```css
hr {
  background-color: hsl(215, 32%, 27%);
  height: 0.1rem;
  border: none;
}
```

### Useful resources

- [How TO - Image Hover Overlay](https://www.w3schools.com/howto/howto_css_image_overlay.asp)

## Author

- Frontend Mentor - [@mah07308](https://www.frontendmentor.io/profile/mah07308)
