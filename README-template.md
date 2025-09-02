# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![](../order-summary-component-main/images/iPhone-14-Pro-342x741.png)

![](../order-summary-component-main/images/Macbook-Air-1356x848.png)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

I learned a lot how to use BEM in my HTML.
I learned how i can apply flexbox options to some code blocks 
I learned the use of hover


To see how you can add code snippets, see below:

```html
<main class="main">
    <div class="main__image"></div>
    <div class="main__information">
      <h3 class="main__title">Order Summary</h3>
      <p class="main__description"> You can now listen to millions of songs, audiobooks, and podcasts on any device anywhere you like!</p>
      <div class="main__plan_infomation">

        <div class="main__plan__image"></div>
        <div class="main__plan__text"><!--hacerlo con grid-->
          <p class="main__plan__title">Annual Plan</p>
          <p class="main__plan__price">$59.99/year</p>
        </div>
        <a href="#" class="main__plan__change">Change</a>
       
      </div>
    </div>
```
```css
.main__button--cancel{
    background-color: transparent;
    color: var(--Gray-600);
    box-shadow: none;
    margin-top: 0.5rem;
    margin-bottom: 2rem;
    width: 80%;
}
.main__button--cancel:hover{
    cursor: pointer;
    background-color: whitesmoke;
    color: black;
}
```


## Author

- Website - [Manuel Felipe Gonzalez]()
- Frontend Mentor - [@ymManuelGonzalez1](https://www.frontendmentor.io/profile/mManuelGonzalez1)



## Acknowledgments

THE CONSISTENCY BEATS TALENT 

