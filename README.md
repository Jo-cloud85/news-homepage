# Frontend Mentor - News homepage solution

This is a solution to the [News homepage challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/news-homepage-H6SWTa1MFl). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

## Overview

Basically, I am using Bootstrap 5 in this project to create a webpage with navigation bar and an offcanvas side bar.

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

With built-in components in Bootstrap 5, you can quickly create components like navbar, offcanvas side bar with toggle. As each of these built-in components comes with their built-in styles, icons, color, you have to know what the styles each built-in classes entails and replace them accordingly to fit your desired outcomes.

The next approach will be to use grid to align the divs. The little difficulty in this challenge with regards to CSS is the vertical alignment of the elements.

For example, the text "We dive into...", the "Read More" button and the computer image card under "02" have to be vertically aligned. The right-m-container (my own class) has to be vertically aligned with the nintendo switch image below.

The approach is:

1. Group "01" and "02" as 1 component first, and "03" as another component, and use grid to align and format the 3 cards horizontally into 3 columns. In this way, "03" will align vertically with the right-m-container above.

2. Next, apply the same margins and paddings of the left-m-container to the "01" and "02" component. In this way, the "02" will align vertically with the "highlight-text" component above.

There is no separate js file for this challenge as the offcanvas toggler is purely done using Bootstrap.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [Styled Components](https://styled-components.com/) - For styles
- [Bootstrap 5](https://getbootstrap.com/) - For Bootstrap
