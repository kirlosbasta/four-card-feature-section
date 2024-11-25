# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK).

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

this is a simple four card feature section that is responsive and mobile first. I used flexbox to align the cards.

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./images/Screenshot%202024-11-26%20011720.png)
![](./images/Screenshot%202024-11-26%20012226.png)

### Links

- Live Site URL: <https://kirlosbasta.github.io/four-card-feature-section/>

## My process

I started by mobile first and then I used media queries to make the site responsive.

for the desktop version I used flexbox to align the cards into three columns, the middle two cards are wrapped in a div to make them in the center of the page.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I learned using margin to push elements to either side of the page, the tricky part was to turn the image to block in order for the margin to work.

```css
.card__img {
  display: block;
  margin-left: auto;
}
```

## Author

- Frontend Mentor - [@kirlosbasta](https://www.frontendmentor.io/profile/kirlosbasta)
- LinkedIn - [kirlos-basta](https://www.linkedin.com/in/kirlos-basta/)
