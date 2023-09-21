# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents



## Overview

### The challenge

### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it. 

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

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
