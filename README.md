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
- [Acknowledgments](#acknowledgments)


## Overview

### Screenshot

![](./assets/images/challenge%204.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


### What I learned

1. Some users may prefer reduced motion because of `motion sickness`, so it is advised to prevent if its what the user chose
```css
@media (prefers-reduced-motion: reduce){
    * {
        transition: none;
        animation: none;
    }
}
```

2. To give the application a smooth look then you need to `antialiased` or `grayscale` based of the browser
```css
body{
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
```

## Acknowledgments

- Darkster on discord helped in an issue on trying to meet the design given and gave me so tips on when giving an elemnt bold attributes