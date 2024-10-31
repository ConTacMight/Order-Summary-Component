# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [What I learned](#what-i-learned)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![](./images/screenshot.png)

### Links

- Solution URL: [https://github.com/ConTacMight/Order-Summary-Component](https://github.com/ConTacMight/Order-Summary-Component)
- Live Site URL: [https://contacmight.github.io/Order-Summary-Component/](https://contacmight.github.io/Order-Summary-Component/)

## My process

### What I learned

Before this guided project, I only had a basic understanding of HTML and CSS; the advanced interactions and options within properties and alluded me. This project taught me more about styling and practices that I should apply to make my code more legible and easier to manipulate later.

- There's default css properties that can be overwritten

```css
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
```

- Unique color names can be designated and used with var()

```css
:root {
  --uniquename: hsl(225, 100%, 94%);
}
body {
  background-color: var(--uniquename);
}
```

- Alignment of items and boxes are intricate and require trial and error, especially when coding for responsiveness on smaller screens.
- Shorthand techniques for padding, margin, etc.

```css
.order-description {
  padding: 5px 20px 20px 20px;
}
```

## Acknowledgments

Thank you to [freeCodeCamp](https://www.freecodecamp.org/) and [Madison Kanna](https://www.youtube.com/c/MadisonKanna) for a clear and concise guided tutorial for a better understanding of HTML basics and CSS tips that help create clean and efficient code.
