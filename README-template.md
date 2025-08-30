# Frontend Mentor - Huddle landing page with curved sections solution

This is a solution to the [Huddle landing page with curved sections challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-curved-sections-5ca5ecd01e82137ec91a50f2). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- Accessibility
- Performance
- NVDA (screen reader tested)

### What I learned

The project help me practice my use of semantic tags and ARIA at making the project more accessible. On CSS it helped me get more experience at using Grid and flex.

To see how you can add code snippets, see below:

```html
<article class="main__stats container">
  <figure class="main__communities">
    <img
      src="images/icon-communities.svg"
      alt=""
      class="main__communities-svg"
    />
    <p class="main__communities-stats heading">1.4k+</p>
    <figcaption class="main__communities-formed">Communities Formed</figcaption>
  </figure>

  <figure class="main__messages">
    <img src="images/icon-messages.svg" alt="" class="main__messages-svg" />
    <p class="main__messages-stats heading">2.7m+</p>
    <figcaption class="main__messages-sent">
      <span
        >Messages<br />
        Sent</span
      >
    </figcaption>
  </figure>
</article>
```

```css
.main__grow-together .main__illust-container,
.main__your-users .main__illust-container {
  grid-column: 2 /-1;
  grid-row: 1;
}

.footer__newsletter {
  grid-column: 2;
  grid-row: 1;
}
```

### Useful resources

- [Example resource 1](https://www.frontmentor.io)

## Author

- Website - [Add your name here](https://pastasus.github.io/huddle-landing-page-with-curved-sections-master/)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/PastaSus)

## Acknowledgments

Really thankful to the people who gave me feedback on this project. Specially to front-end-mentor.io members/mods
