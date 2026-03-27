# APEX University | Home Portal

A high-performance, responsive, and visually stunning university landing page designed with a focus on **Prestige, Intelligence, and Modernity**. This portal features a sophisticated "Blood Red" and "Obsidian" color palette, smooth parallax effects, and a production-ready UI.

---

## Key Features

* **Premium Aesthetic:** Uses a blend of `Playfair Display` for high-end serif typography and `Inter` for clean, SaaS-style readability.
* **Dynamic Hero Slider:** A full-viewport image slider with elegant fade transitions and a glassmorphism navigation bar.
* **Interactive UI Components:**
    * **Mega Menus:** Hover-activated dropdowns for Departments and About sections.
    * **News Grid:** Hover-animated cards with scale-up effects and status badges.
    * **Stats Parallax:** A fixed-background section highlighting university milestones (15k+ Alumni, 94% Placement).
* **Built-in Accessibility:** Integrated **Google Translate** element for global multi-language support.
* **Fully Responsive:** Mobile-first design using Tailwind CSS utility classes.
* **Scroll Animations:** Powered by **AOS (Animate On Scroll)** for a smooth, professional feel.

---

## Tech Stack

* **Styling:** [Tailwind CSS](https://tailwindcss.com/) (Post-modern utility framework)
* **Animations:** [AOS.js](https://michalsnik.github.io/aos/) & [Animate.css](https://animate.style/)
* **Typography:** Google Fonts (Playfair Display & Inter)
* **Icons:** Custom SVG-based iconography
* **Structure:** HTML5, CSS3, Vanilla JavaScript (ES6+)

---

## Quick Start

1.  **Clone the project:**
    ```bash
    git clone [https://github.com/your-username/apex-university.git](https://github.com/your-username/apex-university.git)
    ```
2.  **Add your Logo:**
    Replace the placeholder `logo.png` in the root directory with your institution's logo.
3.  **Launch:**
    Open `index.html` in any modern web browser. No build steps or local servers are required.

---

## Customization

### Brand Colors
To change the primary university color, update the CSS variable in the `<style>` block of `index.html`:
```css
:root {
    --blood-red: #8C0000; /* Update hex code here */
}
