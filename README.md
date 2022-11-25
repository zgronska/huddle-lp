# Frontend Mentor - Huddle landing page with single introductory section solution

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

<center>
  <img src="./images/final-ss-desktop.png" width="100%" height="auto">
  <img src="./images/final-ss-mobile.png" width="auto" height="600px">
</center>

### Links

- Solution URL: [GitHub](https://github.com/zgronska/huddle-lp)
- Live Site URL: [GitHub Pages](https://zgronska.github.io/huddle-lp/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [Font Awesome](https://fontawesome.com/) - For styles
- LOTS of Googling

### What I learned

This is the first project where I worked extensively on a grid layout, and it's been a huge challenge - the layout still isn't pixel perfect as in the design.

```css
.container {
  grid-template-columns: minmax(0, 1.5fr) minmax(0, 1fr);
  gap: 1rem 1rem;
  height: calc(100vh - 2rem);
  margin: 1rem 3rem;
  align-content: center;
  align-items: center;
}
```

I also learned how to scale text based on viewport size.

```css
body {
  font-size: 2.5vmin;
}
```

### Continued development

In future project, I definitely have to brush up my knowledge of grid, and layouts in general.

### Useful resources

- [Grid Cheat Sheet](https://grid.malven.co/) - The holy bible.
- [Viewport Sized Typography](https://css-tricks.com/viewport-sized-typography/) - Awesome resource about responsive text scaling.
- [CSS Reset](https://www.joshwcomeau.com/css/custom-css-reset) - Custom CSS reset by Josh Comeau.

## Author

- GitHub - [zgronska](https://github.com/zgronska)
- Frontend Mentor - [@zgronska](https://www.frontendmentor.io/profile/zgronska)
