# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Planning](#planning)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
<!-- - [Acknowledgments](#acknowledgments) -->

<!-- **Note: Delete this note and update the table of contents based on what sections you keep.** -->

## Overview

This is a challenge from Frontend Mentor. The challenge is to build out this QR code component and get it to look as close to the design as possible. There are two design prototypes for this project: for mobile and desktop screens. This means that I will have to make sure that the site is responsive.

### Screenshot

![Picture of QR Code](<images/Screenshot%20(11).png> "Screenshot of QR Code website")

<!-- **Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.** -->

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [https://pjiceskull.github.io/qr-code-component-main/](https://pjiceskull.github.io/qr-code-component-main/)

## My process

### Planning

When coding design prototypes I try to break down important elements individually. This is a beneficial skill that makes the process of coding the look of a website smoother. The first thing I look at is the website’s color palette. How many colors are there and what are they being used for?
Usually, I’ll use a color palette generator to get color themes or I’ll use a color picker tool to select all the colors. However, Frontend Mentor was able to provide me with a style guideline for the website. This guideline mentions what fonts, colors, and dimensions of the website were designed for.

The next step is planning how I should build the website’s layout before I before coding. Looking at the design files, I’ll need to create a div that contains the content of the QR Code card. As shown in the design files, the card is positioned at the center of the screen. Inside the card, we’ll have two more div containers, one will hold the QR code, and the other div will contain the text. The text seems to be in a sans-serif font and in different font sizes. The top text is larger, bolder, and has a navy blue color. Meanwhile, the bottom text is smaller and seems to share a smaller font color with the background. Another thing I notice is that both the card box and the QR code have a border radius.
I named the class of our main container div, “qr-card” since this div will have a white background color for our card. When styling content for a website, I prefer to use a preprocessing language like SASS for a better workflow. Inside our “qr-card” container div I created two more divs. One of the biggest challenges when translating a design is making sure that everything is in the right place.

### Built with

<!-- - Semantic HTML5 markup -->

- HTML markup
- CSS custom properties
- Custom CSS Properties
  - Flexbox
  - Box-shadow
- [SCSS](https://sass-lang.com/) - Preprocessor Language for CSS
- [Visual Studio Code](https://code.visualstudio.com/) - Code Editor

<!-- **Note: These are just examples. Delete this note and replace the list above with your own choices** -->

### What I learned

- Make sure to always read over all of your files as they may contain important guidelines and documentation.
- Box shadow properties and how to manipulate its values.

Some Code I’m proud of

```css
.qr-card {
  background-color: #ffffff;
  height: $card-height;
  width: $card-width;
  margin: 0 auto;
  font-size: 15px;
  padding: 20px;
  border-radius: 20px;
  box-shadow: 15px 15px 30px rgba(82, 90, 111, 0.4);
}
```

<!-- **Note: Delete this note and the content within this section and replace with your own learnings.** -->

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [ColorDesigner.io](https://colordesigner.io/) - As a reference for the website’s color palette.
- [Coolors.co](https://coolors.co/) - For giving me the names of the value of the colors I could use and creating them as variables.
- [Google Fonts](https://fonts.google.com/specimen/Outfit) - For the "Outfit" font family.
- [W3Schools](https://www.w3schools.com/cssref/css3_pr_box-shadow.php) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/CSS/box-shadow) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

## Author

- Website - [Pierce Issah](https://pjiceskull.github.io/WebPorfolio)
- Frontend Mentor - [@PJIceskull](https://www.frontendmentor.io/profile/PJIceskull)
- Twitter - [@Pierce24I](https://twitter.com/pierce24i)

<!-- ## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.** -->
