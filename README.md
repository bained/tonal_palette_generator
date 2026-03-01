# 🎨 Interactive Color & Design System

## 🚀 Overview
This application is a functional web tool designed with a focus on professional UI/UX principles. It leverages a structured color system and dynamic JavaScript to provide a seamless user experience.

## 🧠 Design Logic (How it Works)
The application follows a rigorous design system based on **HSL (Hue, Saturation, Lightness)** to ensure visual harmony and accessibility.

### 1. The Core Palette (100 - 500)
The project uses a primary 5-color scale for consistent UI elements:
* **100 (Lightest):** Used for Section Backgrounds or Disabled states.
* **200 (Soft):** Perfect for Card Backgrounds, Dividers, or Secondary Buttons.
* **300 (Base):** The **Primary Brand Color** for Main Actions and Active Links.
* **400 (Deep):** Applied to Hover States and Subheadings.
* **500 (Darkest):** High contrast for Main Text and Dark Mode accents.

### 2. Tints & Shades (XX1 - XX9)
For complex UI components like tooltips or layered cards, we use "micro-adjustments":
* **Tints (XX1):** (+15% Lightness) Ideal for Success/Info notifications.
* **Shades (XX9):** (-15% Lightness) Used for Inner Shadows and Pressed button states.

### 3. Why HSL?
Unlike HEX, HSL maintains the "energy" of a color. We apply an **8° Hue Shift** when darkening colors to prevent them from looking "muddy" or "greyish," mimicking how natural shadows work in the real world.

## ✨ Features
* **Responsive Design:** Fully optimized for all screen sizes.
* **Design-to-Code Sync:** Supports `.gpl` export for tools like Inkscape or GIMP.
* **Dynamic UI:** Real-time interactivity powered by Vanilla JavaScript.

## 🛠️ Tech Stack
* **HTML5 & CSS3:** Semantic structure and custom layouts.
* **JavaScript (ES6+):** Core logic and HSL color calculations.

## 🌐 Live Demo
You can view the live version of the application here:  
👉 [**View Live Site**](https://bained.github.io/tonal_palette_generator/)

## 🔧 Installation & Setup
To run this project locally:
1. Clone the repository:
   ```bash
   git clone [https://github.com/bained/tonal_palette_generator.git](https://github.com/bained/tonal_palette_generator.git)
2. Or just download **index.html**

---
*Developed with a focus on UI/UX Science.*
