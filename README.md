# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Links

- Solution URL: [https://github.com/hugo-marroquin/NFT-preview-card-component]
- Live Site URL: [https://nft-preview-card-component-fm6.netlify.app/]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Desktop-first workflow

### What I learned

Adding a hover effect on an image.

```css
.container .overlay {
  position: absolute;
  background: hsla(178, 100%, 50%, 0.5);
  border-radius: 0.5rem;
  height: 100%;
  width: 100%;
  top: 0;
  align-items: center;
  justify-content: center;
  opacity: 0;
}

.container .overlay:hover {
  cursor: pointer;
  opacity: 1;
  transition: all 0.5s;
}
```

### Continued development

- Keeping Semantic HTML in mind as I build my projects.
- Refactoring my code to find ways to keep it DRY.
