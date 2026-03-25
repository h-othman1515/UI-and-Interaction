# 🖱️ JavaScript Tasks — UI & Interaction

A collection of 5 interactive JavaScript exercises built with vanilla HTML, CSS, and JS.  
No frameworks, no libraries — just clean, beginner-friendly code.

---

## 📁 Project Structure

```
project/
├── index.html
└── assets/
    └── images/
        ├── jordan.png
        ├── usa.png
        ├── UK.png
        └── palestine.png
```

---

## ✅ Tasks

### 🟡 Task 1 — Hover Effect

| Event | Effect |
|-------|--------|
| Mouse enters | Background turns **yellow**, text becomes **bold** |
| Mouse leaves | Styles reset to default |

**Concepts used:** `mouseover`, `mouseout`, `element.style`

---

### 🌍 Task 2 — Country Dropdown & Flag

- Dropdown menu with a list of countries
- When a country is selected → its **flag image** and **name** are displayed
- Flag images are loaded from `assets/images/`

**Concepts used:** `addEventListener("change")`, `createElement`, `appendChild`, object lookup

---

### 👁️ Task 3 — Show / Hide Content

- Two separate content sections, each with its own **Show** and **Hide** buttons
- Clicking **Show** → reveals the content
- Clicking **Hide** → hides the content

**Concepts used:** `classList.add("hidden")`, `classList.remove("hidden")`

---

### ✍️ Task 4 — Mini Text Editor

- Type freely inside a content-editable box
- Toolbar options:

| Button / Dropdown | Action |
|-------------------|--------|
| **B** | Bold selected text |
| <u>U</u> | Underline selected text |
| Size dropdown | Change font size (Small → XLarge) |
| Font dropdown | Change font family |

**Concepts used:** `contenteditable`, `document.execCommand()`

---

### 🎨 Task 5 — Animated Color Box

- Box background cycles through colors automatically using CSS `@keyframes`
- A **speed slider** controls how fast the animation runs (1s → 10s)

**Concepts used:** CSS `animation`, `animationDuration`, `input` event on range slider

---
link: 
