# Social proof section solution

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### Screenshot

![screenshot-127 0 0 1_5501-2021 12 29-23_33_56](https://user-images.githubusercontent.com/69512496/147701317-31be01c3-df52-47cd-8f48-b495fc9be964.png)


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
