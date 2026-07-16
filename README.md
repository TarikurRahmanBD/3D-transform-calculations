# 3D Transform Calculations (Anime.js Periodic Table)

An interactive, high-performance 3D periodic table animation utilizing **Anime.js** for smooth transitions. The core 3D spatial calculations—mapping elements into dynamic geometric layouts like spheres, helixes, and grids—have been custom-ported directly from **three.js** to run natively using CSS 3D transforms.

This project delivers a lightweight, highly responsive 3D visualization without the overhead of a full WebGL rendering engine.

---

## 🚀 Features

* **Four Interactive Layouts:** Seamlessly morph elements between **Table**, **Sphere**, **Helix**, and **Grid** views.
* **Three.js Math Port:** Recreates complex 3D vector and matrix calculations to position flat HTML/CSS elements in physical 3D space.
* **High Performance:** Built with pure HTML, CSS, and JS, utilizing hardware-accelerated CSS 3D transforms (`transform-style: preserve-3d`).
* **Smooth Motion:** Managed entirely by custom easing curves using **Anime.js**.

---

## 🛠️ Tech Stack

* **Animation Engine:** [Anime.js](https://animejs.com/)
* **Styling:** Custom CSS (Flexbox, Grid, 3D Transforms)
* **Calculations:** Ported three.js vector layouts (3D transform mathematics)
* **Core:** Vanilla JavaScript, HTML5

---

## 📦 Installation & Local Setup

Getting the project up and running locally takes just a few seconds.

1.  **Clone the Repository**
    ```bash
    git clone [https://github.com/TarikurRahmanBD/3D-transform-calculations.git](https://github.com/TarikurRahmanBD/3D-transform-calculations.git)
    cd 3D-transform-calculations
    ```

2.  **Run Locally**
    * Since this is a client-side web application, you can simply open `index.html` directly in your browser.
    * Alternatively, run it using a local development server like **Live Server** in VS Code to ensure smooth asset loading:
        ```bash
        # If you have Node/npm installed, you can spin up a quick server:
        npx serve .
        ```

3.  **Explore**
    * Open `http://127.0.0.1:5000` (or your local port) in your browser.
    * Click the **table**, **sphere**, **helix**, and **grid** navigation buttons at the top to trigger the 3D layouts!

---

## 📂 Project Structure

```text
├── index.html      # Structure of the periodic table elements and control UI
├── style.css       # Layout styles and perspective-preserving 3D setup
└── script.js      # Core logic: Element generation, Anime.js config, and 3D math ports
