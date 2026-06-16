# 🍔 Tappy Food — Premium Street Food Delivery 🍟

Welcome to **Tappy Food**, a vibrant, interactive, and highly responsive single-page web application designed to bring the atmosphere and flavors of local night markets right to your screen. This project combines premium street-food aesthetics with a modern, fast, and completely client-side interactive experience.

---

## 🎨 Theme & Mood

The visual theme is inspired by **Retro Neo-Brutalism mixed with Cozy Night Market vibes**. Unlike standard, sterile modern apps, Tappy Food feels organic, warm, and tactile.

*   **Atmosphere:** Warm, friendly, delicious, street-smart, and active.
*   **Vibe:** Flat design elements, thick strokes, paper-like card shadows, and cozy lighting.
*   **Target Audience:** Foodies and night-market fans looking for local gourmet treasures.

---

## 🍱 Design Language & UI Spec

The design language uses distinct Neo-Brutalist elements to make buttons and cards feel clickable and physical:

### 1. Typography ✍️
*   **Display & Headings:** `Bowlby One` (Cursive, Bold, Retro, Fun) — Used for titles, logos, and accent headings.
*   **Body & UI Text:** `DM Sans` (Clean, Modern, Geometric Sans-Serif) — Used for card text, navigation list, badges, and forms.

### 2. Color Palette 🎨
| Color | Variable | Hex Code | Purpose |
| :--- | :--- | :--- | :--- |
| **Rich Charcoal** | `--primary` | `#1A0F05` | Bold headlines, core text, and thick container borders |
| **Earth Brown** | `--secondary` | `#7A6A54` | Muted borders, captions, and secondary metadata |
| **Fiery Red** | `--tertiary` | `#F23C3C` | Accent/Highlights, call-to-actions, and interactive alerts |
| **Warm Cream** | `--neutral` | `#F5E9CF` | Main background, clean paper feel |
| **Soft Butter** | `--surface` | `#FCF3DC` | Cards, sidebars, and navigation headers |

### 3. Tactile Neo-Brutalist Styles 📐
*   **Borders:** Container cards and buttons have a solid `3px solid var(--primary)` border.
*   **Drop Shadows:** Instead of soft blurs, components feature hard offset shadows: `box-shadow: 6px 6px 0px 0px var(--secondary)` or `8px 8px 0px 0px var(--primary)`.
*   **Micro-interactions:** When hovered, elements translate upwards (`transform: translate(-4px, -4px)`) while their drop shadows expand, providing an authentic physical button-press click feel.

---

## ⚡ Core Features

*   🔍 **Interactive Cuisine Filter:** Filter both restaurants and best-selling dishes in real-time by Italian, Burgers, Japanese, Mexican, Indian, Healthy, and Dessert cuisines.
*   🛒 **Interactive Slide-Out Shopping Cart:**
    *   Smooth drawer animation sliding in from the right overlaying the screen.
    *   Increment or decrement quantities directly within the cart drawer.
    *   Real-time subtotal and total billing logic.
    *   Auto-updating cart notification badge in the header.
*   🏆 **Spotlight Feature:** A beautiful monthly spotlight card featuring top partners (e.g., "The Golden Olive").
*   🏷️ **Smart Badges:** Visual tags indicating custom criteria like `🌶️ Spicy`, `🌱 Vegan`, `⭐ Bestseller`, and estimated delivery times.
*   📬 **Customer Inquiry Form:** A sleek inquiry form with floating focus borders and validation.

---

## 🛠️ Technology Stack

*   **Structure:** HTML5 Semantic Layout
*   **Styling:** Vanilla CSS3 (Custom properties, CSS Grid, Flexbox, transitions)
*   **Logic:** Modern Vanilla JavaScript (ES6+ array utilities, DOM events, state management)
*   **Fonts:** Google Fonts Integration (Bowlby One & DM Sans)
*   **Icons:** Web-safe Emojis (no heavy external SVG/Font libraries)

---

## 📂 Project Structure

```
frontendprograms/
├── index.html       # Main application page (Markup, Javascript Logic & State)
├── styles.css       # Design System Variables & Styling rules
├── same.html        # Main page backup copy
├── day5/            # Practice exercises directory
└── css selectors/   # CSS Selector exercises directory
```

---

## 🚀 Getting Started

No database setup or package installation is required! Follow these steps to run the application:

1.  Clone or download the project directory.
2.  Navigate to the root directory.
3.  Double-click [index.html](file:///c:/Users/User/frontendprograms/index.html) to open it directly in any modern web browser, or serve it locally using:
    ```bash
    # If you have python installed
    python -m http.server 8000
    
    # Or if you have Node/npx
    npx serve .
    ```
4.  Open `http://localhost:8000` (or the port specified by your tool) in your web browser.

Enjoy tapping your street food! 🍽️
