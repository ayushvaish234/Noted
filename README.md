# 📝 Noted

A clean, lightweight web application for reading and sharing short-form notes and essays. Built with plain HTML, CSS.
 
🌐 **Live Demo:** [ayushvaish234.github.io/Noted](https://ayushvaish234.github.io/Noted/)
 
---

## 📌 Overview

**Noted** is a simple note-sharing platform where users can browse articles written by others, log in to their account, sign up, or get in touch via a contact page. The project is entirely static — no frameworks, no build tools, just HTML and CSS.

---

## 📁 Project Structure

```
noted/
├── index.html          # Home page — displays all notes/articles
├── login.html          # Login page
├── signup.html         # Sign up / registration page
├── contact.html        # Contact page
├── styles.css          # Global stylesheet shared across all pages
└── README.md           # You're reading it
```

---

## 🗂️ Pages

### `index.html` — Home / All Notes
The main landing page. Displays a feed of all published notes in reverse-chronological order. Each note card shows:
- Article title
- Author name and date
- A short excerpt/body

Navigation links to the Notes feed and Contact page. Auth links (Login) are in the header.

---

### `login.html` — Login
Allows existing users to log in to their account.

---

### `signup.html` — Sign Up
Registration page for new users to create an account.

---

### `contact.html` — Contact
A contact form or information page for users to reach out.

---

### `styles.css` — Global Styles
A single stylesheet used across all pages for consistent typography, layout, colors, and component styling (header, nav, articles, footer, forms).

---

## 🚀 Getting Started

No installation or build step needed. Just open the project in a browser:

```bash
# Clone or download the project
git clone https://github.com/your-username/noted.git

# Open the home page directly
open index.html
```

Or simply double-click `index.html` in your file explorer.

---

## 🔧 Customization

- **Add a new note:** Copy an `<article>` block in `index.html` and update the title, author, date, and body text.
- **Change colors or fonts:** Edit the relevant properties in `styles.css`.
- **Add new pages:** Create a new `.html` file and link it in the `<nav>` inside `<header>`.

---

## 📋 HTML Notes

- All pages share the same `<header>` structure (logo, nav, auth links) for consistency.
- Article body text uses `id="article"` — note that IDs should be unique per page; consider switching these to `class="article"` if you have multiple articles per page.
- The footer displays copyright: `2026@Noted`.

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Page structure and content |
| CSS3 | Styling and layout (via `styles.css`) |
| No JavaScript | Fully static, no JS dependencies |

---
 
---

## 📄 License

© 2026 Noted. All rights reserved.
