<div align="center">

# 🚀 CSS Learning Portfolio

### Building My Full Stack Development Journey, One Lesson at a Time.

<img src="https://img.shields.io/badge/Status-In%20Progress-00C853?style=for-the-badge" />
<img src="https://img.shields.io/badge/Lessons-15%2B-2196F3?style=for-the-badge" />
<img src="https://img.shields.io/badge/Language-HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white" />

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
# Lesson 14: CSS Outline

An **outline** is a line drawn outside the border of an element (outside the border edge) to make the element stand out or indicate focus state (e.g., input fields or buttons during navigation).

---

## Key Differences: Border vs Outline

| Feature              | CSS Border                                                                   | CSS Outline                                                          |
| :------------------- | :--------------------------------------------------------------------------- | :------------------------------------------------------------------- |
| **Box Model Impact** | Affects the size of the element and takes up space in layout calculations.   | Does **not** take up space or affect element dimensions/layout.      |
| **Sides**            | Can be customized individually per side (`border-top`, `border-left`, etc.). | Applied equally to **all sides at once** (cannot set `outline-top`). |
| **Position**         | Placed inside the margin.                                                    | Placed outside the border (can overlap surrounding elements).        |

---

## 1. CSS Outline Style

The `outline-style` property specifies the style of an outline.

> **Important:** An outline will not appear unless `outline-style` (or the shorthand `outline`) is set!

### Allowed Values:

- `dotted` - Defines a dotted outline.
- `dashed` - Defines a dashed outline.
- `solid` - Defines a solid outline.
- `double` - Defines a double line outline.
- `groove` - Defines a 3D grooved outline.
- `ridge` - Defines a 3D ridged outline.
- `inset` - Defines a 3D inset outline.
- `outset` - Defines a 3D outset outline.
- `auto` - Allows the browser to display a default user-interface style.
- `hidden` / `none` - Removes the outline.

---

```CSS
    /* test1.html */
    <style>
        .p1 {
            outline-style: dotted;
        }
        .p2 {
            outline-style: dashed;
        }
        .p3 {
            outline-style: double ;
        }
        .p4 {
            outline-style: groove ;
        }
        .p5 {
            outline-style:auto ;
        }
        .p6 {
            outline-style: hidden ;
        }
        .p7 {
            outline-style: ridge ;
        }
        .p8 {
            outline-style: outset  ;
        }
        .p9 {
            outline-style: invert ;
        }
        .p10 {
            outline-style: none ;
        }
    </style>
```

---

## 2. CSS Outline Width

The `outline-width` property sets the thickness of the outline.

Values can be pre-defined keywords (`thin`, `medium`, `thick`) or specific measurement units (`px`, `pt`, `em`, etc.).

```CSS
    /* test2.html */
    <style>
        p {
            padding: 5px;
            outline-style: solid;
            outline-color: green;
        }

        .p1 {
            outline-width: thin;
        }

        .p2 {
            outline-width: medium;
        }

        .p3 {
            outline-width: thick;
        }

        .p4 {
            outline-width: 8px;
        }

    </style>
```

---

## 3. CSS Outline Color

The `outline-color` property sets the color of the outline using standard color syntax:

- Color Names: `red`, `black`, `antiquewhite`, etc.
- HEX Values: `#10a352`
- HSL Values: `hsl(233, 82%, 35%)`
- HWB Values: `hwb(327 6% 36%)`

```CSS
    /* test3.html */
    <style>
        p {
        padding:10px;
        }
        .p1 {
            outline-style: dotted;
            outline-color:black;
        }
        .p2 {
            outline-style: dashed;
            outline-color: red;
        }
        .p3 {
            outline-style: double ;
            outline-color: #10a352;
        }
        .p4 {
            outline-style: groove ;
            outline-color: hsl(233, 82%, 35%);
        }
        .p5 {
            outline-style:auto ;
            outline-color: hwb(327 6% 36%);
        }
        .p6 {
            outline-style: ridge ;
            outline-color: antiquewhite;
        }
        .p7 {
            outline-style: outset  ;
            outline-color: chartreuse;
        }

    </style>
```

---

## 4. CSS Outline Shorthand

The `outline` property is a shorthand property for setting width, style, and color in a single declaration.

**Syntax Order:**
`outline: [outline-width] [outline-style] [outline-color];`

```CSS
    <style>
        p {
            padding: 5px;
            outline: 10px outset red;
        }
    </style>
```

---

## 5. CSS Outline With Rounded Corners

When `border-radius` is applied to an element that has an outline, modern browser implementations follow the element's border radius curves.

```CSS
    <style>
        p {
            padding: 5px;
            outline: 10px outset red;
            border-radius: 5px;
            width: 300px;
            margin-left: 10px;
        }
    </style>
```

---

## 6. CSS Outline Offset

The `outline-offset` property adds space between an element's border edge and its outline. The space between the element and its outline is transparent.

```CSS
    /* test6.html */
    <style>
        p {
            outline-offset: 15px;
        }
    </style>
```
