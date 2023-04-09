# Frontend Mentor - Stats preview card component solution by Marcia Belen Alvarez

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout depending on their device's screen size

### Screenshot

![Design preview for the Stats preview card component coding challenge](./design/screenshot.jpg)

![Design preview for the Stats preview card component coding challenge mobile view](./design/screenshot-mobile.jpg)

### Links

- Live Site URL: (https://marciabel.github.io/stats-preview-card-component-fem/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I was able to practice writing vanilla HTML5 and CSS. One thing I learned was to use the mix-blend-mode CSS property to blend in the content or make it more harmonious. I had to use a little trick to get the image blended with a purple/magenta color by putting the color on the 'picture' container and then blending it into the image.




To see how you can add code snippets, see below:

```html
<picture id="image">
	<img src="images/image-header-desktop.jpg" alt="people working at an office">
</picture>
```
```css
#image {
    display: flex;
    border-radius: 0px 8px 8px 0px;
    background-color: hsl(277, 64%, 61%);
}

#image img {
    mix-blend-mode: multiply;
    opacity: 0.75;
}
```

### Continued development

In my next project I will try to focus firts on the mobile view, and move on from that to the desktop version, since that would be saving resources for mobile users and it would be a new approach to me.

## Author

- Website - Marcia Belen Alvarez (https://www.linkedin.com/in/marciabelenalvarez/)
- Frontend Mentor - [@marciabel](https://www.frontendmentor.io/profile/marciabel)
- Twitter - [@Marcia_Dev](https://twitter.com/Marcia_Dev)
