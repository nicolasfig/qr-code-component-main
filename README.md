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
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Desktop Screenshot

![](/screenshot.png)

### Mobile Screenshot

![](/mobile_screenshot.png)

### Links

- Solution URL: [Repository with the solution](https://github.com/nicolasfig/qr-code-component-main)
- Live Site URL: [Live site on github pages](https://nicolasfig.github.io/qr-code-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

Learned basic css positioning using flexbox, how to fit images inside a container and the use of css variables

```css
:root {
  --white: hsl(0, 0%, 100%);
  --light-grey: hsl(212, 45%, 89%);
  --grayish-blue: hsl(220, 15%, 55%);
  --dark-blue: hsl(218, 44%, 22%);
  --outfit: "Outfit", sans-serif;
  --f-regular: 400;
  --f-bold: 700;
}

img {
  object-fit: contain;
  border-radius: 5%;
  width: 100%;
}
```

### Continued development

### Useful resources

- [Flexbox maven](https://flexbox.malven.co/) - A really helpful flexbox cheatsheet

## Author

- Frontend Mentor - [@nicolasfig](https://www.frontendmentor.io/profile/nicolasfig)
