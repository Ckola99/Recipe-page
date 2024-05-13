# Frontend Mentor - Recipe page solution

This is my personal solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects and I enjoyed working on this project.

## Table of Contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
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

#### Desktop view
![](/assets/images/screencapture-ckola99-github-io-Recipe-page-2024-05-13-10_53_13.png)

#### Mobile view
![](/assets/images/screencapture-ckola99-github-io-Recipe-page-2024-05-13-10_56_58-mobile.png)

### Links

- Live Site URL: [Live site URL here](https://ckola99.github.io/Recipe-page/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned

I learned and refined my understanding of css selectors and I learned more about padding, margin as well as containers. I also learned more about CSS resets and implemented one in my project and I want to continue using them and improving them in future.

CSS Reset
```
*,
*::before,
*::after {
	box-sizing: border-box;
}
* {
	margin: 0;
}
body {
	line-height: 1.5;
	-webkit-font-smoothing: antialiased;
}
img,
picture,
video,
canvas,
svg {
	display: block;
	max-width: 100%;
}
input,
button,
textarea,
select {
	font: inherit;
}
p,
h1,
h2,
h3,
h4,
h5,
h6 {
	overflow-wrap: break-word;
}
#root,
#__next {
	isolation: isolate;
}

```

Marker psudeo selector
```
.ingredients li {
	padding-left: 14px;
	margin: 5px 0;
}

.ingredients li::marker {
	color: var(--heading-color);
	font-weight: 100;
}
```

I learned about a new pseudo selector "::marker" through the MDN docs. Through this project I've also learned how to properly make a README.md using markdown language.

### Continued development

The areas where I think I'd like to improve is my understanding of selectors and positioning of elements in css. I learned about psuedo selector and I would like to learn more about them and use them more in my future projects. I also used variables and I would like to using them more to streamline my css. The css reset is something I would like to improve as this is interesting to me and I feel like I can learn more about CSS through learning more about resets.

### Useful resources

- [Css reset](https://www.joshwcomeau.com/css/custom-css-reset/) - this article taught me about CSS reset and a little bit more about css defaults.
- [MDN](https://developer.mozilla.org/en-US/) - this website is what I used to make sure I used the correct selectors and available properties.
- [ChatGPT](https://chatgpt.com) - I used chatgpt for small queries about my code where I couldn't necessarily see issues.

### Author

- Website (yet to be created)
- Frontend Mentor (https://www.frontendmentor.io)

### Acknowledgements

I learned a bit from [Josh Comeau](https://www.joshwcomeau.com/css/custom-css-reset/).
