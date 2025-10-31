# Modern QR Code Suite

A sleek, mobile-first, privacy-focused QR code generator and scanner built with pure HTML, CSS, and JavaScript. This single-page application works entirely offline and in your browser—no data ever leaves your device.

![App Screenshot](https://i.imgur.com/your-screenshot-url.png)
*(Replace the URL above with a link to your own screenshot)*

## ✨ Features

* **Generate QR Codes:** Create custom QR codes for URLs and plain text.
* **Customize Styles:**
    * Change dot and corner colors.
    * Select different dot and corner square styles.
    * Set a custom background color.
* **Add Your Logo:** Embed your own logo directly into the QR code.
* **Scan QR Codes:** Use your device's camera to scan codes instantly from the browser.
* **100% Client-Side:** **No data ever leaves your device.** All processing (generation, scanning, and storage) happens locally in your browser.
* **History:** Automatically saves your generated and scanned codes to your browser's local storage for quick access.
* **Mobile-First Design:** A beautiful, responsive, app-like interface that works perfectly on all devices, from phones to desktops.
* **Download Options:** Save your generated codes as high-quality **PNG** or **SVG** files.
* **Zero Dependencies:** Runs as a single `index.html` file. No server, no `npm install`, just plain web technologies.

## 🚀 How to Use

No setup or build process is required!

1.  Download the `index.html` file from this repository.
2.  Open the file in any modern web browser (like Chrome, Firefox, or Safari).
3.  That's it! The app will work instantly, even offline.

## 🛠️ Tech Stack

This project is intentionally lightweight and built with fundamentals:

* **HTML5**
* **Tailwind CSS** (loaded via a CDN for rapid, responsive styling)
* **JavaScript (ES6+)** (for all application logic and interactivity)
* **[qr-code-styling.js](https://github.com/kozakdenys/qr-code-styling)** (for advanced QR code generation and styling)
* **[jsQR.js](https://github.com/cozmo/jsQR)** (for QR code scanning from the camera)

## 🔒 Privacy-First

This tool is built with privacy as the top priority.
* **No Server:** The entire application is a single static file.
* **No Data Transmission:** All scanning and generation happen 100% in your browser. No images, data, or history are ever sent to a server.
* **Local Storage:** Your history is saved *only* on your own device using the browser's `localStorage`.

## Future Improvements

* [ ] Add more QR code types (Wi-Fi, vCard, Email, SMS).
* [ ] Implement gradient colors for QR code dots.
* [ ] Add PWA (Progressive Web App) support to install it on a phone.

---
*This project was built with assistance from Gemini.*
