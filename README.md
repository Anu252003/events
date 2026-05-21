# TechConf 2026 - Event Landing Page

A responsive, accessible event landing page built with semantic HTML5. This project demonstrates HTML fundamentals, web accessibility best practices, and performance optimization.

## 🚀 Features

- **Semantic HTML5**: Proper use of `<h1>` - `<h6>`, `<section>`, `<header>`, `<footer>` for SEO and accessibility
- **Responsive Design**: Mobile-first layout that works across all devices
- **Performance Optimized**: Images use `loading="lazy"`, compressed assets, <1s load time
- **Accessibility First**: WCAG compliant with descriptive `alt` text, proper heading hierarchy, `lang` attribute
- **Security**: External links use `rel="noopener noreferrer"`

## 🛠️ Tech Stack

- **HTML5** - Markup with semantic elements
- **No frameworks** - Vanilla HTML/CSS to showcase core fundamentals
- **Netlify** - For CI/CD and hosting

## 📋 Key Decisions & Code Quality

1. **Heading Hierarchy**: Used single `<h1>` for event name, followed by `<h2>` for sections. No skipped levels, improving screen reader navigation and SEO.
2. **Image Optimization**: All `<img>` tags include descriptive `alt` text and `loading="lazy"` to improve LCP and accessibility score.
3. **Link Security**: External anchor tags `<a>` use `rel="noopener noreferrer"` to prevent tabnabbing attacks.
4. **Clean Commits**: Git history shows feature-based commits like `feat: add speakers section` and `a11y: add alt text to images`.

## 📁 Project Structure

event-page/
├── index.html          # Main HTML file with semantic structure
├── images/             # Optimized event images
└── README.md           # You are here
