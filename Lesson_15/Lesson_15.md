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

<a href="https://yourportfolio.com">
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

<a href="https://yourportfolio.com">
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
# Lesson 15: CSS Text Styling and Formatting

CSS provides an extensive set of properties for formatting text, controlling colors, alignments, decorations, transformations, letter/word spacing, and shadows.

---

## 1. CSS Text Color

The `color` property is used to set the color of text elements. You can specify values using standard color formats (RGB, HEX, HSL, or color keywords).

```CSS
    /* test1.html */
    <style>
        h1 {
            color: rgb(90, 37, 28);
        }
        h2 {
            color: rgb(29, 26, 186);
        }
        h3 {
            color: rgb(105, 218, 56);
        }
        h4 {
            color: rgb(255, 70, 233);
        }
        h5 {
            color: rgb(238, 231, 40);
        }
        h6 {
            color: rgb(97, 244, 121);
        }
    </style>
```

---

## 2. Text Color and Background Color

Always ensure proper contrast between the text color and background color to maintain accessibility and readability.

```CSS
    /* test2.html */
    <style>
        h1 {
            color: white;
            background-color: rgb(90, 37, 28);
        }
        h2 {
            color: white;
            background-color: rgb(29, 26, 186);
        }
        h3 {
            background-color: rgb(105, 218, 56);
        }
        h4 {
            color: white;
            background-color: rgb(255, 70, 233);
        }
        h5 {
            color: white;
            background-color: rgb(238, 231, 40);
        }
        h6 {
            color: white;
            background-color: rgb(97, 244, 121);
        }
    </style>
```

---

## 3. CSS Text Alignment

### I. Text Alignment (`text-align`)

The text-align property sets the horizontal alignment of text within its container (`left`, `right`, `center`, `justify`).

```CSS
    /* test3.html */
    <style>
        h1 {
            text-align: center;
        }
        h3 {
            text-align: right;
        }
        h4 {
            text-align: left;
        }

    </style>
```

---

### II. Text Align Last (`text-align-last`)

The `text-align-last` property sets how the last line of a paragraph (or a line right before a manual line break `<br>`) is aligned.

```CSS
    /* test4.html */
    <style>
        .p1 {
            text-align-last:auto;
        }
        .p2 {
            text-align-last:center;
        }
        .p3 {
            text-align-last:justify;
        }
        .p4 {
            text-align-last:left;
        }
        .p5 {
            text-align-last:right;
        }
        .p6 {
            text-align-last:start;
        }
        .p7 {
            text-align-last:end;
        }
    </style>
```

---

### III. Vertical Alignment (`vertical-align`)

The `vertical-align` property sets the vertical alignment of an inline, inline-block, or table-cell element relative to surrounding text or line boxes.

```CSS
    /* test5.html */
    <style>
        .p1 {
            vertical-align:auto ;
        }
        .p2 {
            vertical-align:baseline ;
        }
        .p3 {
            vertical-align:bottom ;
        }
        .p4 {
            vertical-align:middle ;
        }
        .p5 {
            vertical-align:sub ;
        }
        .p6 {
            vertical-align:super ;
        }
        .p7 {
            vertical-align:text-bottom ;
        }
        .p8 {
            vertical-align:text-top ;
        }
        .p9 {
            vertical-align:top ;
        }

    </style>
```

---

### IV. Text Direction (`direction` & `unicode-bidi`)

The `direction` property paired with `unicode-bidi` can change the text writing direction (e.g., Right-To-Left `rtl` for Arabic/Hebrew).

```CSS
    /* test6.html */
    <style>
        p {
            direction: rtl;
            unicode-bidi: bidi-override;
        }
    </style>
```

---

## 4. CSS Text Decoration

### I. text-decoration-line

Specifies which decoration lines to render on text (`none`, `underline`, `overline`, `line-through`).

```CSS
    /* test7.html */
    <style>
        .p1 {
            text-decoration-line:none ;
        }
        .p2 {
            text-decoration-line: underline ;
        }
        .p3 {
            text-decoration-line:overline ;
        }
        .p4 {
            text-decoration-line:overline underline ;
        }
        .p5 {
            text-decoration-line:line-through ;
        }
    </style>
```

---

### II. text-decoration-color

Sets the color of the text decoration line.

