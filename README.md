# Frontend Mentor - Social proof section solution

This is a solution to the [Social proof section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)



## Overview

### The challenge

Users should be able to:

- View the optimal layout for the section depending on their device's screen size

### Screenshot

This is a screenshot of my solution.
![](./images/Screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I learned how to use the background url and background position. I didn't know that you could use background in such a way. I was also able to practice CSS grid. It is not longer as daunting as it seemed before. I also learned that you can add multiple urls to a background and set the position for each of them.

To check out the code snippets, see below:

```css
.main {
  background:url(./images/bg-mobile-top.svg) no-repeat, url(./images/bg-mobile-bottom.svg) no-repeat;
  background-postion:-1em -2em, -1em -2em;
}
```
The first unit is used to set the image horizontally and the second unit is used to set the image vertically. It also uses percentages as a unit of measurement. 

### Continued development
I have not yet fully understood CSS grid and its usage, so I'll continue to work on that.

### Useful resources

- [Example resource 1](https://css-tricks.com/almanac/properties/b/background-position/) - This contributed to my understanding of background-position. I really liked this pattern and will use it going forward.

## Author
- Frontend Mentor - [@Favvie](https://www.frontendmentor.io/profile/Favvie)
- Twitter - [@__kenpachi_](https://www.twitter.com/__kenpachi_)

