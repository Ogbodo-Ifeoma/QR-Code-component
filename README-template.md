# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### Screenshot

![] qr-code-component-main\Screenshot Frontend Mentor QR code component.png

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

I began with HTML, placing the main content in its container and giving class names to elements I wanted to target. In CSS, I made use of the CSS Positioning to position the container in the middle if the page.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Positioning
- Desktop-first workflow

### What I learned

I am more comfortable using CSS Positioning to position elements than using CSS Flex or Grid.

.container {
position: absolute;
left: 40%;
bottom: 130px;
}

The only problem with using CSS Positioning was finding the correct value to place the element where I wanted it.

Also, I worked on this project using VSCode on my laptop, so it was a desktop first design.
I have not practiced using CSS media queries and since I coded using my laptop, I don't know how the design will look on mobile screens.

I did add the media queries for it, just to be on the safe side.

@media screen and (max-width: 375px){
.container{
display: block;
height: 70vh;
}
}

### Continued development

I want to focus on developing mobile first websites and learning how media queries work. I also intend to delve more into CSS Flex and Grid.

### Useful resources

- (https://www.google.com) - This helped me search for some css properties and values that i could not remember immediately.

## Author

- Frontend Mentor - [@IfeomaOgbodo](https://www.frontendmentor.io/profile/IfeomaOgbodo)
- Twitter - [@~THEM.HER](https://www.twitter.com/~THEM.HER)
