# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

Animated on hover card with QR code and description

### Screenshot

![](./images/solution_screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I used here workaround to add placeholder to image while it doesn't load yet. There is an example how to use it:

```html
<div class="parent-div">
  <image class="img" ...></image>
</div>
```

```css
.parent-div {
  position: relative;
  padding-top: 100%;
  /* add here background image or color */
}

.img {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
}
```

### Useful resources

- [CSS BOX-SHADOW GENERATOR](https://active-vision.ru/icon/box-shadow/) - great CSS box-shadow generator
