# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the site depending on their device's screen size

### Screenshot

Desktop

![](./screenshots/Frontend%20Mentor%20Four%20card%20feature%20section%20-%20Desktop.png)

Mobile

![](./screenshots/Frontend%20Mentor%20Four%20card%20feature%20section%20-%20Mobile.png)


### Links

- Solution URL: [Frontend Mentor](https://www.frontendmentor.io/solutions/four-card-feature-section-NKrZrjfEgd)
- Live Site URL: [GitHub](https://nicoams.github.io/four-card-feature-section/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- [Sass](https://sass-lang.com/) - CSS Preprocessor


### What I learned

The challenge on this one was displaying the cards using grid. Initialy I build a 2x3 grid, but it was not working. After some reflection, I ended up with the 4x3 code below:

```css
grid-template:
        ". two ." 1fr
        "one two four" 1fr
        "one three four" 1fr
        ". three ." 1fr
        / 1fr 1fr 1fr;
gap: 1.6rem;
```

It aligned vertically the first and the last card at the center of their column while all the cards kept the same size.


### Continued development

Even though I prefer to work with Flex, I intend to refine my knowledgments about Grid. I think it is important to know both of them. 

### Useful resources

- [Guia CSS Grid Layout](https://www.origamid.com/projetos/css-grid-layout-guia-completo/) - This guide has pretty much evertything about CSS Grid with lots of examples to illustrate its use in all kinds of situations.

## Author

- GitHub - [Nicholas Albuquerque](github.com/nicoams)
- Frontend Mentor - [@nicoams](https://www.frontendmentor.io/profile/nicoams)