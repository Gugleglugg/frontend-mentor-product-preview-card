# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
 - [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
 


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

(./screenshot.jpg)


## My process

### Built with

- CSS custom properties
- Flexbox
- Mobile-first workflow
- Accessibility (screenreader-only text)


### What I learned

I've learned A LOT.

First and foremost, I've learned *one of the ways to make the browser display a different image file depending on viewport width*. I originally wanted to use the solution from MDN, but for whatever reason it refused to work in my case. So I did a simple 

````css
 .desktop-image { display: none; }
 ```` 

 thingy and then wrote a media query that set the mobile image to hidden and made the desktop image show up instead. Probably not the most elegant solution, but it works.

 I also practiced adding screenreader-only text. I have to admit I'd almost forgotten about it, and then I stumbled across a video of Kevin Powell doing this same challenge and making use of screenreader-only text.


### Continued development

Note to self: never forget accessibility.

