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

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the app depending on their device's screen size
- See hover states for all interactive elements on the page
- Select and submit a number rating
- See the "Thank you" card state after submitting a rating

### Links

- Solution URL: [https://github.com/lesandra007/interactive-rating-component](https://github.com/lesandra007/interactive-rating-component)
- Live Site URL: [https://rococo-halva-3fc346.netlify.app/](https://rococo-halva-3fc346.netlify.app/)

## My process

### Built with

- Visual Studio Code - To write code
- Netlify - To deploy website

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
