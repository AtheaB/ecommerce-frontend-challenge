# 🛒 E-commerce Frontend Challenge

This repository contains my submission for the **24-hour eCommerce Front End Developer Code Challenge**.  
The objective was to build a **responsive, pixel-perfect homepage** based on the provided design mockup, using modern front-end best practices.

---

## 🚀 Tech Stack

- **HTML5** – semantic structure
- **SCSS (Sass)** – modular, component-based styling
- **Foundation Framework** – grid system & utilities
- **JavaScript (ES6)** – interactions & DOM scripting
- **Flickity** – lightweight, touch-friendly carousel
- **Google Fonts** – typography

---

## 📂 Project Structure

```
/scss         → SCSS partials (variables, mixins, components)
/css          → Compiled CSS
/assets       → Images & icons, and Fonts from design mockup
index.html    → Homepage implementation
```

---

## ⚙️ Setup & Usage

1. **Clone the repository**

   ```bash
   git clone https://github.com/<your-username>/ecommerce-frontend-challenge.git
   cd ecommerce-frontend-challenge
   ```

2. **Compile SCSS → CSS**  
   Make sure Sass is installed globally:

   ```bash
   npm install -g sass
   ```

   Then run:

   ```bash
   sass scss/main.scss css/main.css --watch
   ```

3. **Open the project**  
   Simply open `index.html` in your browser.

---

## 📱 Features

- **Responsive Design** → Mobile-first, scales to desktop seamlessly
- **Pixel-perfect Layout** → Matches the provided Sketch mockup
- **BEM Naming Convention** → Consistent, scalable class structure
- **Reusable SCSS Variables** → Colors, typography, spacing centralized
- **Modern Practices** → Semantic HTML5, flexbox & CSS grid

---

## 🎥 Demo

📌 (Optional: Add a GIF or link to your recorded walkthrough video here)

---

## 📝 Notes

- Built with a **scalable SCSS architecture** (`_variables.scss`, `_mixins.scss`, `_components.scss`)
- Media queries are written **inline within components** for modularity

---

✅ **In summary**: This project demonstrates a clean, maintainable, and scalable approach to front-end development, balancing **design accuracy**, **responsive behavior**, and **code organization**.
