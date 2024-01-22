# Frontend Mentor - Results summary component solution

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
- [Acknowledgments](#acknowledgments)


## Overview
I have designed a *result summary component* for the front-end mentor challenge. which was helpful in further enhancing my development skills.

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page
- **Bonus**: Use the local JSON data to dynamically populate the content

### Screenshot
You can see my design below 😊.

![](assets/images/desktop-design.png)
![](assets/images/mobile-design.png)

### Links

- Solution URL: checkout my solution on [Frontend mentor]()
- Live Site URL: checkout my live site [here]()

## My process
For this challenge I decided to test out bootstrap first I had imported bootstrap in HTML as a link but then later I came across CSS `@layer` feature and learned it was a nice way to overwrite the default bootstrap style. Then I learned to import bootstrap into CSS with `@import` and put it in a layer named framework and gave it a low specificity. Feel free to go through my code to see more.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- [Bootstrap](https://getbootstrap.com/)

### What I learned

By doing this challenge: 
- I was able to improve my knowledge in *Bootstrap*.
- I learned to use the CSS `@Layer` feature. Which was really useful in overwriting the default bootstrap styles.
- I learned that you could import frameworks as a cascade layer and give it a lower specificity to overwrite the defaults.
- I also learned that the `@import` would cause some loading latency and the way to solve it was to use the `@import` in the internal style.

### Useful resources
- [Web Dev simplified video on CSS layers](https://www.youtube.com/watch?v=Pr1PezCc4FU&t=630s&ab_channel=WebDevSimplified) - I learned to use CSS layers from this video.
- [Kevin Powell's video on CSS layers](https://www.youtube.com/watch?v=NDNRGW-_1EE&t=3s&ab_channel=KevinPowell) - Also watched this to further explore on CSS layers but both videos almost had the same contents.
- [Stephanie Eckles article on CSS cascade layers](https://www.smashingmagazine.com/2022/01/introduction-css-cascade-layers/) - This articles also offers a dive into the CSS cascading layers.
- [Keith J. Grant's article on CSS resets](https://keithjgrant.com/posts/2024/01/my-css-resets/) - Got my CSS reset from here.


## Author

- Frontend Mentor - [@tenze21](https://www.frontendmentor.io/profile/tenze21)
- Twitter - [@TenzinChoe17842](https://www.twitter.com/TenzinChoe17842)

## Acknowledgments
I am greatful to the frontend mentor community for their amazing challenges and unwavering support for new developers. I am also greateful to the author of the materials I have linked above which provided me with new insights.
