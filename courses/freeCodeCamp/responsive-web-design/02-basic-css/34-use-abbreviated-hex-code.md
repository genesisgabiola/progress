# [Use Abbreviated Hex Code](https://learn.freecodecamp.org/responsive-web-design/basic-css/use-abbreviated-hex-code)

Many people feel overwhelmed by the possibilities of more than 16 million colors. And it's difficult to remember hex code. Fortunately, you can shorten it.

For example, red's hex code `#FF0000` can be shortened to `#F00`. This shortened form gives one digit for red, one digit for green, and one digit for blue.

This reduces the total number of possible colors to around 4,000. But browsers will interpret `#FF0000` and `#F00` as exactly the same color.

---

Go ahead, try using the abbreviated hex codes to color the correct elements.

| Color   | Short Hex Code |
| ------- | -------------- |
| Cyan    | #0FF           |
| Green   | #0F0           |
| Red     | #F00           |
| Fuchsia | #F0F           |

## Solution

```css
.red-text {
  color: #f00;
}
.fuchsia-text {
  color: #f0f;
}
.cyan-text {
  color: #0ff;
}
.green-text {
  color: #0f0;
}
```

```html
<h1 class="red-text">I am red!</h1>

<h1 class="fuchsia-text">I am fuchsia!</h1>

<h1 class="cyan-text">I am cyan!</h1>

<h1 class="green-text">I am green!</h1>
```