# Frontend Mentor - Results summary component solution

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview
Working on this project was not as easy as I thought it will be. I don't know how to build responsive grids without bootstrap and struggled to get it right in this project. In summary, this project made me realize that I have a long way to go in my learning journey as a front end developer. I look forward to all I will get to learn though.

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size (I spent a long time doing this. Glad I got to figure it out)
- See hover and focus states for all interactive elements on the page


### Links

- Solution URL: [Link to the solution on my github](https://github.com/JulietNnaji/results-summary-component-main)
- Link to the live solution on Netlify (https://magical-dodol-e0498b.netlify.app)


### Built with

- CSS custom properties
- Flexbox
- CSS Grid

### What I learned
I learned another way of building a responsive grid


```html
Some HTML code I like how I wrote it(I know it can be better though)
```
 <div class="reaction-box">
  <img src="assets/images/icon-reaction.svg" class="reaction-icon" alt="reaction-icon"/>
  <span class="reaction">Reaction </span>
  <small class="reaction-number"> 80 <span class="icon-opacity">/100</span></small>
  </div>
```css
Super proud-of this css
```
.grid-section{
    max-width: 650px;
    margin: 0 auto;
    display: grid;
    gap: 1rem;
    background: hsl(0, 0%, 100%);
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
}
```

### Continued development

I would try using React to build my next project. While also working on building much better looking responsive grids and websites.


### Useful resources

- [Example resource 1](https://travishorn.com/responsive-grid-in-2-minutes-with-css-grid-layout-4842a41420fe) - This site helped me to build my responsive grid. 
- [Example resource 2](https://www.w3schools.com/) - Each time I am stuck and I google to find how to debug my code, I always look out for W3schools. They give you up to date and straight-forward examples often times with pictures on how you can solve a particular challenge. 

*
## Author

- Website - [Juliet Nnaji](https://www.github.com)
- Frontend Mentor - [@JulietNnaji](https://www.frontendmentor.io/profile/JulietNnaji)
- Twitter - [@nnajijuliet17](https://www.twitter.com/nnajijuliet17)

## Acknowledgments

Doubt I will be able to build this site without the help of these links, https://travishorn.com/responsive-grid-in-2-minutes-with-css-grid-layout-4842a41420fe and https://www.w3schools.com/ 

