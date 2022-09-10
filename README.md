# Product-preview-card-component
Solution For Frontend Mentor Newbie Challenge Product preview card component
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


## Overview

### The challenge

Users should be able to:

- View the optimal layout on Large Screen.

### Screenshot

![](ScreenShot.png)

### Links

- Live Site URL: [Product preview card component](https://abdallahsalah003.github.io/Product-preview-card-component/)

## My process

### Built with
ONLY WITH
- Semantic HTML5 markup
- CSS custom properties

### What I learned
Learned to Use Both Flex, Grid And make the Card Responsive in small screen ONLY
```css
.container{
    width: 100vw;
    height: 90vh;
    background-color: white;
    display: flex;
    justify-content: center;
    align-items: center;
}
.sub2container{
    width: 30%;
    height: 60%;
    background-color: white;
    display: grid;
    grid-template-columns: repeat(16 , 1fr);
    grid-template-rows: 0.5fr repeat(10 , 1fr) 0.5fr;
    border-radius: 15px;

}
@media only screen and (max-width: 600px) {
    .sub2container{
        width: 40%;
        height: 90%;
        grid-template-columns: 1fr 1fr;
        grid-template-rows: repeat(26,1fr);
    }
```

### Continued development
Why Not!
### Useful resources
I realy love this site
- [w3schools](https://www.w3schools.com/howto/howto_css_image_overlay_title.asp)

## Author

- Website - working on it
- Frontend Mentor - [@AbdallahSalah003](https://www.frontendmentor.io/profile/AbdallahSalah003)
