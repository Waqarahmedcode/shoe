# SHAN & MARFANI — World-Class Premium 3D Sneaker E-Commerce Site

This repository contains a high-end, responsive, interactive 3D e-commerce site for **SHAN & MARFANI (S&M)**. It combines a state-of-the-art WebGL 3D rendering engine, an interactive shoe customizer, a full-featured shopping cart/checkout flow, and a 2.5D layered visual fallback.

---

## 🚀 Key Features

1. **Interactive 3D Sneaker Model**:
   - Renders a highly detailed 3D sneaker in a simulated studio environment using **Three.js**.
   - Dual lighting states: **Warm pearl light mode** and **Charcoal dark mode**, matching the site theme.
   - Cinematic studio highlights: Cyan fill, magenta rim, energy orange bounces, and lime accents.
   - Smooth mouse-hover tilt (pointer parallax) and scroll-linked scale/rotation changes.

2. **Interactive 3D Customizer Lab**:
   - Allows users to select specific parts of the shoe (Mesh Upper, Overlays, Laces, Midsole, Tread, Inner Liner) by clicking on the 3D model (Raycaster) or utilizing control tabs.
   - Recolor parts in real-time with curated premium color swatches (Acid Lime, Hot Pink, Cyber Cyan, Energy Orange, Bone White, Charcoal Black).
   - Try ready-made designer presets (TOXIC NEON, CYBERPUNK, NIGHTFALL, SUNSET EDGE).
   - Add customized models directly to the Cart Drawer with custom spec details preserved.

3. **Responsive Parallax Fallback (2.5D Layered Engine)**:
   - If WebGL is disabled or the 3D sneaker model loading times out (>4.5s), the site automatically falls back to a 2.5D layered engine.
   - Layers (Background explosion, light streaks, shadow reflection, and high-res transparent sneaker) animate independently on mouse-move to maintain the illusion of depth.

4. **Complete E-Commerce Flow**:
   - Interactive slide-out **Bag Drawer** with quantity controls and subtotal calculations.
   - Integrated **Secure Checkout Modal** containing billing forms, payment methods (Cash on Delivery simulation), and final summaries.
   - **Order Success Overlay** with randomly generated Order IDs.
   - **Real-Time Order Tracking Console** (e.g. tracking for mock order `SM-1001` or any custom generated Order ID).
   - Full **Filtering & Sorting Sidebar** (Category, Gender, UK sizes, Price limits, and Authenticity Grades).

5. **Visual Excellence & Accessibility**:
   - Ultra-bold athletic display typography (`Anton`) and clean body copy (`Inter`).
   - Pure CSS custom grain noise overlays and magnetic CTA hover animations.
   - Seamless GreenSock (`GSAP`) + `ScrollTrigger` intersection reveals.
   - Responsive layouts optimized for mobile, tablet, and desktop viewports.

---

## 📁 File Structure

- [index.html](file:///e:/New%20folder/shoe%20brand%20marfani/index.html): The HTML structural shell of the application.
- [styles.css](file:///e:/New%20folder/shoe%20brand%20marfani/styles.css): Complete styling rules, responsive media queries, layouts, custom cursors, and theme variables.
- [app.js](file:///e:/New%20folder/shoe%20brand%20marfani/app.js): Application logic, Three.js WebGL setups, customizer click raycaster, filters, animations, and e-commerce state.
- [netlify.toml](file:///e:/New%20folder/shoe%20brand%20marfani/netlify.toml): Netlify build headers configuration.
- [assets/](file:///e:/New%20folder/shoe%20brand%20marfani/assets/): Production-grade images, transparent shoe silhouettes, glowing lighting streaks, and icons.

---

## ⚡ How to Run Locally

1. **Option A: Simple Local View**:
   - Double-click [index.html](file:///e:/New%20folder/shoe%20brand%20marfani/index.html) to open it directly in your browser.
   - *Note: Some modern browsers restrict loading CDN models over the file system (`file://` protocol) due to Cross-Origin Resource Sharing (CORS). For the full 3D experience, we recommend using Option B.*

2. **Option B: Local Web Server (Recommended)**:
   - Run a simple local HTTP server inside the project directory:
     - Using VS Code: Right-click `index.html` and select **Open with Live Server**.
     - Using Python: `python -m http.server 8000`
     - Using Node.js: `npx serve .`
   - Open `http://localhost:8000` (or the server's provided port) in your web browser.

---

## 🌐 How to Deploy to Netlify

1. Zip all files in the project folder (ensure `index.html`, `styles.css`, `app.js`, and `netlify.toml` are at the root level).
2. Go to [Netlify Drop](https://app.netlify.com/drop).
3. Drag and drop the generated ZIP file.
4. Netlify will deploy the site in seconds, and it will be live at a custom URL.
