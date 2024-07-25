# Frontend Mentor - Product preview card component solution

<div align="left">
  <a href="https://www.linkedin.com/in/danae-lescano-salvatierra" target="_blank">
    <img src="https://img.shields.io/static/v1?message=LinkedIn&logo=linkedin&label=&color=0077B5&logoColor=white&labelColor=&style=for-the-badge" height="25" alt="linkedin logo"/>
  </a>
  <a href="https://lescano713.github.io/Product-Preview-Card-Component-Main/" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Demo&label=&color=6A0DAD&logoColor=white&labelColor=&style=for-the-badge" height="25" alt="demo badge"/>
  </a>
  <a href="https://www.frontendmentor.io/profile/Lescano713" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Frontend%20Mentor&label=&color=ff1538&logoColor=white&labelColor=&style=for-the-badge" height="25" alt="FrontendMentor badge"/>
  </a>
</div>


## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)


## Overview

### Screenshot

![](./screenshot/desktop.gif)




## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- desktop-first workflow


### What I learned

<p>Use of classes to separate the content and recycle them when it's necessary, making the structure cleaner and readeable.This approach not only improves code maintainability but also allows for easier updates and scalability.</p>

<p>Using media queries to fit the content depending on the user's device ensures that the layout is responsive and looks good on all screen sizes. This is crucial for improving user experience on different devices.</p>

```css
.product-container{
    margin: 1em;
    display: grid;
    background-color: var(--neutralWhite);
    grid-template-columns: repeat(auto-fit, minmax(16rem, 1fr));
    width: 585px;
    min-width: 290px;
    grid-auto-rows: minmax(17em, 26rem);
    border-radius: 10px;
}
```


### Continued development

<p>For future development, I plan to focus on enhancing my skills in CSS animations to create more interactive and engaging user interfaces. Additionally, I want to delve deeper into JavaScript to add more dynamic functionalities to my web projects.</p>

<p>Another area for improvement is optimizing the website for better performance by minimizing CSS and JavaScript files, and ensuring images are properly compressed without losing quality.</p>

