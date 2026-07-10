# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ).  

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: https://github.com/MaxPlummer/social-links-profile
- Live Site URL: https://maxplummer.github.io/social-links-profile/

## My process

### Built with

- Semantic HTML5 markup
- CSS classes
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I learned how to implement a @font-face rule to utilize a variable font file. Being able to use a single variable file as opposed to several static files is simpler and more centralizes, which I appreciate very much. 
```css
@font-face {
  font-family: "Inter";
  src: url("./assets/fonts/Inter-VariableFont_slnt,wght.ttf") format("truetype");
  font-weight: 100 900;
  font-style: normal;
  font-display: swap;
}
```
I also decided to use a CSS grid for the layout of the profile card itself, which was quite easy. I have used flexbox often, including in this project, and it was interesting seeing how grid behaves compared to flex on the same page. 
```css
display: grid;
place-items: center;
```

### AI Collaboration

This project was coded with the occasionally use of GitHub Copilot to remind me of syntax rules and attributes. I mostly used the agent for debugging when identifying the root causes for some unintended behavior on the page. 

I tend to use AI as a supplementary resource to help me learn and understand more about proper web development practices, rather than as a primary source of code. 

## Author

- Website - [Max Plummer](https://github.com/MaxPlummer)
- Frontend Mentor - [@MaxPlummer](https://www.frontendmentor.io/profile/MaxPlummer)
- LinkedIn - [Maxwell Plummer](https://www.linkedin.com/in/maxwell-plummer-1b2b13291/)
