# Frontend Mentor - QR code component solution

Hello, my name is Samuel (kailera is my game nickname) and this is my first experience coding a frontend challenge from FrontEnd mentor. This project proposes the creation of a responsive qr code card in html/css stack. This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)


**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

This qr code card adapts in mobile and desktop screens, without many changes to its structure. Basically, im mobile and large/desktop screens it has to be in center view.
The style guide provide by FrontMentorChallenge specify the widths for mobile and desktop screens: 375 and 1440 px respectively. Without much difficulty, to try to respect these measurements, the size of the wrapper was defined as follows:

```
style.css
background-color: var(--light-gray);
width: 100vw;
max-width: var(--desktop);
height: 100vh;
display: flex;
justify-content: center;
flex-direction: column;
gap: 10px;
align-items: center;
```

Body has a white background, so when screen is large than a desktop measurement, the wrapper increases stops and shows the body background. This prevents the card from growing to the point of becoming useless (a QR code on a television screen that covers the entire transmitted image for example).

### Screenshot

##### Mobile Screen

![Mobile Screen](./images/screenshots/mobile%20screen.png)

##### Desktop Screen

![Desktop Screen](./images/screenshots/qrcode_desktop%20screen.png)

##### Overflow Desktop Behavior

![Overflow Desktop Behavior](./images/screenshots/overflow%20screen.png)

### Links

[Final QR Code Card ](https://kailera.github.io/qrcode/)


### My Process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

Mobile first is a good one aproach to focus your application to be scallable and reache as many devices as possible.

### Useful resources

- [W3Schools Card Example](https://www.w3schools.com/howto/howto_css_cards.asp) - This helped with ideas to structure a card.

- [kevin Powell's Pratical Guide to Responsive Web Design](https://www.youtube.com/watch?v=x4u1yp3Msao&t=378s) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

## Author

[My GitHub](https://github.com/kailera)
