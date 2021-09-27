# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- Build out the project to the designs provided

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [Solution on Frontend Mentor](https://www.frontendmentor.io/solutions/responsive-profile-card-using-html-css-and-flexbox-0AiuHN3aY)
- Live Site URL: [GitHub Page to Solution](https://pszponder.github.io/fem-profile-card-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

When creating a border radius on the parent element, the image or background on the child element may overflow over the parent element and obscure the border radius. In order to fix this, set the `overflow` property of the parent element to `hidden`. This will hide any items which overflow over the parent and therefore, will be able to see the radius on the parent.

Pseudo-elements `::before` and `::after` can be used to add additional styling or content to a webpage without the need of additional HTML elements.

### Continued development

Tis is only my 2nd project styling with CSS. In the future, I would like to revisit this component to determine if there is a more efficient way to style the CSS and structure the HTML. I may also look into incorporating a similar card to my portfolio with modified stats.

### Useful resources

- [Stack Overflow - Forcing child to obey parent's curved borders in CSS](https://stackoverflow.com/questions/3714862/forcing-child-to-obey-parents-curved-borders-in-css) - This helped me understand why I needed to use `overflow: hidden` on my card element in order to allow for the border radius to show up.

- [Kevin Powell - Before and After Pseudo elements explained](https://www.youtube.com/watch?v=zGiirUiWslI) - Kevin Powell is always a great resource for all things CSS. I learned a lot about the `::before` and `::after` pseudo-elements and was able to take what I learned from Kevin's videos to add the body background semi-transparent circles to my site. I decided to use pseudo-elements instead of the body so that I can anchor the semi-transparent circles to the card, and not the body. This way, the circles don't move their position when the screen-size changes, as it would when I tried to attach them to the body's background using background-image.

## Author

- Website - [Piotr Szponder](https://github.com/pszponder)
- Frontend Mentor - [@pszponder](https://www.frontendmentor.io/profile/pszponder)
- Twitter - [@PSzponder](https://twitter.com/PSzponder)
