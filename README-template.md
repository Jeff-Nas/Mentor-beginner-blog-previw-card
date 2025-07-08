# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Blog preview card solution](#frontend-mentor---blog-preview-card-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
  - [Author](#author)



## Overview

My challange was to recreate this card for Blog presentation. 

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](/assets/images/screen-shot.png)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it. 

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Media Queries


### What I learned

I learned to use `tabindex="0"` to make an element that is not naturally focusable (like <div>, <span>, <li>, etc.) receive focus with Tab.
I also learned that when inserting an image into a container, it must have its height and width properties defined. Otherwise the image will try to fill 100% of the header height, but the header will automatically try to adapt to the image size. This creates an ineffective loop, and the image cropping never happens.


```html
<h1 `tabindex="0"`>Some HTML code I'm proud of</h1>
```
```css
.card>header {
    height: 12rem;
    overflow: hidden;
    border-radius: 12px;
}
```

## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/Jeff-Nas)
- Twitter - [@yourusername](https://x.com/Jeferso65230539)



