# Frontend Mentor - 3-column preview card component solution

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](/project-screenshot.png)


### Links

- Solution URL: [Add solution URL here](https://github.com/alisazarina/3-column-preview-card)
- Live Site URL: [Add live site URL here](https://alisazarina.github.io/3-column-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Visual Studio Code

### What I learned / for future reference

Adding fonts in the HTML code instead of manually downloading font files
👉🏼 reference: top "link rel" code in head section

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Big+Shoulders+Display:wght@700&display=swap" rel="stylesheet">
```

Adding variables via :root code
👉🏼 :root is a pseudo-class; used so that it can be applied globally across the HTML doc
    use variables to avoid repetitive code

```css
:root {
    --bright-orange: hsl(31, 77%, 52%);
    --dark-cyan: hsl(184, 100%, 22%);
    --very-dark-cyan: hsl(179, 100%, 13%);
    --transparent-white: hsla(0, 0%, 100%, 0.75);
    --very-light-gray: hsl(0, 0%, 95%);
}
```

**Note: Check out [The Markdown Guide](https://www.markdownguide.org/) for more help with writing markdown.

### Continued development

Need to work on Flexbox and CSS Grid knowledge, to make building responsive websites easier and faster. Try to master Vanilla CSS as much as possible before learning CSS Frameworks to gauge differences.

Also continue to use and learn the Git environment, though I've gotten better at working with the Terminal (Ubuntu or VS Code).

### Useful resources

- [MDN: CSS Flexbox](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox)
- [MDN: CSS :root](https://developer.mozilla.org/en-US/docs/Web/CSS/:root)
- [w3schools: CSS Variables - The var() function](https://www.w3schools.com/css/css3_variables.asp)
- [How to add images to README.md on GitHub?](https://stackoverflow.com/questions/14494747/how-to-add-images-to-readme-md-on-githubm)
- [How do you correct a bad git “remote add origin” command?](https://stackoverflow.com/questions/46860918/how-do-you-correct-a-bad-git-remote-add-origin-command)

*To fix Accessibility Issues:
- [HTML <"main"> element // semantic markup](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/main)
- [Visually hidden content for accessibility](https://www.frontendmentor.io/solutions/mobile-first-html-and-vanilla-css-ZtRIqu8KQ)

## Author

- Website (WIP) - [Alisa Zarina](https://alisazarina.com)
- Github - [alisazarina](https://github.com/alisazarina)
- Frontend Mentor - [@alisazarina](https://www.frontendmentor.io/profile/alisazarina)
- Twitter - [@alisazrna](https://www.twitter.com/alisazrna)
