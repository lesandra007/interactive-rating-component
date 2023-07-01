# Frontend Mentor - Interactive rating component solution

This is a solution to the [Interactive rating component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/interactive-rating-component-koxpeBUmI). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the app depending on their device's screen size
- See hover states for all interactive elements on the page
- Select and submit a number rating
- See the "Thank you" card state after submitting a rating

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Visual Studio Code

### What I learned

First project using Javascript!!

To access and name a class: 
```js
const mainContainer = document.querySelector(".main-container")
```

To access and a name a group of the same class:
```js
const rates = document.querySelectorAll(".btn")
```

To access and name an id:
```js
const submitButton = document.getElementById("submit")
```

To add an Event Listener for a button:
```js
submitButton.addEventListener("click", () => {
    thanksContainer.classList.remove("hidden")
    mainContainer.style.display = "none"
})
```
Using forEach function:
```js
rates.forEach((rate) => {
    rate.addEventListener("click", () => {
        rating.innerHTML = rate.innerHTML
    })
})
```

### Useful resources

- [Interactive CSS Cheat Sheet](https://htmlcheatsheet.com/css/) - Visually play with elements and copy the code for it
- [GeeksforGeeks CSS Basic Guide](https://www.geeksforgeeks.org/css-cheat-sheet-a-basic-guide-to-css/#) - Explains the basics of CSS


## Acknowledgments

- [Solution by TsbSankara](https://youtu.be/cQnUopEeZgw)
