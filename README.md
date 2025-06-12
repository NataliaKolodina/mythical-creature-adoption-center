# 🐉 Mythical Creature Adoption Center

Welcome to the **Mythical Creature Adoption Center** — a semantic, accessible, and media-rich single-page website built with HTML5 and CSS3. This project showcases the adoption process of magical creatures like dragons, unicorns, phoenixes, and griffins through a fully-structured and interactive web interface.

---

## 🌐 Live Demo

🔗 [Visit the Live Site](https://NataliaKolodina.github.io/mythical-creature-adoption-center)  


---

## 📌 Project Overview

This is a final project developed as part of a front-end development course. It demonstrates the practical application of HTML5 semantics, multimedia integration, form handling, accessibility best practices, and structured content layout — without any use of JavaScript or external frameworks.

---

## 🛠️ Technologies Used

- **HTML5** – Semantic structure, form elements, multimedia embedding
- **CSS3** *(optional in extended version)* – Styling and layout (not part of this task but can be added)
- **Git & GitHub** – Version control and deployment

---

## 📂 Project Structure

```text
mythical-creature-adoption-center/
├── index.html               # Main HTML file
├── submit_adoption.html    # Form submission landing page (placeholder)
├── assets/
│   ├── images/              # All images (magical landscape, creatures, etc.)
│   ├── audio/               # Welcome music or sound
│   └── video/               # Magical journey clip
└── README.md                # Project documentation ```

## 📄 Features Implemented

### ✅ Semantic HTML Layout
- `<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`
- Semantic tags: `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`

### ✅ Navigation
- Internal anchor links: `#home`, `#adopt`, `#creatures`, `#faq`
- External link: Encyclopedia of Mythical Creatures (opens in a new tab)

### ✅ Home Section
- Magical landscape image with descriptive `alt`
- `<figcaption>` under image: “Welcome to your next adventure!”
- Embedded `<audio>` element with controls
- Intro paragraph featuring:
  - `<span>` for "once-in-a-lifetime"
  - `<strong>` for "magical companions"
  - `<em>` for "extraordinary journey"
  - `<br>` tags for line breaks

### ✅ Adoption Form
- Form with `POST` method to `submit_adoption.html`
- Fields:
  - Text (Full Name)
  - Email
  - Age (Number)
  - Password
  - Select dropdown (creature choice)
  - Datalist for pickup locations
  - Range slider for "Magic Compatibility Level"
  - Checkboxes (Magical Skills)
  - Radio buttons (Adoption Speed)
  - Textarea (Motivation)
  - Submit button
- `<label>` elements correctly associated with inputs
- Accessibility-first markup

### ✅ Creatures Table
- Full table with `<thead>`, `<tbody>`, `<tfoot>`
- Use of `scope="col"` and `scope="row"` for accessibility
- Table footer with `colspan` to summarize total creatures

### ✅ FAQ Section
- Unordered list of common questions
- Bolded "Q:" and "A:"
- Emphasis tags for important words (`<strong>`, `<em>`)
- Link inside FAQ that jumps to the “Adopt” section

### ✅ Multimedia
- Embedded `<video>` clip with caption: “Discover the world of mythical creatures!”
- One image wrapped in a link (`<a><img></a>`) to open the Dragon encyclopedia page in a new tab

### ✅ HTML Comments
- Includes at least one descriptive HTML comment (e.g., `<!-- Adoption Form Section -->`)

---

## ♿ Accessibility & Best Practices

- All images include descriptive `alt` attributes
- Proper use of `label` elements
- Accessible forms, inputs, and navigation
- Logical document structure for screen readers
- Valid HTML5 syntax and proper indentation

---

## 🚀 How to Run Locally

1. Clone the repo:

```bash
git clone https://github.com/yourusername/mythical-creature-adoption-center.git
cd mythical-creature-adoption-center
```

2. Open `index.html` in any browser, or use **Live Server** in VS Code.

---

## 🔮 Future Enhancements 

- CSS styling for layout and theme  
- Responsive design with media queries  
- JavaScript interactivity (form validation, animations)  
- Creature database integration with JSON or external API  

---

## 📜 License

This project is open-source and available under the **MIT License**.

---

## 👩‍💻 Author

**Nataliia Kolodina**  
Junior Front-End Developer  
🌍 Sassari, Italy  
📧 nataliiakolodina89@gmail.com

