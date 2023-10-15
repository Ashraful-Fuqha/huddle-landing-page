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
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](./design/desktop-design.jpg)

### Links

- Solution URL: [Solution URL here](https://www.frontendmentor.io/solutions/huddle-landing-page-F51qLan0YP)
- Live Site URL: [Live site URL here](https://ashraful-fuqha.github.io/huddle-landing-page/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- CSS variables
- Mobile-first workflow

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

In this project i learner about css grid property with css variables.

See below:

```html
<main>
      <img src="./images/illustration-mockups.svg" alt="illustration-mockups">
      <section>
        <h2>Build The Community Your Fans Will Love</h2>

        <p>Huddle re-imagines the way we build communities. You have a voice, but so does your audience. 
        Create connections with your users as you engage in genuine discussion.</p> 

        <button>Register</button>
      </section>
    </main>
```
```css
body{
    min-height: 100vh;
    display: grid;
    padding: 2rem 2.3rem;
    place-items: center;
    grid-template-areas: 
                "h ."
                "m m"
                "f f"
                "a a";
    background: url(../images/bg-mobile.svg) no-repeat;
    background-size: contain;
    background-color: var(--voilet);
}

```

### Continued development

I'm curious about the css pre-processor SCSS.


## Author

- Website - Definetly
- Frontend Mentor - [@MjafarsadiqD](https://www.frontendmentor.io/profile/Ashraful-Fuqha)