# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

![](./qr-code-component.png)

### Links

- Solution URL: [https://github.com/KH-Ray/qr-code-component](https://github.com/KH-Ray/qr-code-component)
- Live Site URL: [https://kh-ray.github.io/qr-code-component/](https://kh-ray.github.io/qr-code-component/)

## My process

### Built with

- Semantic HTML5 markup
- Flexbox
- [TailwindCSS](https://tailwindcss.com/) - CSS Framework

### What I learned

```html
<main class="flex h-screen items-center bg-[#d6e2f0]">
  <div
    class="mx-auto flex w-96 flex-col items-center rounded-2xl bg-white p-6 shadow-sm"
  >
    <img
      class="h-auto w-auto rounded-2xl"
      src="./images/image-qr-code.png"
      alt="QR code image"
    />
    <h1 class="w-11/12 pt-6 text-center text-2xl font-bold text-[#1f3251]">
      Improve your front-end skills by building projects
    </h1>
    <p class="w-11/12 pb-6 pt-4 text-center text-lg leading-6 text-[#7b879d]">
      Scan the QR code to visit Frontend Mentor and take your coding skills to
      the next level
    </p>
  </div>
</main>
```

```css
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

html {
  font-size: 62.5%;
  font-family: "Outfit", sans-serif;
}

@media only screen and (min-width: 640px) {
  html {
    font-size: 75%;
  }
}
```

## Author

- Frontend Mentor - [@UncertainlySure](https://www.frontendmentor.io/profile/UncertainlySure)
