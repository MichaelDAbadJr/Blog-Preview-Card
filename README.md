# Frontend Mentor - QR code component solution

TThis is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)



## Overview

<a href="https://junmike-blog-preview.netlify.app/" target="_blank">View Live Website</a>
</br>
<img src="https://raw.githubusercontent.com/MichaelDAbadJr/assets/refs/heads/main/blog-preview-cover.png" width="600">

link to the repository -->
<a href="https://github.com/MichaelDAbadJr/Blog-Preview-Card" target="_blank">Blog-Preview Repository</a>

## My process
I used the figma design to extract measurements such as the font, text size, text weight, padding, margin, and gaps, etc. I Focused on scalability and making presets for fonts and defining :root css variables.

### Built with
CSS Reset:
Including margin: 0; padding: 0; box-sizing: border-box; ensures a consistent design across browsers.

Root Variables:
Using :root for color variables, font weight variables, and text-presets is excellent for scalability and maintainability. It makes it easier to update the text theme and reuse colors.

Typography:
The Google Font Figtree is applied consistently, and the font weights (400 and 800) are preloaded for performance optimization. I also used text-preset classes to easily re-use and scale the text/font theme when I needed.

Responsive Design:
Using max-width for the .blog-card-container ensures the design remains responsive across devices.
The use of min-height: 100svh for the body ensures the card is always vertically centered in the viewport.

Semantic HTML:
Using main for the card container is semantically correct because it represents the main content of the page.

Flexbox:
Flexbox is used effectively for centering and aligning content, both for the overall layout and within the card.


### What I learned
Here I really focused on using correct and proper semantic HTML. I  really learned the difference between using an article for standalone content, a section for important relatable content with H tags within the overall content, and div's are really for everything else that just need content to be grouped.


## Author
- Website - [JunMike](https://junmike.dev)
- Frontend Mentor - [@MichaelDAbadJr](https://www.frontendmentor.io/profile/MichaelDAbadJr)