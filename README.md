# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- View an order summary card with dynamic pricing
- See hover states for interactive elements
- Experience responsive design across devices

### Screenshot

![](./images/Screenshot%202025-02-19%20061140.png)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5
- CSS Custom Properties (CSS Variables)
- Flexbox
- Mobile-First Workflow
- CSS Media Queries

### Key Features

- Responsive design optimized for mobile (375px) and desktop (1440px)
- Interactive hover states for buttons and links
- CSS custom properties for consistent theming
- Clean component-based structure

### What I learned

1. **CSS Positioning**: Implemented absolute positioning for perfect centering:

```css
section {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}
```

2. **Dynamic Styling**: Utilized CSS variables for theme management:
```css
:root {
  --bright-blue: hsl(245, 75%, 52%);
  --desaturated-blue: hsl(224, 23%, 55%);
}
```

3. **Responsive Design**: Media queries for mobile adaptation:

```css
@media screen and (max-width: 768px) {
  main {
    background-image: url("../images/pattern-background-mobile.svg");
  }
}
```

### Continued development

- Implementing CSS Grid for complex layouts
- Adding accessibility features (ARIA labels)
- Enhancing animation transitions
- Exploring CSS-in-JS solutionsinued development.**


## Author

- Website - [4MaxR](https://github.com/4MaxR)
- Frontend Mentor - [@4MaxR](https://www.frontendmentor.io/profile/4MaxR)

