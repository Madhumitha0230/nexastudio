# 🌟 NexaStudio
### Task 3 — Advanced CSS Styling & Responsive Design

> A fully responsive, production-grade webpage built with advanced CSS techniques,
> Bootstrap 5, and Vanilla JavaScript. Everything lives in a single HTML file —
> no server, no installation, just open and run.

---

## 📸 Sections Overview

| # | Section | What it Shows |
|---|---------|---------------|
| 1 | **Navbar** | Sticky glassmorphism nav, hamburger menu on mobile |
| 2 | **Hero** | Full-viewport dark hero with animations & floating card |
| 3 | **Marquee** | Infinite scrolling CSS ticker strip |
| 4 | **About** | Split layout with image frame and signature |
| 5 | **Services** | 6-card CSS techniques grid |
| 6 | **Skills** | Animated progress bars (scroll-triggered) |
| 7 | **Portfolio** | 5 cards with real CSS-drawn UI mockups |
| 8 | **Testimonials** | 3-column review cards |
| 9 | **CTA Banner** | Gold call-to-action with background text |
| 10 | **Contact** | Working form with validation + toast notification |
| 11 | **Footer** | Links + copyright |

---

## 🚀 How to Run

```
1. Download  nexastudio-final.html
2. Double-click the file
3. It opens in your browser — done!
```

> No Node.js · No terminal · No installation · Just one file

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **HTML5** | Semantic page structure |
| **CSS3** | All custom styling & animations |
| **Bootstrap 5** | Responsive grid & navbar |
| **Vanilla JavaScript** | Interactions, form validation, modal |
| **Google Fonts** | Cormorant Garamond · DM Sans · Bebas Neue |

---

## 🎨 Advanced CSS Techniques Used

```css
/* 1. CSS Custom Properties */
:root {
  --gold: #c9a96e;
  --cream: #faf8f3;
}

/* 2. Keyframe Animations */
@keyframes fadeUp {
  from { opacity: 0; transform: translateY(35px); }
  to   { opacity: 1; transform: translateY(0); }
}

/* 3. Cubic-Bezier Transitions */
transition: transform 0.45s cubic-bezier(0.76, 0, 0.24, 1);

/* 4. Fluid Typography with clamp() */
font-size: clamp(2.8rem, 10vw, 8rem);

/* 5. CSS Grid — asymmetric layout */
grid-template-columns: repeat(12, 1fr);

/* 6. Backdrop Filter — glassmorphism */
backdrop-filter: blur(20px);

/* 7. Mobile-first Media Queries */
@media (min-width: 576px) { ... }
@media (min-width: 992px) { ... }
```

---

## 📱 Responsive Breakpoints

| Breakpoint | Screen Size | Layout Changes |
|-----------|-------------|----------------|
| `xs` | 0 – 575px | 1 column, mobile hero pills, stacked form |
| `sm` | 576 – 767px | 2 column cards, side toast, row form |
| `md` | 768 – 991px | 3 column testimonials, tablet nav |
| `lg` | 992px+ | Full desktop layout, hero card visible |

### Test Responsiveness
```
Press F12 in browser
→ Click the 📱 device icon  (Ctrl + Shift + M)
→ Test these sizes:
   • iPhone SE    — 375px
   • iPhone 14    — 390px
   • iPad Mini    — 768px
   • Laptop       — 1280px
```

---

## ✨ JavaScript Features

```javascript
// 1. Custom Gold Cursor (desktop only)
//    → Dot follows instantly, ring lags smoothly

// 2. Scroll Reveal — IntersectionObserver
//    → Elements fade up / slide in from left or right

// 3. Animated Skill Bars
//    → Width transitions when scrolled into view

// 4. Navbar Shrink on Scroll
//    → Padding reduces after 60px scroll

// 5. Contact Form Validation
//    → Checks name, email format, subject, message length
//    → Shows red errors inline, clears on typing

// 6. Toast Notification System
//    → Slides up from bottom (mobile) or right (desktop)

// 7. Project Modal
//    → Bottom sheet on mobile, centered dialog on desktop
//    → Closes on backdrop click or Escape key
```

---

## 📂 File Structure

```
nexastudio-final.html      ← Everything in one file
│
├── <style>                ← All CSS (700+ lines)
│   ├── CSS Variables
│   ├── Reset & Base
│   ├── Cursor
│   ├── Navbar
│   ├── Hero
│   ├── Marquee
│   ├── Section Helpers
│   ├── About
│   ├── Services
│   ├── Skills
│   ├── Portfolio
│   ├── Testimonials
│   ├── CTA Banner
│   ├── Contact
│   ├── Toast
│   ├── Modal
│   ├── Footer
│   └── Scroll Reveal
│
├── <body>                 ← All HTML
│   ├── Navbar
│   ├── Hero
│   ├── Marquee
│   ├── About
│   ├── Services
│   ├── Skills
│   ├── Portfolio (5 cards with CSS mockups)
│   ├── Testimonials
│   ├── CTA Banner
│   ├── Contact Form
│   ├── Footer
│   ├── Toast Container
│   └── Project Modal
│
└── <script>               ← All JavaScript
    ├── Custom Cursor
    ├── Scroll Reveal
    ├── Skill Bars
    ├── Navbar Shrink
    ├── Toast System
    ├── Contact Form
    └── Modal
```

---

## 🎯 Task 3 Objectives — Completed

- [x] **Complex multi-section layout** — 11 distinct sections
- [x] **CSS transitions** — cubic-bezier on every hover state
- [x] **CSS animations** — shimmer, marquee, fadeUp, spinSlow, scrollPulse, barGrow
- [x] **CSS framework** — Bootstrap 5 grid throughout
- [x] **Responsive design** — tested from 320px to 1440px
- [x] **CSS variables** — full design token system on `:root`
- [x] **Advanced selectors** — `::before`, `::after`, `:hover`, `:first-child`
- [x] **Mobile-first** — all layouts built small-screen first

---

## 👨‍💻 Author

**NexaStudio**
Tamil Nadu, India
Instagram: [@nexastudio.in](https://instagram.com/nexastudio.in)

---

*© 2026 NexaStudio · Task 3: Advanced CSS Styling & Responsive Design*
