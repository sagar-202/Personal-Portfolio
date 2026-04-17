<div align="center">
  <h1>🌌 Storytelling Setup: Personal Portfolio</h1>
  <p>A clean, modern, and highly interactive personal portfolio built entirely with Vanilla HTML, CSS, and JavaScript.</p>

  <!-- Badges -->
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />

  <br />
  <br />
</div>

## 📖 Overview

This project departs from traditional vertical scrolling architectures by implementing a highly tactile, narrative-driven **Sticky Stacking Deck** UI layout that responds naturally to the user. It serves as a premium, production-ready portfolio template for designers and developers to showcase their work innovatively.

> **Note:** This project is built without React, Tailwind, or complex build engines—demonstrating the absolute power of modern native browser capabilities.

---

## ✨ Key Features

| Feature | Description |
| :--- | :--- |
| **Sticky Stacking Mechanics** | Sections intelligently stick to the viewport and stack continuously above one another as you traverse vertically, delivering the sensation of assembling physical glass cards. |
| **Deep Dark Mode Themes** | Fully embraces a dark slate color palette (`#020617`) paired with refined contrast mapping to promote readability and reduce eye strain. |
| **Premium Glassmorphism** | Cards feature robust blurred semi-transparent backgrounds with incredibly subtle highlighting borders and ambient electric blue shadows to foster depth. |
| **Responsive Degradation** | Automatically detects touch devices (`<1024px`) and unwraps the strict `100vh` sticky behaviors, smoothly transitioning down to an elegant, standard vertical column flow ensuring perfect touch usability. |
| **Native Performance** | Powered strictly by native DOM interactions, CSS Variables, and CSS Grids. Feather Icons manages the lightweight SVG iconography natively. |

---

## 🛠️ Technology Stack

- **Markup Elements:** Semantic HTML5
- **Styling Architecture:** Vanilla CSS3 (Variables, Grid, Flexbox, Media Queries, Hardware Acceleration)
- **Interactive Logic:** Vanilla JavaScript (IntersectionObserver, DOM Manipulation)
- **Iconography:** Feather Icons (via CDN)

---

## 🚀 Setup & Installation

Since the project compiles naturally inside any web browser without an overt build mechanism, running is fundamentally trivial:

1. **Clone the repository:**
   ```bash
   git clone git@github.com:sagar-202/Personal-Portfolio.git
   ```

2. **Navigate into the directory:**
   ```bash
   cd Personal-Portfolio
   ```

3. **Launch the Application:**
   Open `index.html` natively through your web browser or utilize a live-reloading server like **[VSCode Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)** for automatic updates while editing.

---

## 📐 Architecture & Customization

To scale out other pages or modify the existing content:

- **`index.html`**  
  Contains the global structural wrapper (`<main class="story-container">`) encapsulating multiple nested `<div class="stack-card">` nodes that compose the timeline pieces. Easily copy/paste an existing `stack-card` to append new chapters.

- **`styles.css`**  
  CSS heavily utilizes variables for maintainability. Simply adjust root tokens to instantly theme the portfolio:
  - Base Spacing: `--space-lg`, `--space-xl`
  - Color Tokens: `--clr-primary`, `--clr-bg`, `--clr-surface`
  - Typography: `var(--font-primary)`
  - Card Elevations: `var(--shadow-heavy)`

---

## ☁️ Deployment

This architecture is inherently optimized for zero-configuration, automatic CI/CD deployment onto modern hosting providers.

**Vercel Deployment:**
1. Connect your GitHub repository matching this codebase into the Vercel Dashboard.
2. Ensure you import it as an "Other" framework configuration.
3. Vercel will mount and serve the static `index.html` edge artifacts live instantly, without requiring any supplemental build commands.

---

<div align="center">
  <p>Built with ❤️ using clean code & smooth scrolls.</p>
</div>
