# HTML Tags Demo Project

A practice project showcasing various **HTML tags** including text formatting, structural elements, forms, tables, lists, popovers, images, and input enhancements.  
This file is designed as a quick reference for learning and experimenting with HTML.

---

## ✨ Features

### 1. Logical Text Formatting
Semantic tags that add meaning to text:
- `<strong>` → Bold (importance)  
- `<em>` → Italics (emphasis)  
- `<abbr>` → Abbreviation with tooltip  
- `<cite>` → Citation (book, film, etc.)  
- `<code>` → Inline code snippet  
- `<kbd>` → Keyboard input (`Ctrl + S`)  
- `<var>` → Variable in math/science  
- `<mark>` → Highlighted text  
- `<strike>` → Strikethrough (**deprecated**, use `<s>`)  
- `<tt>` → Old teletype text (**deprecated**)  
- `<blockquote>` → Long quotations  
- `<q>` → Short inline quotes  
- `<dfn>` → Marks a term being defined  

---

### 2. Structural Tags
- `<article>` → Independent content block  
- `<aside>` → Sidebar / extra info  
- `<div>` → Generic container with styles  

---

### 3. Inputs & Forms
- `<input type="text" enterkeyhint="send">` → Shows "Send" on mobile keyboard  
- `<input type="text" inputmode="numeric">` → Opens numeric keypad (PIN/OTP)  
- `<form>` → Collects user input with `textarea`, `select`, and `button`  
- `<select multiple size="3">` → Dropdown with multiple selection  

---

### 4. Tabindex
```html```
<a tabindex="1">Google</a>
<a tabindex="3">Instagram</a>
<div tabindex="2">Microsoft</div>

---

### 5. Table with Rowspan & Colspan
- `<caption>` → Table title  
- `<colgroup>` → Style columns  
- `<thead>` → Header row  
- `<tbody>` → Main data  
- `<tfoot>` → Summary/totals  
- `rowspan` → Cell spans multiple rows  
- `colspan` → Cell spans multiple columns  

---

### 6. Lists
- `<ul type="square">` → Unordered list with square bullets  
- Nested `<ul type="circle">` → Circle bullets  
- `<ol type="A" reversed>` → Reverse ordered list with letters  

---

### 7. Popover
```html```
<div popover id="mydiv"> ... </div>
<button popovertarget="mydiv">Click me!</button>


### 8. Images
- `<img src="..." loading="eager" alt="Lazy cat">`  
  - `loading="eager"` → loads image immediately  
  - `alt` → fallback text if image fails  

  ### 9. Miscellaneous

  - `<hr>` → horizontal rule for separation  
  - `<h2>`, `<h3>` → subheadings  
  - Inline styles in `<div>` (example: black background, white text)  

---

## 🛠️ Tech Stack
- **HTML** – Page structure and elements  
- **CSS** – Basic styling (optional)  

---

## 🚀 How It Works
1. Open `index.html` in your browser or run it with **Live Server** / **GitHub Pages**.  
2. Explore different examples of HTML tags (text, tables, popovers, images, lists, etc.).  
3. Modify the file to experiment and understand how each tag behaves.  

> ✅ Perfect for **beginners learning front-end development**.
