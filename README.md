# Frontend Mentor - Space tourism website solution

This is a solution to the [Space tourism website challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/space-tourism-multipage-website-gRWj1URZ3). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

Users should be able to:

- View the optimal layout for each of the website's pages depending on their device's screen size
- See hover states for all interactive elements on the page
- View each page and be able to toggle between the tabs to see new information


### Screenshot

![2022-04-10 (1)](https://user-images.githubusercontent.com/82599062/162626399-9345b86d-38d5-4010-9dae-a2cc241c325c.png)


### Links

- Solution URL: (https://thatsrajeev.github.io/Space-Tourism-Website/)

## My process

### Built with

- Raw HTML
- CSS custom properties

### What I learned

This is my first Web Development project I have worked on. It took a way long time than expected to build the site but the good part is that finally I have made it. Although there a tons of imperfections in the site but I have tried to apply the best of knowledge I have gained so far and also did the necessary research to make an appealing website as good as I can.

I have learnt to create good looking navigation bars while working on this project. I tried the chrome inspect tool to see how professionals create their navigation bars and I tried to reinforce the same to create my own. The code snippet is as follow:

```html
<ul class="strip">

    <li><a class="active" href="index.html"><strong>00</strong> HOME</a></li>
    <li><a class="nav" href="destination-moon.html"><strong>01</strong> DESTINATION</a></li>
    <li><a class="nav" href="crew-commander.html"><strong>02</strong> CREW</a></li>
    <li><a class="nav" href="technology-vehicle.html"><strong>03</strong> TECHNOLOGY</a></li>
  </ul>
```
I also learnt how to put on interesting background images to my webpage. Although early on, I faced a lot of issues while scrolling through or changing my window size affected the appearance of my background image but finally I figured out the perfect options which worked out for me.

```css
.home {
  background-image: url("../assets/home/background-home-desktop.jpg");
  background-size: cover;
  background-repeat: no-repeat;
  background-attachment: fixed;
  color: #FFFFFF;
  height: 900px;
  width: 1440px;
}
```
  
It was also interesting to learn how to create shadows around an element when in hovered state as:

```html
.button:hover {
  box-shadow: 0 0 0 88px rgba(255, 255, 255, 0.1);
}
```

There were a lot other new things that I learned while doing this project and for sure those lessons would be helpful ahead as well.

### Continued development

There are a lot of things that I want to work upon throughout my future projects. Firstly, this project was purely based on CSS and HTML and still a lot of elements I have created right through the basics. Things could be more smooth in the site I believe after I learn JavaScript as well and definitely I would learn and apply in my future projects

### Useful resources

- [MDN Web Docs](https://developer.mozilla.org/en-US/) - This site was really helpful to find about any HTML or CSS element with examples to use it as well.
- [Stack Overflow](https://stackoverflow.com/) - It was certainly a boon for a beginner like me. It got me answers of many different questions I had about adding a specific feature to my website with code snippet examples as well.


## Author

- Frontend Mentor - [@ThatsRajeev](https://www.frontendmentor.io/profile/ThatsRajeev)
- Twitter - [@Rajeev21c](https://twitter.com/Rajeev21c)

## Acknowledgments

I am extremely grateful to Dr Angela Yu for whatall she have taught in her web development course and some really useful tips that she gave which helped me complete this project successfully.
