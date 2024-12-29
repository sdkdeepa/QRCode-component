# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents
- [Frontend Mentor - QR code component solution](#frontend-mentor---qr-code-component-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)
    - [Useful resources](#useful-resources)
    - [Author](#author)


## Overview
<hr />

### Screenshot

![Desktop view](/design/desktop-design.jpg)
![Mobile view](/design/mobile-design.jpg)


### Links

- Solution: https://github.com/sdkdeepa/QRCode-component
- Live website : https://qrcode.netlify.app

## My process
First built semmatic HTML and then figured our the styling. Added accessibility at the end.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Accessibility: alt text for the image and taborder


### What I learned

I learnt about `rem` and `color: hls()` in css. Also learnt how to add `tab order` in the HTML for the elements present.

```css
body {
	background-color: hsl(212, 45%, 89%);
	font-size: 15px;
	font-family: 'Outfit', sans-serif;
	display: flex;
	flex-direction: column;
	align-items: center;
	justify-content: center;
	margin: 4rem;
}

.card {
	background-color: hsl(0, 0%, 100%);
	box-shadow: 5px 5px 5px rgba(0, 0, 0, 0.1);
	border-radius: 0.625rem;
	width: 200px;
	padding: 0.9rem;
	margin-bottom: 1rem;
}

```

### Continued development

I would like to build my own QR code generator. I could use for my content sharing such as videos, netlify urls or my workshop. this was I don't need to use external QR Geneators.

### Useful resources
Read these to refresh my memory: 
1. [Tab Order](https://learning.oreilly.com/library/view/html-xhtml/0321430840/0321430840_ch06lev1sec8.html)
2. [color:hsl](https://learning.oreilly.com/videos/modern-html/9781835880562/9781835880562-video5_6/)
3. [Flexbox](https://learning.oreilly.com/videos/modern-html/9781835880562/9781835880562-video7_2/)
4. [REM](https://learning.oreilly.com/videos/modern-html/9781835880562/9781835880562-video8_4/)

### Author
**Frontend Mentor - [@sdkdeepa](https://www.frontendmentor.io/profile/sdkdeepa)**


