# 🕵️ Confidential Email Page — Web Layout & CSS Styling

A responsive, themed confidential email web page built using semantic **HTML5** and **CSS3**. This project demonstrates core front-end styling techniques, including custom layout sizing, box-sizing models, rotated inline-block stamps, and CSS blur filters for sensitive text redaction.

---

## 📌 Overview

The **Confidential Email Page** presents a styled, classified document interface designed to look like a redacted intelligence briefing. 

It features:
- A structured `#email` main container with precise dimensions and border-box sizing.
- Rotated "CONFIDENTIAL" and "TOP SECRET" visual badge stamps.
- Redacted paragraph content using programmatic CSS `blur()` filters.

---

## ✨ Key Features

- **Exact Box-Model Control**: Built with `box-sizing: border-box` to ensure strict dimensional alignment across browsers.
- **Visual Stamps**: Custom `div` elements styled with borders, padding, and CSS `transform: rotate()` to mimic authentic classified documentation.
- **Redacted Information**: Dynamic `.blurred` span elements styled with CSS `filter: blur(3px)` to conceal sensitive operational details.
- **Clean Semantic HTML**: Follows standard HTML structural guidelines using standard elements (`<main>`, `<div>`, `<p>`, `<span>`).

---

## 🛠️ Built With

* **HTML5**: Semantic web structure.
* **CSS3**: Layout design, box-model configuration, CSS transforms, and visual filters.

---

## 📁 Project Structure

```text
confidential-email/
├── index.html     # HTML structure and redacted document text
├── styles.css     # CSS styling, transforms, and blur filters
└── README.md      # Project documentation
