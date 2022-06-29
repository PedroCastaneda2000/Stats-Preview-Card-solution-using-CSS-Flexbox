# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)

## Overview

In the Order Summary challenge, I was tasked to mirror the design of an example Stats Previw Card page.

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Links

- Solution URL: [https://github.com/pgc0004/Stats-Preview-Card-solution-using-CSS-Flexbox.git]
- Live Site URL: [https://stats-preview-card-solution-using-css-flexbox.netlify.app]

## My process

1. Began with the HTML layout of the main background and the card's container. Then continued with the card's contents such as the main image, main text, and the main stats after centering the card's container with CSS Flexbox.

2. Next designed the layout of the CSS with a Mobile First Approach. Began with global paramenters and variables. Then continued to style the card's contents using responsive sizing such as rem and percentage %.

3. Then designed the destop layout of the CSS using the @media with a min-width approach.

4. Lastly, the text and background color variables were added and implimented in the Global section.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

1. Learned to use the CSS @media to create a desktop layout. Then rearranging the card's contents the using CSS Flex. Basicily, learned to reverse engineer the commands used on the mobile version to fit the destop version.

2. Learned to use CSS background properties to create an overlay to the main image.

```css
.main-image {
  width: 100%;
  min-width: auto;
  height: 17rem;
  background: url(/images/image-header-mobile.jpg);
  background-size: cover;
  background-repeat: no-repeat;
  border-top-right-radius: 0.75rem;
  border-top-left-radius: 0.75rem;
}

.color-overlay {
  width: 100%;
  min-width: auto;
  height: 17rem;
  background: var(--bg-accent-strongViolent);
  opacity: 0.5;
  border-top-right-radius: 0.75rem;
  border-top-left-radius: 0.75rem;
}
```

```

### Continued development

In the future, I would like to better understand the creation of overlays on images. Additionally, I would like to try CSS Grid instead of CSS Flexbox to complete this challenge to determine the shortest approach.

```
