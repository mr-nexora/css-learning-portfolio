<div align="center">

# 🚀 CSS Learning Portfolio

### Building My Full Stack Development Journey, One Lesson at a Time.

<img src="https://img.shields.io/badge/Status-In%20Progress-00C853?style=for-the-badge" />
<img src="https://img.shields.io/badge/Lessons-15%2B-2196F3?style=for-the-badge" />
<img src="https://img.shields.io/badge/Language-CSS-E34F26?style=for-the-badge&logo=html5&logoColor=white" />


<br><br>

<a href="https://github.com/mr-nexora">
<img src="https://img.shields.io/badge/GitHub-mr--nexora-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<a href="https://www.linkedin.com/in/mrnexora/">
<img src="https://img.shields.io/badge/LinkedIn-Sahan%20Udara-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<a href="https://mr-nexora.github.io/mr-nexora-personal-portfolio/">
<img src="https://img.shields.io/badge/Portfolio-Visit%20Website-6C63FF?style=for-the-badge&logo=googlechrome&logoColor=white"/>
</a>

</div>

---

# 👋 Welcome

Welcome to my **CSS Learning Repository**.

This repository showcases my journey of learning modern CSS, including layouts, Flexbox, Grid, animations, responsive design, and UI styling. Each lesson contains source code, notes, screenshots, and practical exercises to improve my front-end development skills.

---

# 📂 Repository Overview

| 📌 Information | Details |
|:---------------|:--------|
| 👨‍💻 Author | **T.M.S.U. Thennakoon (Sahan Udara)** |
| 🎓 Program | Computer Science Undergraduate |
| 💻 Technology | CSS3 |
| 📚 Learning Method | Daily Lessons & Hands-on Practice |
| 🎯 Goal | Become a Professional Full Stack Developer |
| 📅 Repository Started | 2026 |

---

# ✨ What's Inside

- 📖 Structured Lessons
- 💻 Source Code
- 📷 Output Screenshots
- 📝 Markdown Notes
- 🚀 Mini Projects
- 📚 Practice Exercises
- 📈 Continuous Progress Updates

---

# 🌍 Connect With Me

<div align="center">

<a href="https://github.com/mr-nexora">
<img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github"/>
</a>

<a href="https://www.linkedin.com/in/mrnexora/">
<img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin"/>
</a>

<a href="https://mr-nexora.github.io/mr-nexora-personal-portfolio/">
<img src="https://img.shields.io/badge/Portfolio-Visit-6C63FF?style=for-the-badge&logo=googlechrome"/>
</a>

</div>

---

# 📚 Learning Resources

This repository is built through continuous practice using educational resources such as:

- W3Schools
- MDN Web Docs
- freeCodeCamp


---

# ⚖️ Copyright

> **© 2026 T.M.S.U. Thennakoon (Sahan Udara). All Rights Reserved.**
>
> This repository has been created for educational, portfolio, and personal learning purposes.
>
> You are welcome to explore the code and learn from it. However, copying, redistributing, or presenting this work as your own without permission is not allowed.

---
<div align="center">

⭐ If you find this repository useful, consider giving it a Star.

Happy Coding! 🚀

</div>

---

# Lesson 05: CSS Comments & Code Documentation

Comments are an essential part of writing clean, maintainable, and readable CSS code. They are ignored by web browsers and serve as notes or instructions for developers.

---

## 1. What are CSS Comments?

CSS comments are used to explain code, leave reminders, or temporarily prevent the browser from executing specific style rules during testing and debugging.

- Comments do **not** render on the web page.
- They are enclosed within `/*` and `*/`.
- CSS does **not** support standard HTML comment syntax (`<!-- -->`) or JavaScript single-line comments (`//`).

---

## 2. Types of CSS Comments

### I. Single-line Comments

Even though CSS doesn't have a distinct syntax for single lines, you can write a comment on a single line using the standard `/* ... */` syntax.

```css
/* This is a single-line CSS comment */
p {
  color: #333333; /* Sets paragraph text color to dark gray */
}
```

### II. Multi-line Comments

If your note spans across multiple lines, you can wrap all lines inside a single pair of comment delimiters.

```css
/* 
    ==========================================
    MAIN NAVIGATION STYLES
    ==========================================
    This section controls the header navigation bar,
    dropdown menus, and mobile drawer styles.
    */

.navbar {
  background-color: #1a1a1a;
  display: flex;
  justify-content: space-between;
}
```

## 3. Practical Uses of CSS Comments

### A. Code Organization & Structuring

In larger CSS projects, comments help divide the stylesheet into clear, searchable sections.

```CSS
/* ==================== 1. GLOBAL RESETS ==================== */
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

/* ==================== 2. TYPOGRAPHY ==================== */
h1, h2, h3 {
  font-family: 'Inter', sans-serif;
  color: #222;
}

/* ==================== 3. BUTTONS & UI ==================== */
.btn-primary {
  background-color: #007bff;
  color: #ffffff;
  border-radius: 4px;
}
```

### B. Commenting Out Code (Debugging)

During development, you can temporarily disable certain CSS declarations to troubleshoot layout or visual bugs without deleting your code.

```CSS
.card {
  width: 300px;
  background-color: #f9f9f9;
  /* border: 2px solid red; */ /* Disabled for testing */
  padding: 20px;
}
```
