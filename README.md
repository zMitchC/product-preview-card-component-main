# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

Desktop design screenshot<br>
![Desktop design screenshot](./screenshots/desktop.design_screenshot.png)

Mobile design screenshot<br>
![Mobile design screenshot](./screenshots/mobile.design_screenshot.png)

### Links

- Live Site URL: [GitHub Page](https://zmitchc.github.io/product-preview-card-component-main/)

## My process

I started with all the structure in [index.html](index.html) adding the containers I needed and named them.

After finished structuring, I started working on the style in [main.css](./public/stylesheet/main.css). Initially I set up the main container size and center it. Then I put the desktop image on the left using the `float` attribute, as well for the content container. After I had everything done with the desktop version, It was time to work on accessibility: using **@media queries** I made the site responsive to the size of the screen users are using. I did it for two types of screen: the `@media only screen and (max-width: 600px)` is for generic mobile devices with 600px or less. The second one, `@media only screen and (max-width: 300px)`, I did it in particular for the Galaxy Fold, which has a very tight screen.

That's all folks! Hope you have a great day!

### Built with

- HTML
- CSS

### What I learned

I learned more about accessibility and responsiveness, in particular using **@media queries**.

### Continued development

A thing that I want to get better and improve is the repsonsiveness of a page and being able to make a site accessible to every device.


### Useful resources

- [@media queries](https://www.w3schools.com/cssref/css3_pr_mediaquery.php) - This made me understand how @media queries work to make the website accessible.

## Author

- GitHub - [zMitchC](https://github.com/zMitchC)
- Frontend Mentor - [@zMitchC](https://www.frontendmentor.io/profile/yourusername)
