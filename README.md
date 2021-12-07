# Frontend Mentor - FAQ accordion card solution

This is a solution to the [FAQ accordion card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/faq-accordion-card-XlyjD0Oam). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See hover states for all interactive elements on the page
- Hide/Show the answer to a question when the question is clicked

### Screenshot

![](./design/my-solution.png)

### Links

- Solution URL: [GitHub](https://github.com/marisudris/frontend-mentor-faq-accordion-card)
- Live Site URL: [GitHub Pages](https://marisudris.github.io/frontend-mentor-faq-accordion-card/)

## My process

As always - first I came up with a markup that is both semantic, accessible, and provides the necessary styling hooks. This time a correct markup was also necessary for a proper behavior - I used the `<detail>` and `<summary>` elements for the _accordion_ section - this way I could do this project without JavaScript.  
Afterwards I did the mobile layout first with the top-down approach: styling larger sections
first an then going smaller and more detailed. Coming up with proper styling & the best markup for
images took a pretty long time. The accordion section wasn't as time-consuming as I thought it
would be. As always it took some effort to decide the proper spacing. Here I didn't try to go as _pixel-perfect_
as I usually do.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I learned to pay attention to image details - particularly when an image overflows and when it gets
clipped within its parent container's boundaries. Since background images get clipped and markup images
can overflow (if we use `transform: translate` or negative `margins` as in my case) the solution pretty much reveals itself (that and also convenient names for asset images - ones starting with `bg-..` are probably meant to be background images).

### Continued development

I'll probably do some more research on flex containers and how flex items behave when they only contain an image, and also recap on how intrinsic sizing relates to flex item size.

## Author

- Frontend Mentor - [@marisudris](https://www.frontendmentor.io/profile/marisudris)
- GitHub - [@marisudris](https://www.github.com/marisudris)
