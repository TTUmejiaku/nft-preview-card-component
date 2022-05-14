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
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./design/Desktop%20View%20-%20NFT%20preview%20card%20component.png)
![](./design/Mobile%20View%20-%20%20NFT%20preview%20card%20component.png)

### Links

- Solution URL: (https://github.com/TTUmejiaku/nft-preview-card-component)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

CSS positioning properties like relative and absolute - using it to control image overlay on hover.

```css
.img-container div {
  position: absolute;
  top: 0;
  margin-top: 1.5rem;
  background-color: hsl(178, 100%, 50%, 45%);
  height: 300px;
  width: 310px;
  z-index: 999;
  border-radius: 8px;
  opacity: 0;
  cursor: pointer;
  transition: opacity 0.3s ease-in-out;
}
```

## Author

- Frontend Mentor - [@TTUmejiaku](https://www.frontendmentor.io/profile/TTUmejiaku)
- Twitter - [@TTUmejiaku](https://www.twitter.com/TTUmejiaku)

## Acknowledgments
