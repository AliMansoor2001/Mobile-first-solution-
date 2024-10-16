# Frontend Mentor - Bento grid solution

This is a solution to the [Bento grid challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size

### Screenshot

![]("C:\Users\alima\Downloads\bento-grid-main\bento-grid-main\FireShot Capture 001 - Frontend Mentor - Bento grid - .jpg")

### Links

- Solution URL: file:///C:/Users/alima/Downloads/bento-grid-main/bento-grid-main/index.html


## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

I learnt about display grid properties, grid-auto-rows and grid-template-columns.

```html
<div class="container">
</div>
```
```css
.container {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  grid-auto-rows: minmax(100px, 200px);
}
```
Setting each content on it's position using grid-template areas.

```html
<div class="container">
</div>
```
```css
.container {
  grid-template-areas:
    "quick_content socialMedia socialMedia social_schedule"
    "AI_content multi_accs schedule social_schedule"
    "AI_content growth followers followers";
}
```

### Useful resources

- [MDN Grid System](https://developer.mozilla.org/en-US/docs/Web/CSS/grid) - used MDN Web docs for getting a basic idea of grid model.

## Author

- Website - [Ali Mansoor Qadir](file:///C:/Users/alima/Downloads/bento-grid-main/bento-grid-main/index.html)
- Frontend Mentor - [alimansoorqadirghumro@gmail.com](https://www.frontendmentor.io/profile/AliMansoor2001)
- Twitter - [@yourusername](https://www.twitter.com/alimansoorqadirghumro@gmail.com)

## Acknowledgments

I Acknowledge my friend Abu Bakr as he explained and assessed me in this project and clearing my doubts.

