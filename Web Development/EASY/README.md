# 🌟 Responsive Perfume Card Design

Welcome to my **Responsive Perfume Card** project! 💫 This simple yet elegant card is designed to be fully responsive using **HTML** and **CSS**. It showcases a premium perfume product in style! Here's how I made it:

---

## 🔨 How I Built It

## 1. Setup the HTML Structure 🏗️
   - I started by creating the foundation of the card with **HTML**. This includes headings, a product image, a description, the price, and a stylish **BUY NOW** button.

```html
<div class="container">
  <div><p class="heading">Premium Perfume presents:</p></div>
  <div><p class="perfume-name">French Essence Perfume</p></div>
  <div class="box">
    <img class="perfume" src="imageperfume.webp" alt="Perfume" />
  </div>
  <p class="description">Experience the allure of timeless sophistication with French Essence Perfume, crafted to evoke elegance and confidence...</p>
  <p class="price">$200.90 <span class="Only">ONLY</span></p>
  <p><button class="Buynow">BUY NOW</button></p>
</div>
```
## 2. Styling with CSS 🎨
•<strong>Fonts: </strong>I gave the card a classy and modern look by adding Google Fonts like Dancing Script for a touch of elegance.<br><br>
•<strong>Layout: </strong>Created a grid layout for a structured appearance, adding margins and borders for a polished design.<br><br>
•<strong>Button: </strong>Designed an attractive BUY NOW button with hover effects, ensuring it's visually engaging! 🛒<br>

```css
.container {
  grid-template-rows: auto auto auto auto auto;
  grid-template-columns: auto auto;
  grid-gap: 3px;
}

.perfume {
  width: 300px;
  height: 300px;
  border-radius: 10px;
  margin-bottom: 25px;
}

.Buynow {
  color: white;
  background-color: green;
  padding: 10px;
  border-radius: 8px;
  box-shadow: 2px 2px 8px rgb(49, 60, 48);
}

.Buynow:hover {
  opacity: 0.8;
}
```
## 3. Making It Responsive 📱💻
To ensure the card looks great on any screen, I used media queries to adjust the layout for smaller devices. Now, it's perfectly responsive! 🙌

```css
@media(max-width:600px) {
  .container {
    flex-direction: column;
  }
}
```

### Key Features ✨ <br>
•Responsive Design: Works seamlessly across different devices.<br><br>
•Clean Layout: Aesthetic use of fonts, borders, and colors.<br><br>
•Engaging Button: Hover and active states for interactivity.<br>

---
Feel free to check out the code and experiment with it! 🚀
```
You can copy and paste this markdown into your README file on GitHub. It will format beautifully with the emojis and code snippets!
```
