# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [Useful Resources](#useful-resources)
  - [What I learned](#what-i-learned)
- [Author](#author)
- [Ackgnowledgment](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](/images/screenshot.png)


### Links

- Live Site URL: (https://faris-thibani.github.io/Stats-Preview/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned




This challenge helped me gain prespective on lists and contexts when to use them. 
```html
   <ul class="stats flex">
            <li class="stats">
              <p> 10k+ <span class="stat-of"> companies</span></p>
            </li>
            <li class="stats">
              <p>314 <span class="stat-of">  templates</span></p>
            </li>
            <li class="stats">
              <p> 12M+ <span class="stat-of">  queries</span> </p>
            </li>
          </ul>
```
Mix-blend-mode was another significant lesson learned during this challenge. 

```css
.image-container{
    width: 50%;
    background-color: hsl(277, 64%, 61%);

}
.image1 {
    object-fit: cover;
    mix-blend-mode: multiply;
    opacity: 80%;
    height: 100%;
   
}
```

Looking forward to more learning! 


### Useful resources

- Styling List Items (https://www.w3schools.com/css/css_list.asp)
- Mix-blend-mode (https://developer.mozilla.org/en-US/docs/Web/CSS/mix-blend-mode)

## Author

- Frontend Mentor - [@Faris-Thibani]https://www.frontendmentor.io/profile/Faris-Thibani

## Acknowledgments

This code would not be possible without the continues effort and support from the Frontend Community. Thanks for @vcarames & @correlucas especially for providing feedback on the submission as usualy and for planting new ideas. 
