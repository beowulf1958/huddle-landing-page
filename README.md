# Frontend Mentor - Huddle landing page with single introductory section solution

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

My goal was to continue to improve my Sass skills. I also wanted to improve my semantic markup. Also, to take a first serious look at layout.
This challenge was fairly straightforward until I got to the social icons.

### The challenge

Users should be able to:

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![Screenshot](images/Screenshot%20Frontend%20Mentor%20Huddle%20landing%20page.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

I began with mobile first to work on the styling. Then went for the desktop version to do the layout.
I wanted to be more organized with the Sass without too many partials.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- Sass / scss

### What I learned

This was my first experience with font awesome. I learned to add the "my kit" script to the head, and the syntax for the body. I also learned how to style the icons and change to hover state
At first I didn't know how to get the circle around the icons, but I figured it out.

```html
<div class="flex">
  <div><i class="fa-brands fa-facebook-f"></i></div>
  <div><i class="fa-brands fa-twitter"></i></div>
  <div><i class="fa-brands fa-instagram"></i></div>
</div>
```

```css
.flex {
  display: flex;
  gap: 2rem;
  justify-content: space-between;
  div {
    width: 2rem;
    height: 2rem;
    font-size: 1rem;
    border: 2px solid var(--white-00);
    border-radius: 50%;
    display: grid;
    place-items: center;
  }
  div:hover {
    border: 2px solid var(--magenta);
    color: var(--magenta);
  }
}
```

### Continued development

I could not get grid-template areas to work, so I did a flexbox solution. Will need to figure out grid for layouts.

## Author

- Frontend Mentor - [@beowulf1958](https://www.frontendmentor.io/profile/beowulf1958)
