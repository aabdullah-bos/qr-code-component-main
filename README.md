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

## Overview

### Screenshot

![Desktop View](./screenshot.jpg)

### Links

- Solution URL: https://www.frontendmentor.io/solutions/html-5-semantic-markup-css-iplsm7C7L_
- Live Site URL: https://aabdullah-bos.github.io/qr-code-component-main/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Mobile-first workflow

### What I learned

#### More about Semantic Elements
This project helped me learn a lot! I dove deeper on the meaning and use of [HTML Semantic Elements](https://developer.mozilla.org/en-US/docs/Glossary/Semantics#semantics_in_html), which help provide context to both human and browsers about the content inside of them. For example, the [`<figure>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/figure) element represents self-contained content, potentially with an optional caption, which is specified with `<figcaption>`. This can be useful for SEO searches where the picture of a dog and the caption of a dog can help search engines find the dog on a page.

```HTML
<figure>
    <img src="/assets/doggie-with-a-mustache.jpg"
         alt="Doggie with a mustache">
    <figcaption>A Doggie with a mustache</figcaption>
</figure>
```

#### Embedding Google Fonts Into Website
[Google Fonts](https://fonts.google.com/about) is a "robust catalog of open source fonts and icons." To add a font from google fonts you can add a `<link>` element in the `<head>` section of your document.

```HTML
<!DOCTYPE html>
<html lang="en">
  <head>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@700&display=swap" rel="stylesheet">
  </head>
  <body>
    <p style="font-family: 'Outfit', serif">
      Hello, Font World!
    </p>
  </body>
</html>
```

#### Positioning Images
Images can be tricky as they are actually `inline` elements by default. This can lead to strange issues around rendering with text, that are not related to the `padding` or `margin` properties of the images style declaration.

### Continued development

I need to 

### Useful resources

The Google Search Engine and the Frontend Mentor Slack Channel.

## Author

- Website - Aquil H. Abdullah
- Frontend Mentor - [@abdullah-bos](https://www.frontendmentor.io/profile/aabdullah-bos)
- Twitter - [@therealaquil](https://www.twitter.com/therealaquil)

## Acknowledgments

Thanks to [Josh Burri](https://www.frontendmentor.io/profile/burrijw) for providing a little more context.
