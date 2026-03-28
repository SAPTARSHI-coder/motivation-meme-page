# 📋 Project Overview — Motivation Meme Landing Page

## 🎯 Goal
A very first CSS layout exercise — the simplest project in this collection. The objective is to take an unstyled HTML meme page and apply basic CSS to center the content, set the font, and make the layout presentable. Ideal for absolute beginners on Day 1 of CSS.

## 📄 HTML Structure
```html
<div>
  <img src="./assets/images/daenerys.jpeg" height="300px"/>
  <h1>THAT SPECIAL MOMENT</h1>
  <h5>When you find the perfect avocado from the supermarket</h5>
</div>
```
Note: There's a minor HTML bug — `<h5>` is closed with `</h6>`. In browsers, it still renders correctly, but it's not valid HTML. Good to notice!

## 🧠 Exercise Tasks

### Task 1: Center the Content
Wrap everything in a div and center it:
```css
div {
  width: 50%;
  margin-left: 25%;
  /* This horizontally centers a block element */
}
```

### Task 2: Center the Text
```css
h1, h5 {
  text-align: center;
}
```

### Task 3: Make the Image Fill the Div
```css
img {
  width: 100%;
  /* Image scales to match its parent container */
}
```

### Task 4: Uppercase Heading via CSS
```css
h1 {
  text-transform: uppercase;
}
```

### Task 5: Apply Google Font (Libre Baskerville)
Already imported in HTML `<head>`, just apply:
```css
body {
  font-family: 'Libre Baskerville', serif;
}
```

## 📊 Difficulty Level
| Aspect | Rating |
|---|---|
| HTML | ⭐ (minimal pre-written code) |
| CSS | ⭐ (5 simple properties) |
| Concepts | ⭐⭐ (centering, text-transform, font) |
| Overall | ⭐ Absolute Beginner |

## 🔍 What the HTML Bug Teaches
The `<h5>` closed with `</h6>` is a common HTML mistake. The browser still renders it because browsers are forgiving. However, HTML validators would flag this. Always close tags with the same tag you opened!

## 💡 Next Steps
- Add a background color to the page
- Style the subtitle differently from the heading
- Add `letter-spacing` to the heading for a dramatic effect
- Try centering with Flexbox instead of margin tricks
- Add a hover scale effect on the image
