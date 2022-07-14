# Order summary card solution

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

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![](Order%20summary%20card%20%E2%80%94%20Firefox%20Developer%20Edition%2014-07-2022%2022_43_54.png)

### Mobile view

![](./design/mobile-design.jpg)

### Links

- Solution URL: [https://github.com/Yashasewi/order-summary-component](https://github.com/Yashasewi/order-summary-component)
- Live Site URL: [https://yashasewi.github.io/order-summary-component/](https://yashasewi.github.io/order-summary-component/)

## My process

## Building your project

Feel free to use any workflow that you feel comfortable with. Below is a suggested process, but do not feel like you need to follow these steps:

1. Initialize your project as a public repository on [GitHub](https://github.com/). Creating a repo will make it easier to share your code with the community if you need help. If you're not sure how to do this, [have a read-through of this Try Git resource](https://try.github.io/).
2. Configure your repository to publish your code to a web address. This will also be useful if you need some help during a challenge as you can share the URL for your project with your repo URL. There are a number of ways to do this, and we provide some recommendations below.
3. Look through the designs to start planning out how you'll tackle the project. This step is crucial to help you think ahead for CSS classes to create reusable styles.
4. Before adding any styles, structure your content with HTML. Writing your HTML first can help focus your attention on creating well-structured content.
5. Write out the base styles for your project, including general content styles, such as `font-family` and `font-size`.
6. Start adding styles to the top of the page and work down. Only move on to the next section once you're happy you've completed the area you're working on.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- CSS Variables
- CSS Custom Properties
- [Styled Components](https://styled-components.com/) - For styles

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<div class="info">
  <h1 class="heading">Order Summary</h1>
  <p class="card_info">
    You can now listen to millions of songs, audiobooks, and podcasts on any
    device anywhere you like!
  </p>
</div>
```

```css
@media screen and (max-width: 40rem) {
  body {
    background-image: url(./images/pattern-background-mobile.svg);
    background-repeat: no-repeat;
    background-size: contain;
    width: auto;
    height: auto;
    padding: 0;
    margin: 0;
  }
  .card {
    width: 100%;
    height: auto;
    min-height: auto;
    max-height: auto;
  }
  .card_content {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    width: 100%;
    height: auto;
    padding: 2rem 2rem 0rem 2rem;
  }
}
```

### Continued development

This project is done.

### Useful resources

- [CssGrid](https://www.example.com) - This helped me for fixing css grid issues.
- [W3 Schools](https://www.w3schools.com/css/) - This is an amazing article which helped me finally understand Css. I'd recommend it to anyone still learning this concept.

## Author

- Website - [Live Url](https://yashasewi.github.io/order-summary-component//)
- Frontend Mentor - [@Yashasewi](https://www.frontendmentor.io/profile/Yashasewi)
- Twitter - [@yashasewi](https://twitter.com/yashasewi)

## Acknowledgments

I alone worked on this project. I did not receive any outside help from anyone.
