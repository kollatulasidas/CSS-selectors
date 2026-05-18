# CSS Selectors Demo

This project demonstrates how different CSS selectors work using a simple HTML page.

---

## 📁 Project Structure

```
index.html
style.css
README.md
```

---

## 🎯 Features Covered

### Element Selectors
Styles applied directly to HTML tags like:
- h1, h2, h4
- p
- ul, ol, li
- span

---

### Class Selector
Used to style multiple elements:

```html
<h1 class="head">Heading</h1>
```

---

### ID Selector
Used for unique elements:

```css
#para {
    color: darkgreen;
}
```

---

### Pseudo-class Selector (:nth-child)
Targets elements based on position:

```css
li:nth-child(1) a {
    background-color: yellow;
}

li:nth-child(2) a {
    background-color: lightblue;
}
```

Ordered list styling:

```css
ol li:nth-child(2) {
    color: blue;
}

ol li:nth-child(3) {
    color: red;
}
```

---

### Descendant Selector
Targets elements inside another element:

```css
p span {
    color: black;
    font-size: 25px;
}
```

---

### Global Styling

```css
body {
    background-color: rgb(250, 151, 129);
    border: solid black;
}
```

---

## 🧠 Key Concepts

- Element selectors apply styles to all matching tags
- Class selectors (.) can be reused
- ID selectors (#) are unique
- :nth-child() selects elements based on order
- Nested selectors help target specific elements

---

## 🚀 How to Run

1. Save the HTML file as `index.html`
2. Save the CSS file as `style.css`
3. Open `index.html` in a browser

---

## ⚠️ Common Mistakes

- Overusing ID selectors
- Writing overly complex selectors
- Misunderstanding :nth-child behavior
- Ignoring CSS specificity

---

## 🔥 Improvements

- Add hover effects for links
- Use :first-child and :last-child
- Try :nth-of-type()
- Learn Flexbox or Grid

---
