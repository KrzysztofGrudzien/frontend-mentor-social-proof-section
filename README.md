# Frontend Mentor - Social proof section solution

This is a solution to the [Social proof section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Social proof section solution](#frontend-mentor---social-proof-section-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
  - [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the section depending on their device's screen size

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [https://github.com/KrzysztofGrudzien/frontend-mentor-social-proof-section](https://github.com/KrzysztofGrudzien/frontend-mentor-social-proof-section)
- Live Site URL: [https://krzysztofgrudzien.github.io/frontend-mentor-social-proof-section/](https://krzysztofgrudzien.github.io/frontend-mentor-social-proof-section/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- BEM Methodology

### What I learned

Basic knowledge about HTML and CSS properties using BEM Methodology.

```html
<main class="main">
    <section class="proof">
        <div class="proof-text">
            <h1 class="proof__title">10,000+ of our users love our products.</h1>
            <p class="proof__description">
                We only provide great products combined with excellent customer service. See what our satisfied
                customers are saying about our services.
            </p>
        </div>
        <div class="proofs-review">
            <div class="proof-review">
                <div class="proof-review__stars">
                    <img src="./images/icon-star.svg" alt="" />
                    <img src="./images/icon-star.svg" alt="" />
                    <img src="./images/icon-star.svg" alt="" />
                    <img src="./images/icon-star.svg" alt="" />
                    <img src="./images/icon-star.svg" alt="" />
                </div>
                <p class="proof-review__text">Rated 5 Stars in Reviews</p>
            </div>
            <div class="proof-review">
                <div class="proof-review__stars">>
```
```css
    .proof-review:nth-child(2) {
        margin-right: 2rem;
    }

    .card {
        max-width: 350px;
        margin-right: 1.875rem;
        padding-bottom: 2.5rem;
    }

    .card:nth-child(2) {
        margin-top: 2rem;
    }

    .card:nth-child(3) {
        margin-top: 4rem;
    }

```

## Author

- Website - [In progress]
- Frontend Mentor - [@KrzysztofGrudzien](https://www.frontendmentor.io/profile/KrzysztofGrudzien)
- E-mail - krzysztof.grudzien.fed@gmail.com

