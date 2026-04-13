# PWA Maker: Material 3 Depth Edition

A sophisticated, single-page utility designed to transform your standalone HTML projects into fully functional **Progressive Web Apps (PWAs)** with just a few clicks.

Built on the **Material 3 Depth** design philosophy, this tool combines the power of Google's **Material Web Components (MWC)** with a modern, immersive "Liquid Glass" interface.

---

## 🎨 Design Philosophy: Material 3 Depth
This application is more than just a utility; it is an implementation of the **Material 3 Depth** design system. 

- **Dynamic Color Engine**: Powered by `@material/material-color-utilities`, the entire UI adapts its color scheme dynamically based on a single seed color. It generates a full suite of M3 tonal palettes (Primary, Secondary, Tertiary, Surface, etc.) ensuring visual harmony in both Light and Dark modes.
- **Glassmorphism & Depth**: Unlike flat Material designs, this version utilizes high-index background blurs (24px), semi-transparent surfaces, and fluid animated mesh gradients to create a sense of hierarchy and spatial "depth."
- **Floating Navigation**: A refined, label-less floating navigation bar provides a clean, mobile-first experience that prioritizes content while keeping actions within reach.

---

## 🚀 Key Features

### 1. Instant PWA Generation
Converting an app to a PWA usually requires manual creation of multiple files and complex configurations. This tool automates the "boring parts":
- **Manifest Generation**: Automatically creates a valid `manifest.json` based on your metadata.
- **Service Worker (sw.js)**: Generates a standard caching script to enable offline support and "Add to Home Screen" functionality.
- **Smart Injection**: It takes your raw HTML and injects the necessary `<link>` and `<script>` tags for the PWA to function, without breaking your existing code.

### 2. Automatic Icon Processing
No need for external image editors. Upload a single high-resolution PNG, and the app uses the browser's Canvas API to:
- Resize images to required PWA dimensions (**192x192** and **512x512**).
- Package them into the final ZIP distribution.

### 3. ZIP-Ready Deployment
Everything is bundled into a single `.zip` file, ready to be extracted into your GitHub Pages or web server root directory.

---

## 🛠 Tech Stack
- **Framework**: Pure HTML5, CSS3, and Vanilla JavaScript.
- **Components**: [Material Web Components (MWC)](https://github.com/material-components/material-web) by Google.
- **Color Logic**: Monet-style Dynamic Color algorithms.
- **Packaging**: [JSZip](https://stuk.github.io/jszip/) for client-side file compression.

---

## ⚠️ Scope & Limitations
**"Simplicity over Complexity"**

This tool is specifically designed for **Single-File HTML Apps** (where CSS and JS are integrated). 
- **What it does**: Provides a robust, "minimum viable" PWA setup (Installation + Basic Caching).
- **What it doesn't do**: It does not support complex build pipelines (Webpack/Vite), multi-page directory structures, or advanced caching strategies (Background Sync, Workbox-level fine-tuning). 

It is the perfect companion for developers who want to take their "one-file tools" or "creative experiments" and make them feel like professional, installable applications.

---

## 📖 How to Use
1. **Configure**: Enter your App Name and GitHub Repository name (for the cache scope).
2. **Branding**: Upload a square PNG and pick your favorite accent color.
3. **Source**: Paste your integrated HTML code into the editor.
4. **Build**: Hit "Generate PWA Package" and download your ZIP.

---
*Created with the Material 3 Depth Framework - Immersive, Fluid, and Functional.*
