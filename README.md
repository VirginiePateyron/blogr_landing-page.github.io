# Frontend Mentor - Blogr landing page solution

<img src="/design/mockup-blogr_both.png" alt="Présentation d'un aperçu de la page d'accueil du site Blogr" />

This is a solution to the [Blogr landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blogr-landing-page-EX2RLAApP). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Links

- Live Site URL: [Preview the website here](https://virginiepateyron.github.io/blogr_landing-page.github.io/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [TailwindCSS](https://tailwindcss.com/) - CSS framework for styles
- [PostCSS](https://postcss.org/) - JavaScript Tool to transform and automate CSS


### What I learned

I discover a new way to work, with front-end tools like Post-CSS. Instead of use [Prepros](https://prepros.io/), I automatize my tasks with plugins from PostCSS, and install TailwindCSS to configure like I wanted. I install the tool thanks to Grafikart tutorial and official documentation.

```html
<h1>Some code I'm proud of</h1>
```
```PostCSS Installation
module.exports = {
    plugins: [
        require('tailwindcss'),
        require('autoprefixer'),
        require('cssnano'),
        require('@fullhuman/postcss-purgecss')({
        content: ['./public/**/*.html', './src/**/*.vue', './src/**/*.jsx'],
        defaultExtractor: content => content.match(/[\w-/:]+(?<!:)/g) || []
        })
    ]
}
```


### Continued development

I use GItHub to version the code.

### Useful resources

- [How to build a responsive navbar with dropdowns](https://www.w3schools.com/howto/tryit.asp?filename=tryhow_js_responsive_navbar_dropdown) - This helped me to build the complex navbar. I first build another but the responsive didn't work well. I search and found this one, more relevant.
- [Howto install TailwindCSS with PostCSS](https://grafikart.fr/tutoriels/tailwindcss-framework-css-1177) - I'd rather install TailwindCSS to configure and use my own CSS easily. I first use the CDN but I wanted to work as well as possible and configure the project with the working rules.


## Author

- Website - [My portfolio](https://www.vriessa.com)
- Behance [Designer profile](https://www.behance.net/Virginievriessa)
- Instagram - [@vriessa.wordpress.etik](https://www.instagram.com/vriessa.wordpress.etik/)
- Mail - [Hire me](hello@vriessa.com)


## Acknowledgments

Thanks to [FrontEnd Mentor](https://www.frontendmentor.io/) for the opportunity to learn more in my HTML integrator carreer !

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
