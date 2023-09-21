# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-).

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

**Mobile**
![](/screenshot/mobile-screenshot.png)

**Desktop**
![](/screenshot/desktop-screenshot.png)

### Links

- Solution URL: [GitHub](https://github.com/mikailafsin/frontend-mentor-3-column-preview-card-component-solution)
- Live Site URL: [Vercel](https://frontend-mentor-3-column-preview-card-component-solution-rho.vercel.app)

## My process

### Built with

- HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- [Sass](https://sass-lang.com/) - CSS pre-processor

### What I learned

I coded this challenge using the Sass pre-processor, which I haven't practiced in a long time. I realized I forgot most things. I refreshed my knowledge by taking another look at the Sass pre-processor.

**Some scss codes I use:**

```scss
$brightOrange: hsl(31, 77%, 52%);
$darkCyan: hsl(184, 100%, 22%);
$veryDarkCyan: hsl(179, 100%, 13%);
$transparentWhite: hsla(0, 0%, 100%, 0.75);
$veryLightGray: hsl(0, 0%, 95%);
```
```scss
button {
  padding: .625rem 1.5rem;
  border-radius: 1.5rem;
  outline: none;
  background-color: $veryLightGray;
  font-weight: bold;
  border: 2px solid $veryLightGray;

  &:active {
      background-color: transparent;
  }
}
```
```scss
.card {
    padding: 2.5rem;
}
```
```scss
.bright-orange-card {
  @extend .card;
  background-color: $brightOrange;

  button {
    color: $brightOrange;

    &:active {
      color: $veryLightGray;
    }
  }
}
```

### Continued development

I will focus on improving my knowledge of the Sass pre-processor in future projects.

### Useful resources

[Sass Tutorial](https://www.w3schools.com/sass/default.asp) - This tutorial really helped me remember my knowledge about the Sass pre-processor. I'd recommend it to anyone still learning this concept.

## Author

- Frontend Mentor - [@mikailafsin](https://www.frontendmentor.io/profile/mikailafsin)
- Instagram - [@mikail.afsin](https://www.instagram.com/mikail.afsin)