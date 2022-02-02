# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

This is my first challenge project from [Frontend Mentor](https://www.frontendmentor.io) and I really enjoyed the practice it gave me. I took it upon myself to do it without using Flexbox as I am just beginning to learn it and wanted more practice without it. It also gave me practice using the GitHub web interface to create new repositories and upload files.

### Screenshot

![Solution Screenshot](/assets/images/solution.png)

### Links

- Live Site URL: [QR Code Challenge](https://rachelle-f.github.io/QR-Code-Challenge/)

## My process

- Created new repository on GitHub.
- Wrote out the HTML structure.
- Used photoshop to measure the various elements and double check colors.
- Wrote the CSS, starting from the top elements and working my way down. 

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned

This project taught me that I'm still learning a good deal about the box model and how it applies to the various elements - particularly when to use certain elements as containers for styling purposes. I got stuck on getting the border-radius around the QR Code image to show properly and have the right padding until I added a div element around it. 


```css
.qrcontainer {
    padding: 15px 0px 0px 17.5px;
}

.qrcode {
    width: 290px;
    height: 290px;
    border-radius: 10px
}
```

### Continued development

I need to continue to work on the box model and juggling the various elements together. This beginner's challenge was great for getting some extra practice in. 

### Useful resources

- [MDN](https://developer.mozilla.org/en-US/) - The MDN was my sole resource for looking up anything I got stuck on. 

## Author

- Frontend Mentor - [@rachelle-f](https://www.frontendmentor.io/profile/rachelle-f)
- Twitter - [@janky_too](https://twitter.com/janky_too)
