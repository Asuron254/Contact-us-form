
# Frontend Mentor - Contact Us Form

This is a solution to the [Contact Us Form challenge on Frontend Mentor](https://www.frontendmentor.io). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of Contents

- [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Continued Development](#continued-development)
  - [Useful Resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The Challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover and focus states for all interactive elements on the page
- Receive form validation messages if:
  - A field is left blank
  - The email address is not formatted correctly

### Screenshot

![Screenshot of the solution](./screenshot.png)

### Links

- Solution URL: [Add your solution URL here](https://your-solution-url.com)
- Live Site URL: [Add your live site URL here](https://your-live-site-url.com)

## My Process

### Built With

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [React](https://reactjs.org/) - JS library (if applicable)
- [Next.js](https://nextjs.org/) - React framework (if applicable)
- [Styled Components](https://styled-components.com/) - For styles (if applicable)

### What I Learned

During this project, I reinforced my knowledge of form validation and responsiveness. Here are some code snippets that I am proud of:

```html
<form id="contact-form">
  <div class="form-control">
    <label for="name">Name</label>
    <input type="text" id="name" name="name" required />
    <small>Error message</small>
  </div>
  <div class="form-control">
    <label for="email">Email</label>
    <input type="email" id="email" name="email" required />
    <small>Error message</small>
  </div>
  <div class="form-control">
    <label for="message">Message</label>
    <textarea id="message" name="message" required></textarea>
    <small>Error message</small>
  </div>
  <button type="submit">Send</button>
</form>

