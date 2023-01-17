# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot
Desktop Layout

![](./screenshots/Akshay%20Frontend%20Mentor%20Testimonial%20Grid%20Section%20-%20Desktop%20layout.png)

Mobile Layout

![](./screenshots/Akshay%20Frontend%20Mentor%20Testimonial%20Grid%20Section%20-%20Mobile%20layout.png)

### Links

- Solution URL: [Frontend Mentor](https://www.frontendmentor.io/solutions/testimonials-grid-section-F6ELuamA6S)
- Live Site URL: [Live site URL](https://testimonials-grid-section-amt.netlify.app/)

## My process
I applied Grid to the container as well the individual testimonial divs. Everything relating to the layout was designed using Grid.
### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow

### What I learned

I practised what I had learned about CSS Grid in this project. 

One new thing I learned in this project is how to position a background image as absolute relative to the parent. You have to add position: relative to the parent for it work. Else, the image will position itself relative to the page.

See the following code for reference:

```html
<div class="testimonial daniel">
      <svg class="bg-quotation" width="104" height="102" xmlns="http://www.w3.org/2000/svg"><path d="M104 102V59.727H84.114c0-5.871.689-11.182 2.068-15.933 1.379-4.75 3.42-9.287 6.125-13.61C95.01 25.86 98.909 22.257 104 19.375V0c-9.758 4.27-17.712 9.874-23.864 16.813-6.151 6.939-10.712 14.545-13.681 22.818C63.485 47.904 62 59.941 62 75.74V102h42zm-62 0V59.727H22.114c0-5.871.689-11.182 2.068-15.933 1.379-4.75 3.42-9.287 6.125-13.61C33.01 25.86 36.909 22.257 42 19.375V0c-9.652 4.27-17.58 9.874-23.784 16.813C12.01 23.752 7.424 31.358 4.455 39.631 1.485 47.904 0 59.941 0 75.74V102h42z" fill="#A775F1" fill-rule="nonzero"/></svg>
      <div class="header">
        <img class="image-daniel" src="./images/image-daniel.jpg" alt="Image of Daniel Clifford">
        <h3 class="full-name">Daniel Clifford</h3>
        <p class="designation">Verified Graduate</p>
      </div>
      <h2 class="testimonial-title">
        I received a job offer mid-course, and the subjects I learned were current, if not more so, 
  in the company I joined. I honestly feel I got every penny's worth.
      </h2>
      <p class="testimonial-body">     
  “ I was an EMT for many years before I joined the bootcamp. I've been looking to make a 
  transition and have heard some people who had an amazing experience here. I signed up 
  for the free intro course and found it incredibly fun! I enrolled shortly thereafter. 
  The next 12 weeks was the best - and most grueling - time of my life. Since completing 
  the course, I've successfully switched careers, working as a Software Engineer at a VR startup. ”
      </p>
    </div>
```
```css
.daniel {
    position: relative;
}

.bg-quotation {
    position: absolute;
    top: 0;
    right: 1.5em;
}
```

## Author

- Frontend Mentor - [@Akshay-Tarde](https://www.frontendmentor.io/profile/Akshay-Tarde)
