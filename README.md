# 🏎️ Team Swarajya Racing - M-BAJA ATV Website

![Project Status](https://img.shields.io/badge/Status-Complete-success)
![License](https://img.shields.io/badge/License-MIT-blue)

A premium, single-page responsive website designed for the M-BAJA SAE India ATV team. Built with modern HTML5, CSS3, and Vanilla JavaScript, this project features a high-performance design with Glassmorphism UI, parallax scrolling, and dark mode support.

## ✨ Features

-   **🎨 Modern Design**:
    -   **Glassmorphism**: Frosted glass effects on cards and navigation.
    -   **Parallax Hero**: Cinematic "Ken Burns" zoom effect and scrolling parallax.
    -   **SVG Dividers**: Organic "wave" shapes separating sections.
    -   **Typography**: Integrated Google Fonts (Montserrat & Open Sans).
-   **📱 Fully Responsive**:
    -   Mobile-first architecture.
    -   Collapsible hamburger menu for mobile devices.
-   **🌙 Dark Mode**:
    -   One-click toggle between Light and Dark themes.
    -   Auto-detects system preference.
    -   Persistent preference using LocalStorage.
-   **⚡ Performance**:
    -   Zero external frameworks (No Bootstrap/Tailwind).
    -   Lightweight Vanilla JS interactions.
    -   Intersection Observer for scroll-triggered animations.

## 🚀 Getting Started

No installation or server is required! This is a **static website**.

### Method 1: Direct Open
1.  Navigate to the folder containing `index.html`.
2.  Double-click `index.html` to open it in your default web browser.

### Method 2: VS Code Live Server (Recommended)
1.  Open the project folder in **VS Code**.
2.  Install the **Live Server** extension.
3.  Right-click `index.html` and select **"Open with Live Server"**.
    *   *This will auto-reload the page whenever you save changes.*

## 🛠️ Customization Guide

This website is designed to be easily editable. Open `index.html` in any code editor to make changes.

### 1. Changing Colors (Theming)
Locate the `:root` section in the `<style>` tag (approx line 20). Change the HEX codes to match your college colors.

```css
:root {
    --primary-color: #ff3b3f;      /* CHANGE THIS to your main color */
    --accent-color: #00d4ff;       /* CHANGE THIS to your secondary color */
}
```

### 2. Updating Images
The website currently uses placeholders (`https://placehold.co/...`). To use your own images:

1.  Create an `assets/` or `images/` folder.
2.  Place your photos there (e.g., `team-photo.jpg`).
3.  Update the `src` or `background-image` paths in the HTML/CSS.

**Example (HTML):**
```html
<!-- BEFORE -->
<img src="https://placehold.co/600x400" alt="Gallery">

<!-- AFTER -->
<img src="images/race-day-1.jpg" alt="Race Day">
```

**Example (CSS):**
```css
/* BEFORE */
background-image: url('https://placehold.co/1920x1080...');

/* AFTER */
background-image: url('images/hero-bg.jpg');
```

### 3. Modifying Content
*   **Team Members**: Search for `<!-- Team Section -->` and duplicate the `.member-card` divs for each new member.
*   **Specs**: Search for `<!-- Vehicle Section -->` and edit the `<dd>` tags in the specifications list.
*   **Links**: Update the `href="#"` attributes in the Footer with your real social media links.

## 🌐 Deployment

### GitHub Pages (Free Hosting)
1.  Upload this folder to a new GitHub repository.
2.  Go to **Settings** > **Pages**.
3.  Under **Source**, select `main` branch.
4.  Click **Save**. Your site will be live at `https://yourusername.github.io/repo-name`.

## 📂 Project Structure

```
├── index.html        # The entire source code (HTML + CSS + JS)
└── README.md         # This documentation file
```

## 🤝 Contributing
Feel free to fork this project and submit pull requests for new features or bug fixes.

---
*Designed for Team Swarajya Racing.*
