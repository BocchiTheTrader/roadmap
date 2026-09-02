# Customizable Dynamic Curriculum Tracker (v1.5)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222222?style=for-the-badge&logo=GitHub%20Pages&logoColor=white)

A modern, zero-dependency, single-file client-side curriculum and goal tracking application originally designed by **BocchiTheTrader**. It requires no compilers, package managers, or Node.js setup. Run it directly via **GitHub Pages** or by simply double-clicking the `index.html` file.

<img width="1917" height="1079" alt="Screenshot 2026-09-03 000207" src="https://github.com/user-attachments/assets/0f740e92-5bd5-40f3-97b0-c9f17123bc38" />

## ✨ Features

* **Customizable Branding (GIFs allowed):** Click on the top left profile area to edit the app name and upload a custom avatar via Drag & Drop. Animated GIFs are fully supported. The browser tab title updates automatically.
* **Smart Storage Engine:** Built-in JS engine scales standard images to 250x250px WebP to save space. GIFs are kept raw but limited to 2MB to ensure the `localStorage` never crashes.
* **Multi-Domain Management:** Create and delete separate tracking domains for different courses or projects.
* **Subtopic Support:** Break down large concepts by clicking the "Arrow" (↵) icon on any topic to add independent sub-items.
* **Rapid Topic Entry & Editing:** Fast topic entry via a single input triggered by the "Enter" key. Double-click a topic name for instant (inline) editing.
* **Flexible Reordering:** Easily rearrange topics chronologically or by difficulty using the `Up/Down` arrows.
* **Progress Telemetry:** Animated progress bar and "Completed: X / Y Topics" chip showing completion rate per main topic.
* **Data Portability:** All data is kept in the browser's local storage. Offers `.json` format export and import capabilities.

## 🚀 Quickstart

Setting up this project takes less than a minute:

1. Clone or download the repository to your computer:
   

🛠️ Architecture Details & Technologies
This application pulls external libraries securely via HTTPS CDNs, preventing local file breakage.

Style Engine: Tailwind CSS CDN

Icon Set: Lucide Icons CDN

Typography: Google Fonts (Inter)

State Engine: Vanilla JavaScript ES6+ & LocalStorage

📄 License
This project is licensed under the MIT License. You are free to use, copy, modify, and integrate it into your own projects.
