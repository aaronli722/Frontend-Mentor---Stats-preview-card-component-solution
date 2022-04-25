# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![Desktop Preview](./images/preview-desktop.png)
![Mobile Preview](./images/preview-mobile.png)

### Links

- Solution URL: [Github](https://github.com/luenlun/Frontend-Mentor---Stats-preview-card-component-solution)
- Live Site URL: [Live Site](https://luenlun.github.io/Frontend-Mentor---Stats-preview-card-component-solution/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

I had learnt a lot in this challenge. Previously I finished three challenges in Frontend Mentor and all were vertical cards without much changes in mobile view. This time, it was a horizontal card that I have to make the elements dynamically adjust to fit the screen when screen width changed.

#### 1. Organized CSS global Setting

I leant the importance of a well organized CSS global setting so that the elements can be well adjusted when screen size decreased before moving to mobile view. A root base size is especially important which I didn't realise. When setting all the size in rem, all the setting like font size, padding, margin can easily adjusted just by changing the base size.

#### 2. card image at different position in desktop and mobile view

In the challenge, the card image is at the right size (the last element?) in desktop view and at the top size (the first element?) in mobile view. I learnt the good use of row-reverse so I can move the image to the right side easily when it is the first element in the HTML codes.

### Continued development

I come up with a lot of questions in this challenge:

#### 1. @media

@meida is used for CSS in different screen size. Is there any industry standard of the @media code structure? For example:

```css
.div1 {}
@media {
  .div1 {}
}

.div2 {}
@media {
  .div2 {}
}
```

```css
.div1 {}
.div2 {}

@media {
  .div1 {}
  .div2 {}
}
```

Which one is preferred?

#### 2. div box same height as image height

In the challenge, initially I used <img> for the card image but then I found that I didn't know how to set the div box responsively same height as the image inside the div box. Finally I used background image instead.

Can it be possible to set the div box same height as the image when <img> is used?

#### 3. Gap space between Flexbox

I used margin to set the gap space between flexbox (the Stat Section). Is there any property instead of margin that can set it?

#### 4. class and id

Is it common to give an id to a div box? Or it is more common to use class?

#### 5. tricks or tool to easy size measurement

As you know, the preview from Frontend Mentor challenge is jpeg image. When I am dealing with the size and value (e.g. padding, margin, font size，color), I have to keep testing by my eyes. Is there any tricks or tools so that I can easily get the value?

### Useful resources

- [圖解：CSS Flex 屬性一點也不難](https://www.casper.tw/css/2017/07/21/css-flex/) - A good page to explain Flex, but in Chinese

## Author

- Frontend Mentor - [@luenlun](https://www.frontendmentor.io/profile/luenlun)
- Twitter - [@luenlun](https://www.twitter.com/luenlun)
