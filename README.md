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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

![](./images/finished.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- CSS custom properties
- CSS Grid

### What I learned

This project taught me about the :root pseudo class. I previously knew how to create custom properties,
but I didn't know that it was common to put them in the :root pseudo class.

Additionaly, this project reinforced the importance of being able to look for information. I knew of the :root, but 
I wasnt accessing it properyly as I was using an element selector. After noticing that my custom properties weren't working, I went to MDN and learned about :root and how it's common practice to put properties there to make them globally available.


```css
:root{
    --color-lightGray :  hsl(212, 45%, 89%);
    --color-grayishBlue : hsl(220, 15%, 55%);
    --color-darkBlue : hsl(218, 44%, 22%);
}
```

### Continued development

I'd like to continue implementing custom properties into my code, and continue leanring about best practices surrounding them.

### Useful resources

- [MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/:root) - This helped me correct my misunderstanding about root and introduce me to putting global variables into the psuedo class.

## Author

- Frontend Mentor - [@Moses2308](https://www.frontendmentor.io/profile/moses2308)
- DEV - [@moses2308](https://dev.to/moses2308)
