# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

## Overview

### The challenge

Recreate the design of the component provided

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![Desktop](/assets/images/screenshot.png)
![Mobile](/assets/images/screenshot_image.png)

### Links

- Solution URL: [Frontendmento](https://www.frontendmentor.io/solutions/qr-code-component-kSY9L23vv9)
- Live Site URL: [Github](https://theroborobin.github.io/frontend-mentor-blog-preview-card/)

## My process

I'm going to start with mobile first. I have only done desktop first design up to this point so lets change that.

Once I had finished building the basic structure, I created some css custom properties. Fairly easy but, I was having trouble in the css to apply the background color. But figured out that instead of

    :root {
      --color-primary: hsl(47, 88%, 63%);
    }

I had done...

    .root {
      --color-primary: hsl(47, 88%, 63%);
    }

Conceptualizing mobile first is a difficult switch mentally. It's not all that natural to me. Sure the devtools in the browser helps. But it doesn't quite feel right.

I think I've handled it fairly okay with the initial build. Next I'm going to handle some media queries.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I feel like I have a better idea of how to start from mobile from the beginning. It was a little difficult thinking past that but I think I made it work.

I also have a better grasp on git this time. It was a fairly smooth setup and compile. I wonder how that will change as things get more complicated.

### Continued development

I want to continue to solidify my workflow and maybe focus a bit more on mobile first as well. Just so I can get a better handle on it.

## Author

- Website - [Robin](https://github.com/TheRoboRobin)
- Frontend Mentor - [@TheRoboRobin](https://www.frontendmentor.io/profile/TheRoboRobin)
