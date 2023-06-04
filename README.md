# Frontend Mentor - Fylo data storage component solution

This is a solution to the [Fylo data storage component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/fylo-data-storage-component-1dZPRbV5n). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Desktop-first workflow
- Visual Studio Code
- Chrome DevTools

### What I learned

In this challenge the most challenging task was to create inverted borders for the text bubble. The following is a snippet of what the code for inverted borders look like: 

```html
<section class="storage">
  <div class="bubble">
    <p><span>185</span>GB LEFT</p>
  </div>
</section>
```

```css
.storage .bubble::before
{
    content: "";
    position: absolute;
    background-color: var(--white);
    bottom: -25px;
    right: 0;
    height: 50px;
    width: 30px;
    clip-path: polygon( 100% 50%, 0 50%, 100% 100% );
    border: 5px solid var(--white);
}
```

### Useful resources

I used the following resources to learn how to make an inverted border: 
- [logrocket.com](https://blog.logrocket.com/how-to-create-fancy-corners-in-css/)
- [chatGPT](https://www.chatopenai.com)

## Author

- Frontend Mentor - [@devTetra](https://www.frontendmentor.io/profile/devTetra)
- Twitter - [@tetra_codes](https://twitter.com/tetra_codes)

