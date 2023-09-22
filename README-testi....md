# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents



## Overview

### The challenge

### Screenshot
![Screenshot 2023-09-21 125011](https://github.com/aboisam/testimonial-grid/assets/128613281/09b19eae-93e8-4f4d-a244-0184e372eb72)
![mobile ](https://github.com/aboisam/testimonial-grid/assets/128613281/29e820a0-0c93-477a-b222-21d29ed30892)

### Links

- Solution URL: https://github.com/aboisam/testimonial-grid.git
- Live Site URL:(https://aboisam.github.io/testimonial-grid/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid

## What I learned
CSS fundamentals
Responsive design
CSS Grid

## Useful resources
W3Schools - A must-go reference when it comes to know how a specific HTML tag or CSS property works.
A Complete Guide to CSS Grid - A comprehensive guide to CSS grid layout.

To see how you can add code snippets, see below:

```html
<div id="kira" class="people bg">
  <div class="profile">
    <img src="images/image-kira.jpg" alt="Kira_profile_picture">
      <h2>Kira Whittle</h2>
      <p class="verified_grad">Verified Graduate</p>
  </div>
```css

#daniel {
    background: var(--Moderate-violet);
    grid-column: 1 / 3;
    background-image: url(./images/bg-pattern-quotation.svg);
    background-repeat: no-repeat;
    background-position: 80% 0%;
}

#jonathan {
    background: var(--Very-dark-grayish-blue);
}
#patrick {
    background: var(--Very-dark-blackish-blue);
    grid-column: 2 / 4;
}
#jeanette {
    background: var(--White);
}
#kira {
    background: var(--White);
    grid-column-start: 4;
    grid-row: 1 / 3;
}
#daniel .profile img, #Patrick .profile img {
    border-color: var(--soft-Moderate-violet);
}
```



## Author

- Website - [ABOI SAMSON ABOI]
- Frontend Mentor - [@aboisam](https://www.frontendmentor.io/profile/aboisam)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)
