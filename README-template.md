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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview
Your challenge is to build out this blog preview card and get it looking as close to the design as possible.

You can use any tools you like to help you complete the challenge. So if you've got something you'd like to practice, feel free to give it a go.


### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [https://your-solution-url.com]
- Live Site URL: [https://your-live-site-url.com]

## My process
I first start of by reading the design brief and going the figma file(design and design system).
Once I am done with that, I open the html file start coding. I use GoLive to be able to see live edits to the codes. I also have the 508 compliance extension installed to help me meet requirements.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


### What I learned

Knowing media quary is big deal for me. Most of the the world's conversations are done via mobile phones. Being able prepare web app the is mobile friendly is huge.This means I am able to deliver content to people on the go. See below


```css

@media (min-width: 500px){
    body{
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
        height: 100vh;
    }
    
    .container{
        width: 384px;
        margin-bottom: 1.25rem;

        &:hover{
            transition-duration: 0.5s;
            transform: scale(1.01);
        }
    }
    
}
```


### Continued development
My focus now is to do more real-world challenges that require only html and css while I continue to learn JavaScript until I get to challenges that requires the use of JavaScript. Also, writing scaleable code in vital to me and any development team. I am big end user before coder. So my focus is also coding for good user experience and technology this my life a bit easier. As a Graphic Designer, understanding coding helps make your design more relatable to both end users and the development team. I have to able to hit the sweet spot for both clients(end users and developers).I know  organization as stakeholder is mentioned here. I know they are an important factor too.


### Useful resources

- [Example resource 1](https://w3schools.com) - .
- [Example resource 2](https://developer.mozilla.org/en-US/) - these two sites are first plaese to go to for  any help I need with html, css and javascript referecnes.


## Author

- Website - [Ishmael Sunday](https://linkedin.com/in/ishmael-sunday)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/ishmaelsunday)
- Bluesky - [@ishmaelsunday.bsky.social](https://bsky.app/profile/ishmaelsunday.bsky.social)



## Acknowledgments
Worked Solo.
