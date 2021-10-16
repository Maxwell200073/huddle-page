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
  - [Useful resources](#useful-resources)
- [Author](#author)


**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](./screenshot.png)


### Links

- Solution URL: [github.com](https://github.com/Maxwell200073/huddle-page)
- Live Site URL: [github.io](https://maxwell200073.github.io/huddle-page/)

## My process

- First thing I did was put my browser in dev mode so I could do Mobile-first. I did this with @media request to ensure the best for both layouts. I started at the top of the page and worked my way down. I used flexbox for the header and footer. For the middle, I used CSS Grid. For the social icons, I used Fontawesome.com and imported the HTML.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

This was the first time I used CSS Grid on a full webpage. It definitely made things easier, though I could tell I need some practice.

Also, I never knew how to add an image to the browser tab. That was very enlightening.

```html
<link rel="icon" type="image/png" sizes="32x32" href="./images/favicon-32x32.png">
```
```css
.container{
  display: grid;
  grid-template-columns: 60% 1fr;
  grid-gap: 20px;
}
```
### Continued development

I want to add a tablet layout later as well. I also may adjust some of the line heights and fix the border around the Facebook icon.

I would like to make my html more semantic. I just didn't have the time to seo.

### Useful resources

- [FontAwesome](https://fontawesome.com/) - I loved the simplicity of adding icons with this site. Also, they had a very large amont or usful resources for free.

## Author
- Chris Maxwell
- CodepenIO - [@maxwell200073](https://codepen.io/maxwell200073)
- Frontend Mentor - [@Maxwell200073](https://www.frontendmentor.io/profile/Maxwell200073)
- Github - [@Maxwell200073](https://github.com/Maxwell200073)
