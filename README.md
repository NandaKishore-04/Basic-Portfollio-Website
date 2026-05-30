# Basic Portfolio Website

A fully responsive personal portfolio website built with **HTML** and **CSS** (plus minimal vanilla JavaScript for interactivity). Designed to showcase projects, work experience, skills, and social/contact links — with a focus on clean UX, accessibility, and mobile-first responsiveness.

---

## 🗂️ File Structure

```
task2-portfolio-website/
├── index.html    # Page structure and content
└── style.css     # All styles, layout, and responsive rules
```

The HTML and CSS are kept in **separate files** as required, linked via a standard `<link>` tag in the `<head>`.

---

## ✅ Features

### Layout & Navigation
- **Fixed sticky navbar** with logo, navigation links, and CTA button
- **Mobile hamburger menu** that toggles the nav on small screens
- **Smooth scroll** navigation between all sections
- **Back-to-top button** that appears after scrolling 400px


### UX Enhancements
- Project filter tabs that show/hide cards by category
- Contact form with client-side validation and a success notification
- Skill bars animate into view when the section scrolls into the viewport (IntersectionObserver)
- Hover micro-interactions on cards, buttons, social icons, and nav links

---

## 🧰 Technologies Used

| Technology | Purpose |
|------------|---------|
| HTML5 | Semantic page structure |
| CSS3 | Grid, Flexbox, custom properties, animations |
| Vanilla JavaScript | Nav toggle, scroll events, filter tabs, form submit |
| Google Fonts | Playfair Display + Outfit typography |
| Phosphor Icons (CDN) | All icons via `<i class="ph ph-...">` |


---

## 📚 What I Learned

- Structuring a multi-section portfolio with semantic HTML
- Building responsive layouts with CSS Grid and Flexbox
- Using CSS custom properties for a consistent design system
- Creating a responsive navbar with a JavaScript-powered mobile toggle
- Implementing smooth UX patterns: scroll events, form feedback, animated skill bars
- Using icon libraries (Phosphor Icons) via CDN
- Writing clean, well-commented, maintainable CSS across a large stylesheet

