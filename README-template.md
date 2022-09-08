# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents


  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)


### Screenshot

![Screenshor-Desktop.link](./Screenshot (9).png)
![Screenshor-Mobile.link](./2022-09-08 (5).png)


### Links

- Solution URL: [Add solution URL here](https://github.com/ayushporwal7078/QR-Code-)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grids


### What I learned

For me it was very dificult to choose the right properties in css to get the body and the .card to work and be seen as the style guide declared.

At the end, i believe i did a good job with the things that i used. Always open to any comments

```html
<div class="box">
    <img src="./images/image-qr-code.png" alt="no imgae" width=285 height=285>
    <h1>Improve Your Front-End Skills by building project</h1>
    <p>scan the QR code to visit Frontend Mentor and take your coding skill to next level!</p>
```
```css
body{
  font-family: 'Outfit', sans-serif;
  font-size: 15px;
  display: flex;
  background-color: hsl(212, 45%, 89%);
  flex-direction: column;
  justify-content: center;
  align-items: center;
  height: 595px;
}
.box{
  background-color: hsl(0, 0%, 100%);
  border-radius: 20px;
  margin-bottom: 1rem;
  padding: 15px;
  padding-bottom: 2px;
  max-width: 310px;
  min-height: 460px;
}
img {
	width: 100%;
	border-radius: 20px;
	max-height: 19rem;
	max-width: 19rem;
  display: block;
  margin-left: auto;
  margin-right: auto;
}


### Continued development
I would like to make my own QR Generator so this could be used as a default template.

The qr code could be links to a document or something along those ways. Going to think about something useful that could come in handy.

### Useful resources

- https://www.w3schools.com/ - This helped me to understand better how to use flexbox.

## Author

- Frontend Mentor - [@ayushporwal7078](https://www.frontendmentor.io/profile/ayushporwal7078)

