# Frontend Mentor - Loopstudios landing page solution

This is a solution to the [Loopstudios landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/loopstudios-landing-page-N88J5Onjw). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)


### Screenshot

![](solution.jpg)


### Links

- Live Site URL: [Add live site URL here](https://shemjay.github.io/loopstudios-landing-page/) ("Github")
- Live Site URL: [Add live site URL here](https://friendly-manatee-d9c944.netlify.app) ("Netlify")

## My process

### Built with

- Semantic HTML5 markup
- Flexbox
- CSS Grid

### What I learned

Like this code cause its how I made the grid image layout. Took me a bit longer than expected.

```css
.grid-display {
    display: grid;
    grid-template-columns: repeat(4, 250px);
    grid-template-rows: 1fr 1fr;
    grid-column-gap: 1em;
    grid-row-gap: 1em;
}

.grid-img {
    position: relative;
    display: flex;
    justify-content: center;
    align-items: flex-end;
    flex-direction: row;
}

.grid-img img {
    height: 100%;
    width: 100%;
    object-fit: contain;
}
```

Also a fan of this cause i learned how to hover two elements at the same time:
```css
.grid-img:hover img {
    transition: 0.2s ease-in-out;
    opacity: .3;
    background-color: hsl(0, 0%, 55%);
}

.grid-img:hover p {
    transition: 0.2s ease-in-out;
    color: hsl(0, 0%, 0%);
}
```



### Continued development

-Need to work on Grid layout. It really kicked my butt when making the grid layout lmao.

## Author

- Frontend Mentor - [@shemjay](https://www.frontendmentor.io/profile/shemjay)
- Twitter - [@shemstack](https://www.twitter.com/shemstack)



