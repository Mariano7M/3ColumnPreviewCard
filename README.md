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
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./screenshots/desktop-screenshot.jpg)
![](./screenshots/mobile-screenshot.jpg)

### Links

- Solution URL: [GitHub Repository](https://github.com/Mariano7M/3ColumnPreviewCard)
- Live Site URL: [GitHub page](https://mariano7m.github.io/3ColumnPreviewCard/)

## My process

In order to complete this challenge I started with the structure of the content in the HTML file. Once I had the structure I started with the styles. I put the fonts and variables that I was going to use on the classes. Then I continued with the colors for the cards. And for the responsive part I used Flexbox, but this time I decided to style the mobile design.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I still learnging about flexbox, so I used to make the page responsive and I think a did a better work this time.

```css
.container {
  display: flex;
  flex-direction: column;
  align-items: stretch;
  justify-content: flex-start;
  align-content: space-between;
  height: auto;
}

.card-preview {
  background-color: violet;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  align-content: center;
  width: 90%;
  margin: 3rem auto;
  border-radius: 10px;
  overflow: hidden;
}

.card {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
  padding: 2.5em;
}

@media (min-width: 850px) {
  .container {
    height: 100vh;
  }

  .card-preview {
    flex-direction: row;
    justify-content: center;
    align-items: stretch;
    margin: 8rem auto;
    width: min(80%, 1000px);
  }

  .card {
    justify-content: space-around;
  }
}


```

### Continued development

I decided tp use Flexbox to make this page responsive. But I think I need to learn more about how to use the breakpoints. 

### Useful resources

- [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This page has a complete guide on how to use Flexbox.
- [Flexbox Playground](https://flexbox.tech/) - On this page you can play with all the properties of flexbox and watch how flexbox works

## Author

Mariano Mogica

- Frontend Mentor - [@Mariano7M](https://www.frontendmentor.io/profile/Mariano7M)
- Twitter - [@10MARINHO](https://twitter.com/10MARINHO)

