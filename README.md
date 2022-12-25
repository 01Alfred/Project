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
- [Acknowledgments](#acknowledgments)



## Overview
I challenged myself with the QR Code Component to hone my frontend skills.

### Screenshot

![QR screenshoot solution](https://github.com/01Alfred/QR-code-component/blob/main/images/QR%20screenshot%20solution.png?raw=true)



### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties



### What I learned

I initially felt I wouldn't be able to accomplish it. But once I started thinking about what the layout should be, I was able to develop something that was near to the solution.
MDN documentation aided me along the way.

A few difficulties I encountered: horizontal and vertical item centering.
How do we center it without the thing bouncing about and shrinking?

Some code snippets I found helpful but doesn't help entirely, see below:

```html
<div class="container">
  <div class="child"></div>
</div>
```
```css
.container {
  font-family: arial;
  font-size: 24px;
  margin: 25px;
  width: 350px;
  height: 200px;
  outline: dashed 1px black;
  /* Setup */
  position: relative;
}

.child {
  width: 50px;
  height: 50px;
  background-color: red;
  /* Center vertically and horizontally */
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}

```
- [freeCodeCamp](https://www.freecodecamp.org/news/how-to-center-anything-with-css-align-a-div-text-and-more/) - Had the snippet from here.



### Continued development

I need a bit more practice with the flexbox.



### Useful resources

- [MDN Docs](https://developer.mozilla.org/en-US/) - This helped me revise some snippet. Very easy to comprehend.



## Author

- Website - [Alfred](http://www.linkedin.com/in/alfred-bonah-b76346223)



