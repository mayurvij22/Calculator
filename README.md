<div align="center">

# 🧮 Calculator

**A clean, responsive calculator built with plain HTML, CSS and JavaScript.**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Vercel](https://img.shields.io/badge/deployed%20on-Vercel-000000?logo=vercel&logoColor=white)

### [🌐 Live demo](https://calculator-xi-hazel.vercel.app)

</div>

---

## ✨ Features

- Basic arithmetic: `+`, `−`, `×`, `÷` and `%` (remainder/modulo)
- **AC** clears the whole expression and **DEL** removes the last character
- Decimal point and a `00` key for quick entry
- The expression builds up live in the display and is evaluated on **=**
- No frameworks or build step: open the page and it works

## 🛠️ Tech stack

| Layer | Technology |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 |
| Logic | Vanilla JavaScript (DOM events) |
| Hosting | Vercel |

## 🚀 Run locally

```bash
git clone https://github.com/mayurvij22/Calculator.git
cd Calculator
# open index.html in your browser
```

## 📁 Project structure

```text
├── index.html   # Calculator layout (display and button grid)
├── style.css    # Styling
└── index.js     # Click handling and expression evaluation
```

## 🧠 How it works

Every button click appends its label to an expression string shown in the display.
Pressing **=** evaluates the expression with JavaScript's `eval`, **AC** resets it and **DEL** trims the last character.

> [!NOTE]
> `eval` keeps the code short for a learning project. A production calculator would use a proper expression parser instead.

---

<div align="center">

Made by **[Mayur Patil](https://github.com/mayurvij22)**

</div>
