# Social proof section solution

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the section depending on their device's screen size

### Screenshot

![screenshot-127 0 0 1_5501-2021 12 29-23_33_56](https://user-images.githubusercontent.com/69512496/147701317-31be01c3-df52-47cd-8f48-b495fc9be964.png)


Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it.

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

### Links

- Solution URL: https://github.com/hassanidris/social-proof-section
- Live Site URL: https://hassanidris.github.io/social-proof-section/

## My process

### Built with

- CSS Variables
- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

To see how you can add code snippets, see below:

- CSS Variables

```scss
--clr-veryDarkMagenta: hsl(300, 43%, 22%);
--clr-softPink: hsl(333, 80%, 67%);
```

- Nesting media queries inside the classes

```scss
&__title {
  font-size: var(--fs-300);
  color: var(--clr-veryDarkMagenta);
  line-height: 1;
  max-width: 11ch;
  margin-bottom: 0.5em;
  font-weight: var(--fw-700);

  @media (max-width: 50em) {
    margin-inline: auto;
    margin-bottom: 1em;
  }
}
```

## Author

- Github - [hassanidris](https://github.com/hassanidris)
- Frontend Mentor - [@hassanidris](https://www.frontendmentor.io/profile/hassanidris)
