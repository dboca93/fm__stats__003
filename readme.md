# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

### Screenshots

**Desktop Screenshot**

![](./images/desktop__screenshot.png)

**Mobile/Tablet Screenshot**

![](./images/tablet__screenshot.png)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

### What I learned

In this project I learned about the following cool techniques. 

1. Using a mixture of fixed heights and auto within
a grid-template-row context: 

```
grid-template-rows: 21.9375rem auto;
```

2. Using a combination of gap, padding 
and exact fixed widths with a grid context to space
out the text exactly how we want. This is crucial 
on small screen sizes: 

```
  .hero__section article {
    gap: 0.125rem;
    padding: 0.3125rem 1.5625rem;
    grid-template-rows: 6.5625rem 7.1875rem 16.5625rem;
  }
```

3. In order to create the change in color we 
see in the image, I used a background--linear-gradient
on the picture element, while using mix-blend-mode: multiply on the img, as seen below: 

```
.hero__section picture {
  grid-area: picture__area;
  background: linear-gradient(180deg, #ff61f3 0, #b86ffb 100%);
}
.hero__section picture img {
  width: 100%;
  height: 100%;
  display: block;
  -o-object-fit: cover;
     object-fit: cover;
  mix-blend-mode: multiply;
}
```
## Author

Dilhan Boca

Frontend Mentor Profile: 

Gmail: dboca93@gmail.com

- Frontend Mentor - [@dboca93](https://www.frontendmentor.io/profile/dboca93
)