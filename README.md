# Arslan Fayyaz — Parallax Portfolio

A modern, cinematic, responsive portfolio for a Full Stack MERN Developer. Built with plain HTML, CSS and JavaScript so it can be opened directly in a browser or deployed to Vercel/Netlify.

## Folder structure

```text
arslan-portfolio/
├── index.html          # ALL portfolio content + sections
├── README.md           # this guide
└── assets/
    ├── style.css       # design, responsive layout, animations
    ├── script.js       # scroll reveal, progress bar, mobile menu, parallax
    └── profile.jpg     # ADD YOUR REAL PHOTO HERE (optional)
```

## What to change

### 1. Name / title / intro
Open `index.html` and search for **Arslan Fayyaz**, **Full Stack MERN Developer**, and the intro paragraphs. Replace the text directly.

### 2. Your picture
Put your photo at:
`assets/profile.jpg`

Then, in `index.html`, replace the `.fake-photo` block with:
```html
<img src="assets/profile.jpg" alt="Arslan Fayyaz">
```
You can style it in `assets/style.css`.

### 3. Projects
Search for `NEXORA`, `VELORA`, and `FLOW`. Each project is an `<article class="project">` block. Change:
- Project name
- Description
- Year/category
- Technology chips
- Case-study/live link
- Project visual

### 4. Services
Search for `<div class="service-list">`. Each `<article class="service">` is one service. Duplicate/delete these cards whenever you want.

### 5. Reviews
Search for `<div class="review-grid">`. Replace the fake names, roles and review text with real testimonials.

### 6. AI Assistant
Search for `Launch AI Assistant`. Replace its `href="#"` with your AI assistant URL.

Example:
```html
<a class="btn primary" href="https://YOUR-AI-LINK.com">Launch AI Assistant ↗</a>
```

### 7. Social media
At the Contact section, search for `<div class="socials">`. Replace each `href="#"` with your actual URLs. Icons are text-based so the page has no external icon dependency.

### 8. Email / Contact form
Your displayed email is:
`arslanfayyaz1997@gmail.com`

The form currently uses **FormSubmit**:
```html
<form action="https://formsubmit.co/arslanfayyaz1997@gmail.com" ...>
```
On the first submission, FormSubmit normally asks you to confirm the receiving email address. After confirmation, submitted form data can be delivered to that Gmail inbox.

If you later move to your own backend, replace the `action` URL with your API endpoint. Never put Gmail passwords/API secrets inside frontend HTML.

### 9. Contact button
The hero `Contact me` link is already a `mailto:` link to your Gmail. Change the address in `index.html` if needed.

## Run locally

Simply double-click `index.html` and open it in Chrome. No build step is required.

## Deploy

You can upload the folder to Vercel, Netlify, GitHub Pages, or any static hosting service. There is no Node/npm requirement for this version.

## Design notes

- Scroll reveal animations
- Scroll progress bar
- Layered hero parallax
- Responsive mobile navigation
- Responsive project/service/review grids
- Mobile-friendly contact form
- Reduced visual complexity on small screens to avoid lag/hanging
- No heavy animation libraries, keeping the site lightweight
