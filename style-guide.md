# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

## Colors

### Primary

- Violet: hsl(257, 40%, 49%)
- Soft Magenta: hsl(300, 69%, 71%)

## Typography

### Headings

- Family: [Poppins](https://fonts.google.com/specimen/Poppins)
- Weights: 400, 600

### Body

- Family: [Open Sans](https://fonts.google.com/specimen/Open+Sans)
- Weights: 400

## Icons

For the social icons, you can use a font icon library. Some suggestions can be found below:

- [Font Awesome](https://fontawesome.com/)
- [IcoMoon](https://icomoon.io/)
- [Ionicons](https://ionicons.com/)
 .container {
    /* display: flex; */
    /* align-items: center; */
    /* justify-content: center; */
    /* flex-direction: column; */
    /* padding: 0; */
    /* position: relative; */
    /* height: 100%; */
    /* padding-bottom: 2%; */
  }
  body {
    /* min-height: 100vh; */
  }
  header {
    /* display: flex; */
    /* justify-self: flex-start; */
    /* padding-left: 2%; */
    /* padding-top: 2%; */
    /* padding-bottom: 25px; */
    max-width: 80rem;
    padding-inline: 1.5rem;
  }
  .wrapper {
    /* align-items: center; */
    padding-inline: 1.5rem;
    max-width: 80rem;
    gap: 2.5rem;
    flex-direction: row !important;
  }
  .title {
    /* padding-top: 4rem; */
    /* padding-bottom: 2.5rem; */
  }
  .bottom-section {
    /* flex-basis: 50%; */
    /* padding: 2rem; */
    /* height: 100%; */
    flex-basis: 40%;
    padding: 2rem 0;
    height: 100%;
    text-align: start;
  }
  .bottom-section * {
    /* text-align: start; */
    note: Really not a good idea to use wildcards like this ! You don't need it anyway';
  }
  .social > a {
    /* padding-right: 10px; */
  }