```CSS
    /* test8.html */
    <style>
        .p1 {
            text-decoration-line:none ;
            text-decoration-color: brown;
        }
        .p2 {
            text-decoration-line: underline ;
            text-decoration-color: rgb(42, 165, 81);
        }
        .p3 {
            text-decoration-line:overline ;
            text-decoration-color: rgb(45, 198, 190);
        }
        .p4 {
            text-decoration-line:overline underline ;
            text-decoration-color: rgb(241, 247, 50);
        }
        .p5 {
            text-decoration-line:line-through ;
            text-decoration-color: rgb(255, 49, 49);
        }
    </style>
```

---

### III. text-decoration-style

Sets the style of the decoration line (`solid, dotted, dashed, double, wavy`).

```CSS
    /* test9.html */
    <style>
        .p1 {
            text-decoration-style: none;
        }
        .p2 {
            text-decoration-style:dotted;
        }
        .p3 {
            text-decoration-style:double;
        }
        .p4 {
            text-decoration-style:solid;
        }
        .p5 {
            text-decoration-style:dashed;
        }
        .p6 {
            text-decoration-style:wavy;
        }

    </style>
```

---

### IV. text-decoration-thickness

Sets the stroke thickness of the decoration line.

```CSS
    /* test10.html */
    <style>
        h3 {
            text-decoration-line: underline;
            text-decoration-thickness: auto;
        }

        h4 {
            text-decoration-line: underline;
            text-decoration-thickness: 5px;
        }

        h5 {
            text-decoration-line: underline;
            text-decoration-thickness: 25%;
        }

        p {
            text-decoration-line: underline;
            text-decoration-color: red;
            text-decoration-style: double;
            text-decoration-thickness: 5px;
        }
    </style>
```

### V. Text Decoration Shorthand Property

You can set line type, color, style, and thickness in a single declaration.

**Syntax:** `text-decoration: [line] [color] [style] [thickness];`

```CSS
    /* test11.html */
    <style>
        p {
            text-decoration: underline red double 5px;
        }
    </style>
```

---

## 5. CSS Text Transformation

The `text-transform` property controls capitalization of text.

```CSS
    /* test12.html */
    <style>
        .p1 {
            text-transform: none;
        }
        .p2 {
            text-transform:capitalize;
        }
        .p3 {
            text-transform:lowercase;
        }
        .p4 {
            text-transform:uppercase;
        }
    </style>
```

---

## 6. CSS Text Spacing

### I. text-indent

Specifies the indentation of the first line in a paragraph.

```CSS
    /* test13.html */
    <style>
        p {
            text-indent: 50px;
        }
    </style>
```

---

### II. letter-spacing

Specifies the space between characters/letters in a text. Can take positive or negative length values.

```CSS
    /* test14.html */
    <style>
        .p1 {
            letter-spacing: 20px;
        }
        .p2 {
            letter-spacing: -10px;
        }
    </style>
```

---

### III. line-height

Specifies the vertical space between lines of text (leading).

```CSS
    /* test15.html */
    <style>
        .p1 {
            line-height: 0.8;
        }
        .p2 {
            line-height: 2;
        }
        .p3 {
            line-height: 5;
        }
    </style>
```

---

### IV. word-spacing

Specifies the space between words in a text.

```CSS
    /* test16.html */
    <style>
        .p1 {
            word-spacing: 40px;
        }
        .p2 {
            word-spacing: -20px;
        }
    </style>
```

---

### V. white-space

Specifies how white-space inside an element is handled (`normal, nowrap, pre, pre-line, pre-wrap`).

```CSS
    /* test17.html */
    <style>
        p {
            font-size: 25px;
        }
        .p1 {
            white-space:normal;
        }
        .p2 {
            white-space:nowrap;
        }
        .p3 {
            white-space:pre;
        }
        .p4 {
            white-space:pre-line;
        }
        .p5 {
            white-space:pre-wrap;
        }
    </style>
```

---

## 7. CSS Text Shadow

The `text-shadow` property adds shadow effect to text.

**Syntax:** `text-shadow: [horizontal-offset] [vertical-offset] [blur-radius] [color];`

```CSS
    /* test18.html */
    <style>
        p {
            font-size: 40px;
        }
        .p1 {
            text-shadow: 2px 2px;
        }
        .p2 {
            text-shadow: 2px 2px red;
        }
        .p3 {
            text-shadow: 2px 2px 5px red;
        }
        .p4 {
            text-shadow: 2px 2px 4px #000000;
        }
        .p5 {
            text-shadow: 0 0 3px #ff0000;
        }
        .p6 {
            text-shadow: 0 0 3px #ff0000, 0 0 5px #0000ff;
        }
        .p7 {
            text-shadow: 1px 1px 2px black, 0 0 25px blue, 0 0 5px red;
        }
    </style>
```

---
