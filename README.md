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
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned
In this fontend mentor challenge I learn the following things: How to arrange a grid element, How to make transparent color cover on image and also I'm able to make a grid columns with auto-fit but I don't get what I want in mobile version (i.e I couldn't make the width of the card right on mobile version but it works for desktop version) if someone know why is this happening please tell me.

Here is the code snippet I use.

```css
@media screen and (min-width: 50em){
  .card {
     grid-template-columns: reapet(auto-fit, minmax(min(35rem, 100%), 1fr));
}
```

### Continued development

I solve a couple of fontend mentors challenges. It helps me so much to solidify my knowledge on different topics, but same of the challenges are quite hard to solve, specially re-creating a full home page. I try a couple of times but I can't do it. I would like to know how should I approach such kind of challenges, and what things should be consider before doing it???

## Author

- Frontend Mentor - [@Gskds](https://www.frontendmentor.io/profile/Gskds)