# 📱 QR Code Studio

[![GitHub Pages](https://img.shields.io/badge/Hosted%20With-GitHub%20Pages-blue?style=for-the-badge&logo=github)](https://qrstudiopro.github.io)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](LICENSE)

An online studio-style platform to design, customize, and generate high-precision QR codes. Features rich styling controls, dynamic content presets, middle logo integration, instant presentation display in a new tab, and smart export behaviors for PNG, PDF, and clipboard copying.

---

## 🚀 Live Demo

🔗 **Access the Application Directly:** [https://qrstudiopro.github.io](https://qrstudiopro.github.io)

---

## ✨ Key Features

### 🎨 1. Full Visual Customization
* **Pattern Shapes:** Choice of Square, Dots, Rounded, Extra Rounded, Classy, and Classy Rounded.
* **Gradients & Colors:** Custom linear gradient pattern overlays with angle controls, transparent background support, and distinct corner frame/eyeball color pickers.
* **Middle Logo Integration:** Preset icon library (Wi-Fi, Globe, WhatsApp, Instagram, Email, Heart, Star) or custom file upload with adjustable scale and margin sliders.
* **Error Correction Levels:** Adjustable levels from Low (7%) to High (30% - ideal for logo overlays).

### 📋 2. Dynamic Content Types
Easily generate QR codes for diverse data types using built-in input generators:
| Data Type | Description |
| :--- | :--- |
| 🌐 **Website Link** | Direct URL formatting |
| 📝 **Plain Text** | Custom message or raw text strings |
| 📶 **Wi-Fi Network** | Encrypted config (WPA/WPA2/WPA3, WEP, Open) with hidden network flag |
| 🎴 **vCard Contact** | Comprehensive contact card details (Name, Phone, Email, Company, Job Title, Web) |
| ✉️ **Email** | Pre-filled email template (Recipient, Subject, Body) |
| 💬 **SMS / WhatsApp** | Direct messaging links with pre-filled text |
| 📁 **File / Media** | File dropzone conversion to direct data URI stream or external file link |

### ✨ 3. Animated Presentation Screen
* **In-Browser Display:** Launch a full-screen presentation view in a new browser tab with one click.
* **Visual Effects:** Features animated entrance transitions, ambient floating glow orbs, shimmering neon borders, and responsive high-contrast scannable QR display.
* **Fullscreen Toggle:** Built-in presenter control bar for interactive showcases.

### 📄 4. Smart Export Logic
* **PNG Card Export:** High-density render of the QR design card. *Scanning guide dropdown is automatically excluded for a clean image output.*
* **PDF Document Export:** Formats an A4 PDF document with the scanning guide automatically expanded for printable instructions.
* **Raw QR Download:** Direct export of standalone QR code graphic.
* **Clipboard Copy:** One-click instant copy of the QR graphic to system clipboard.

### 🌓 5. Automatic Theme Adaptation
* **System Default Detection:** Automatically respects user system/browser preferred appearance (`prefers-color-scheme`).
* **Header Toggle Switch:** Top-right slider switch to manually toggle between Light and Dark modes seamlessly.

---

## 📂 Project Structure

```text
qrstudiopro.github.io/
├── index.html       # Standalone single-file application (HTML, Tailwind, JS Engine)
└── README.md        # Documentation and platform overview
```

---

## 🛠️ Local Development & Deployment

### Running Locally
Since **QR Code Studio** is built as a zero-dependency static application, no Node.js build step is required!

1. Clone this repository:
   ```bash
   git clone https://github.com/qrstudiopro/qrstudiopro.github.io.git
   ```
2. Navigate into the directory:
   ```bash
   cd qrstudiopro.github.io
   ```
3. Open `index.html` in any web browser.

### Hosting on GitHub Pages
1. Push your changes to the `main` or `gh-pages` branch.
2. Go to **Settings** > **Pages** in your GitHub repository.
3. Select the source branch as `main` (root folder `/`) and click **Save**.
4. Your site will be published automatically at `https://qrstudiopro.github.io`.

---

## 📄 License & Credits

* **Copyright:** © 2026 All rights reserved.
* **Developer:** **DHStackWorks**
* **Email Contact:** [dinethhesara20@gmail.com](mailto:dinethhesara20@gmail.com)

*Built using open-source libraries: [qr-code-styling](https://github.com/qr-code-styling/qr-code-styling), [html2canvas](https://html2canvas.hertzen.com/), and [jsPDF](https://github.com/parallax/jsPDF).*