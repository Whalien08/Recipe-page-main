# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

### The challenge

Users should be able to:
- View the optimal layout for the interface depending on their device's screen size.
- See hover and focus states for all interactive elements on the page.

### Screenshot

*(Note: Add the path to your project screenshot here once you take one!)*
![](./assets/images/screenshot.png)

### Links

- Solution URL: [Add your Frontend Mentor solution URL here](https://your-solution-url.com)
- Live Site URL: [Add your live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox layout
- Responsive Design (Media Queries)
- `rem` units for accessible spacing and scaling

### What I learned

Throughout this project, I learned several powerful CSS layout properties and spacing techniques. Some key takeaways include:

**1. Perfect Centering with Flexbox:**
I learned how to perfectly center a component vertically and horizontally on the screen by turning the `body` into a flex container:

```css
body {
    display: flex;
    align-items: center;   
    justify-content: center;  
    min-height: 100vh;
    flex-direction: column; 
}

**2. Styling List Markers:**
I discovered how to independently color the numbers on an ordered list without altering the rest of the text by using the ::marker pseudo-element:

```css
ol li::marker {
    color: hsl(14, 45%, 36%);
    font-weight: bold;
}
```

**3. Edge-to-Edge Mobile Design:**
I utilized CSS media queries to remove padding and border-radiuses on smaller screens. This allowed the image and main container to seamlessly stretch across the entire width of a mobile device:

```css
@media (max-width: 30rem) { 
    .sub1 {
        width: 100%;
        border-radius: 0; 
        padding: 0; 
    }
    .img1 {
        border-radius: 0; 
        margin: 0;
    } 
}
```

###Continued development

In future projects, I plan to continue refining my responsive design skills, focusing on building mobile-first structures and utilizing more fluid layouts. I also want to dive deeper into CSS Grid to complement my knowledge of Flexbox.

##Author

- Frontend Mentor - [Whalien08](https://www.frontendmentor.io/profile/Whalien08)
- Coded by - Mithra Xavier
