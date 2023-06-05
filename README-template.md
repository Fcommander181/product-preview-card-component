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
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

#### Desktop preview
![](./screenshot1.png)

#### Mobile preview
![](./screenshot2.png)



### Links

- Solution URL: (https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

I've learned by this project how to replace images depending on screen sizes 

#### There is an example :

``` css

/* Picture for Mobile  */
  .hero-image {
    background-image: url("images/image-product-mobile.jpg");
    background-size: cover;
    width: 100%;
    height: 100%;
    border-radius: 8px 8px 0 0;
}

/* Picture for Desktop */
@media (min-width: 768px)
.hero-image {
        background-image: url("images/image-product-desktop.jpg");
        border-radius: 8px 0 0 8px;
    }

```


### Continued development

I'm going to focus on enhancing my flexbox and Grid layouts in my future projects. I feel like i need to improve it and make it more efficient . Besides , I will learn how to boost responsivness in my future project . Inshallah ! 

### Useful resources

- [Resource 1](https://www.youtube.com/watch?v=rg7Fvvl3taU&list=LL&index=17&t=40s) - This video really helped me  to recap. I also recommend this channel for everyone who want to learn or improve his CSS knowledge .
- [Resource 2](https://courses.kevinpowell.co/conquering-responsive-layouts) - This is an amazing Website that will give you tips and tricks to make an excellent Responsive layout . 


## Author

- Frontend Mentor - [@Cat Commander](https://www.frontendmentor.io/profile/Fcommander181)


## Acknowledgments

I want to thank a lot Kevin Powell "CSS king" because he helps me implementing CSS Grid in this project . I really recommend his channel : [Kevin Powell](https://www.youtube.com/@KevinPowell).

