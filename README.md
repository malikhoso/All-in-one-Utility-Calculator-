# All-in-One Utilities Hub (Web)

A sleek, dark-mode-ready web application providing essential daily tools in a single interface. Built with a focus on speed and user experience, this "Utility Hub" handles complex file conversions and health/academic calculations entirely on the client side.

## 🛠️ Integrated Tools

* **Advanced File Converter:**
    * **Image ↔ Image:** Seamlessly convert between JPG and PNG.
    * **Image → PDF:** Convert photos into high-quality PDF documents.
    * **PDF → Image:** Render PDF pages into downloadable PNG images using `PDF.js`.
* **BMI Calculator:** Supports Metric, Imperial, and Mixed units with real-time health category classification.
* **GPA Calculator:** Dynamic subject entry system that calculates weighted GPA based on credit hours and letter grades.

## ✨ Key Features

* **Client-Side Processing:** No files are uploaded to a server. All conversions (PDF/Images) happen directly in the browser for maximum privacy and speed.
* **Modern UI/UX:** Built with **Tailwind CSS**, featuring a polished "Inter" typography, smooth transitions, and a fully responsive layout.
* **Smart Dark Mode:** Automatically detects system preferences and allows manual toggling with persistent storage (LocalStorage).
* **Drag & Drop:** Interactive file upload area with visual feedback for seamless user interaction.

## 🚀 Technical Tech Stack

* **Frontend:** HTML5, Tailwind CSS, JavaScript (ES6+).
* **File Handling:** [PDF.js](https://mozilla.github.io/pdf.js/) for rendering PDF content to canvas.
* **Document Generation:** [jsPDF](https://github.com/parallax/jsPDF) for creating PDF files from images.
* **Icons & Fonts:** Google Fonts (Inter) & Custom SVG icons.

## 📂 Project Structure

```text
├── index.html          # Single-page application containing all logic
├── README.md           # Project documentation
└── (Libraries via CDN) # Tailwind, PDF.js, jsPDF
