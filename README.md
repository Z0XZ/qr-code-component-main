# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

I am trying to get started learning frontend, so be gentle with my solution.

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

## Overview

### Screenshot of my finnished page

|                                           Web view                                           |                                            Mobile view                                             |
| :------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------: |
| ![](https://github.com/Z0XZ/qr-code-component-main/blob/master/design/WebPageScreenshot.png?raw=true) | ![](https://github.com/Z0XZ/qr-code-component-main/blob/master/design/WebPageScreenshotMobile.png?raw=true) |

### Links

- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Desktop-first workflow

### What I learned

I have done some frontend a long time ago, and back then I did not know much so for me this was a project to recap some of my own knowledge. I know ting can be made better and easier.

Somewere in te back of my head I felt like it would be best to organize the content of the card in an unordered list since all the information is linked together somehow.

```html
<div id="card">
  <ul id="carditems">
    <li>
      <img
        src="/images/image-qr-code.png"
        alt="QR-code link to frontendmentor.io"
        width=""
      />
    </li>
    <li>
      <h2>Improve your front-end skills by building projects</h2>
    </li>
    <li>
      <p>
        Scan the QR code to visit Frontend Mentor and take your coding skills to the
        next level
      </p>
    </li>
  </ul>
</div>
```

For styling the hardest part was to get the size of the card right and those bloody margins right. There is proabably a simpler way, but what I did was to put 39% margins on each side of the card to get the size I wanted.

```css
#card {
  margin: 10% 39%;
  background-color: hsl(0, 0%, 100%);
  box-shadow: 2px 4px 20px rgba(123, 135, 157, 0.3);
  border-radius: 10px;
  text-align: center;
  padding: 0;
  position: relative;
}
```

I didnt like the way the text on the card scaled and ruined the card itself, so I sized the text to 1.1vw instead of 15px.

Lastly I made the page more responsive to work on mobile devices.

```css
@media screen and (max-width: 700px) {
  #card {
    margin: 10% 10%;
    font-size: 15px;
  }
}
```

### Continued development

I want to get better with css in general. More specifically I would like to get better at flexbox and get more controll on how margins and padding overlaps.

### Useful resources

- [CSS responsive text](https://www.w3schools.com/howto/howto_css_responsive_text.asp) - W3 Schools helped me remembering how to write responsive pages.
- [Flexboxsheet](https://flexboxsheet.com/) - This is an amazing cheat sheet really helped me with flexbox and I really recommend it for anyone using flexbox.

## Author

- Website - [Jon Bjarne Bø](https://www.jonbo.no)
- Frontend Mentor - [@Z0XZ](https://www.frontendmentor.io/profile/Z0XZ)
