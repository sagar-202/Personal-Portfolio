# Storytelling Setup: Personal Portfolio

A clean, modern, and highly interactive personal portfolio built entirely with vanilla HTML, CSS, and precise Vanilla JavaScript. 

This project departs from traditional vertical scrolling architectures by implementing a highly tactile, narrative-driven **Sticky Stacking Deck** UI layout that responds naturally to the user.

## ✨ Core Features

*   **Sticky Stacking Scroll Mechanics**: Sections intelligently stick to the viewport and stack continuously above one another as you traverse vertically, delivering the sensation of assembling physical glass cards.
*   **Deep Dark Mode Aesthetics**: Fully embraces a dark slate color palette (`#020617`) with refined contrast for readability and reduced eye strain.
*   **Premium Glassmorphism**: Cards feature robust blurred semi-transparent backgrounds with extremely subtle highlighting borders and ambient electric blue shadows to foster depth.
*   **Responsive Degradation**: Automatically unwraps the strict `100vh` sticky behaviors on touch devices (<1024px) down to an elegant, standard vertical column flow ensuring perfect touch usability.
*   **Strictly Vanilla**: Powered absolutely by native browser capabilities without React, Tailwind, or complex build engines. Feather Icons manages the lightweight SVG iconography.

## 🚀 Setup & Execution

Since the project compiles naturally inside any web-browser without an overt build mechanism, running is fundamentally trivial:

1. Clone the repository down to your local machine:
   ```bash
   git clone git@github.com:sagar-202/Personal-Portfolio.git
   ```
2. Open the directory and launch `index.html` either natively through your web browser or utilizing a hot-reloading tool like **VSCode Live Server**.

## 🎨 Modifying Structure

To scale out other pages or modify content:
- **`index.html`**: Contains the global structural wrapper (`<main class="story-container">`) encapsulating multiple nested `<div class="stack-card">` nodes that compose the timeline pieces.
- **`styles.css`**: CSS variables govern spacing (`--space-lg`), foundational theming, typography (`var(--font-primary)`) and card elevation shadows.

## ☁️ Deployment

Setup inherently optimized for automatic CI/CD deployment onto Vercel. Link the GitHub repository identically into the Vercel Dashboard and it'll mount the static artifacts live without extra build configurations.
