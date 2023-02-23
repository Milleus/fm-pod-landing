# Frontend Mentor - Pod request access landing page solution

This is a solution to the [Pod request access landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/pod-request-access-landing-page-eyTmdkLSG). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements
- Receive an error message when the form is submitted if:
  - The `Email address` field is empty should show "Oops! Please add your email"
  - The email is not formatted correctly should show "Oops! Please check your email"

### Screenshot

Desktop view

<img src="./docs/landing-desktop.jpg?raw=true" width="100%" alt="desktop view"/>

Tablet view

<img src="./docs/landing-tablet.jpg?raw=true" width="768px" alt="tablet view"/>

Mobile view

<img src="./docs/landing-mobile.jpg?raw=true" width="375px" alt="mobile view"/>

### Links

- Solution URL: (to update)
- Live Site URL: [https://Milleus.github.io/fm-pod-landing/](https://Milleus.github.io/fm-pod-landing/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

- Using Constraint Validation APIs
- Email typeMismatch allows email addresses without a top-level domain, i.e. `x@y` is a valid email.
- Using patternMismatch to accept only emails with top-level domain.
- Setting `novalidate` with JavaScript instead of HTML allows for native form validation fallback when JavaScript fails

### Useful resources

- [Client-side form validation](https://developer.mozilla.org/en-US/docs/Learn/Forms/Form_validation)
- [Contraint validation](https://developer.mozilla.org/en-US/docs/Web/HTML/Constraint_validation)
- [input email validation](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/email#validation)
- [ARIA invalid](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Attributes/aria-invalid)
- [ARIA describedby](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Attributes/aria-describedby)
- [ARIA errormessage](https://w3c.github.io/aria/#aria-errormessage)

## Author

- Website - [Dave Quah](https://milleus.github.io/)
- Frontend Mentor - [@Milleus](https://www.frontendmentor.io/profile/Milleus)
- CodePen - [@Milleus](https://codepen.io/Milleus)
- LinkedIn - [@Milleus](https://www.linkedin.com/in/milleus/)
- Twitter - [@Milleus](https://www.twitter.com/Milleus)
