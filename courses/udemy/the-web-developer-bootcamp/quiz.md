# Quizzes

## Table of Contents <!-- omit in toc -->

- [Quiz 1: Color Quiz](#quiz-1-color-quiz)
- [Quiz 2: Specificity Quiz](#quiz-2-specificity-quiz)


## Quiz 1: Color Quiz

Question 1: Which of the following rgb colors results in the following shade of green:

![RGB color](https://img-a.udemycdn.com/redactor/raw/2020-09-19_19-11-23-b20703576a31744b636469184f2d6407.png?05X4IerTqvMKCp9g8eBPh08RgUXzVVGIX5dZyVy_byPWZcSL1lMQKYbg9R5hmCtxD1Hg0RhDjj2W3XRAEEI0wjKd-qcc_nN1NyjyeQKTNYC-zw8mFco3p0kQGlGXmuII5tVr852iDwfobNR_3xQmrMRzJDO28rvDfYgbHUinwQOY7ilF)

- [ ] `rgb(255, 0, 255);`
- [ ] `rgb(0, 0, 255);`
- [ ] `rgb(0, 400, 0);`
- [x] `rgb(0, 200, 0);`

Question 2: Which of the following hex color codes is equivalent to `rgb(255,255,255)`?

- [ ] `#facedf`
- [ ] `#000000`
- [x] `#ffffff`


## Quiz 2: Specificity Quiz

Question 1: Given the following HTML markup:

```html
<ul>
  <li class="nav-link">Home</li>
</ul>
```

And these CSS styles:

```css
li {
  color:orange;
}
.nav-link {
  color: magenta;
}
ul li {
  color: blue;
}
```

What color will the `<li>` element be?

- [ ] orange
- [x] magenta
- [ ] blue

Question 2: Given this html markup:

```html
<p>
  <button id="submit" class="btn">Submit</button>
</p>
```

And these CSS styles:

```css
#submit {
  color: blue;
}
 
.btn {
  color: pink;
}
 
p button.btn {
  color: purple;
}
```

What color will the button end up?

- [x] blue
- [ ] pink
- [ ] purple

Question 3: Given the following HTML:

```html
<section class="about">
  <h2 class="heading">Welcome To My Page</h2>
</section>
```

And these styles:

```css
.about .heading {
  color: orange;
}
 
.about h2.heading {
  color: pink;
}
 
section.about .heading {
  color: yellow;
}
```

What color will the h2 end up?

- [ ] orange
- [ ] pink
- [x] yellow
