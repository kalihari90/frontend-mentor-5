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

![](./images/screenshot.png)

### Links

- Solution URL: [Solution](https://github.com/kalihari90/frontend-mentor-5)
- Live Site URL: [Live](https://kalihari90.github.io/frontend-mentor-5/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

This time I tried to use semantic tags like `<article>`, `<main>`, `<footer>`.
I also put `display: grid;` & `place-content: center;`, `min-height: 100vh;` on the body for the centring purpose.
I've learned how to use `<picture>` & `<source>` tags for images with 2 different file sources.

```html
<picture class="card__img">
	<source srcset="/images/image-product-desktop.jpg" media="(min-width: 600px)" />
	<img src="/images/image-product-mobile.jpg" alt="" />
</picture>
```

Must remember about this reset for images:

```css
img,
picture {
	display: block;
	max-width: 100%;
}
```

### Continued development

All newbie challenges !

### Useful resources

- [Kevin Powell solution](https://www.youtube.com/watch?v=B2WL6KkqhLQ&t=1102s&ab_channel=KevinPowell) - This helped me with formatting images. I really liked this pattern with use of the tag `<source>` and will use it going forward.

## Author

- GitHub - [kalihari90](https://github.com/kalihari90)
- Frontend Mentor - [@kaLihaRi90](https://www.frontendmentor.io/profile/kalihari90)
