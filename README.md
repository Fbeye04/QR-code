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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Links

- Solution URL: (https://github.com/Fbeye04/QR-code)
- Live Site URL: [Add live site URL here](https://fbeye04.github.io/QR-code/)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Media query

### What I learned

Sure! Here are the explanations for CSS variables and semantic elements in English:

### CSS Variables

CSS variables, also known as custom properties, allow you to store values that can be reused throughout your stylesheet. They are declared using the `--` prefix, and you can reference them with the `var()` function. CSS variables make your code more maintainable by centralizing key values like colors, spacing, or font sizes, so that you only need to change them in one place if needed. Here's a basic example:

```css
:root {
  --primary-color: #3498db;
  --spacing-unit: 16px;
}

button {
  background-color: var(--primary-color);
  padding: var(--spacing-unit);
}
```

In this example, the `--primary-color` and `--spacing-unit` variables are used for consistency and can be updated easily. Using CSS variables makes your stylesheets more modular and easier to manage, especially in larger projects.

### Semantic Elements

Semantic elements in HTML clearly describe their meaning both to the browser and to developers. These elements enhance the readability of code and help search engines and assistive technologies understand the structure and content of a webpage. Examples of semantic elements include `<header>`, `<footer>`, `<article>`, `<section>`, and `<nav>`.

Using semantic elements improves accessibility and SEO because it provides more meaningful information about the content. For example:

```html
<header>
  <h1>Website Title</h1>
  <nav>
    <ul>
      <li><a href="#">Home</a></li>
      <li><a href="#">About</a></li>
    </ul>
  </nav>
</header>
<section>
  <article>
    <h2>Article Title</h2>
    <p>This is the content of the article.</p>
  </article>
</section>
<footer>
  <p>&copy; 2024 Your Website</p>
</footer>
```

In this code, the `<header>`, `<nav>`, `<section>`, `<article>`, and `<footer>` tags help structure the webpage in a way that conveys meaning and improves accessibility.

## Author

- LinkedIn - [Add your name here](https://www.linkedin.com/in/muhammad-fachrezi-barus/)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/Fbeye04)
- GitHub - [@yourusername](https://github.com/Fbeye04)
