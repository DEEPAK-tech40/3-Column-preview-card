# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Overview

![desktop-preview](https://user-images.githubusercontent.com/94350356/189063093-c636921b-d45e-4666-8593-589958c4deb9.jpg)

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

Desktop-view:

![desktop-design](https://user-images.githubusercontent.com/94350356/189063987-74a486b8-3868-41ba-87d0-781dfac13342.jpg)


Mobile-view:

![mobile-design](https://user-images.githubusercontent.com/94350356/189063880-31b4b362-bbb5-4dac-b8a2-abcb64b3438d.jpg)


![](./screenshot.jpg)

### Links

- Solution URL: [Solution](https://www.frontendmentor.io/solutions/3columnpreviewcard-J4vsxBJjhh)
- Live Site URL: [Live site URL](https://deepak-tech40-3column-preview.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Learned to use media queries effectively.

```css
@media screen and (min-width: 500px) {
  body {
    margin: 0;
  }

  h1 {
    font-size: 45px;
  }

  main {
    flex-direction: row;
    width: 920px;
    height: 550px;
  }

  main > div {
    padding: 50px;
  }

  .sedans {
    border-radius: 7px 0px 0px 7px;
  }

  .luxury {
    border-radius: 0px 7px 7px 0px;
  }

  .btn-sedan,
  .btn-suv,
  .btn-luxury {
    height: 3.6rem;
    width: 10.5rem;
    margin-top: 30%;
    font-weight: 700;
    font-size: 18px;
    font-family: Lexend Deca;
    border-radius: 50px;
  }
}
```

## Author

- Frontend Mentor - [@DEEPAK-tech40](https://www.frontendmentor.io/profile/DEEPAK-tech40)
