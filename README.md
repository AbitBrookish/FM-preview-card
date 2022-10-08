# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

## Overview

### The challenge

  Users should be able to:

  - View the optimal layout depending on their device's screen size
  - See hover and focus states for interactive elements

### Screenshot

  Here are screenshots of both the mobile and desktop viewpoint solutions:

  1. [](/design/Solution-mobile.png)
  2. [](/design/Solution-desktop.png)

### Links

  - [Solution URL](https://github.com/AbitBrookish/FM-preview-card)
  - [LIVE site URL](https://abitbrookish.github.io/FM-preview-card)

## My process

  ### Built with

  - Semantic HTML5 markup
  - CSS custom properties
  - Flexbox


### What I learned

  Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

  For the most part, I was glad to finally be able to put all the learning I had been doing over the last few weeks into practice. "Major Learning" basically turned into "major reviewing/re-learning" for me. Even though I ended up not using it, I did learn about img srcsets and responsive images. But mostly, I had to refamiliarize myself with the cohesion of min/max-width/height, flex positioning and the html nesting that was needed to make it all work affectively, and media queries insofar as how order affected what styles were followed and which were ignored. 

  Here is some of the code I spent more than a little time fiddling around with:

  ```html
  <img 
    srcset="/images/image-product-mobile.jpg 686w" 
    sizes="(max-width: 400px) 640px"
    alt="Gabrielle Essence perfume bottle"
    class="perfume-mobile" />

  <img
    srcset="/images/image-product-desktop.jpg 600w"
    sizes="(max-width: 1440px) 1440px"
    alt="Gabrielle Essence perfume bottle"
    class="perfume-desktop" />
  ``` 
  ***this is the code format I eventually didn't use because it didn't translate to the final page (whether because it wasn't the right iteration for the job, or because I didn't code it correctly).

  ```css
  @media (min-width: 40rem) {
    .text-card {
      background: #fff;
      margin: 0;
      max-width: 343px;
      min-height: 475px;
      border-top-right-radius: 12px;
      border-bottom-right-radius: 12px;
    }
  }
  ``` 
  ***I spent more time than I'd like to admit on the height style, until it dawned on me that the function I wanted to see would be accomplished with MIN-height and not MAX-height. 

### Continued development

  This was not as challenging as I thought, however, even as a new developer it outlined some areas that I need to focus more effort into. I was comfortable formating my html file, setting images, creating links, creating styles, hover fx, and cursor changes, but where I was disappointed in myself was the speed in which I did the project. It's a simple challenge and (while acknowledging that I'm still new to it all) I feel as though it should not have taken me as long as it did. Also, when it came to sizing and specific measurements in CSS, there were times when I really struggled to get things to fit. Some skills I'm sure will improve with practice, others I know will need focus. 

### Useful resources

  I made a .md file that listed the sites I recieved help from. 
    -[bibliography](/Helpful-sites.md)

## Author

  - Website - [Alan- AbitBrookish](https://github.com/AbitBrookish)
  - Frontend Mentor - [@AbitBrookish](https://www.frontendmentor.io/profile/AbitBrookish)

