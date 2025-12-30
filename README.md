# ManchiCode V3.0

**ManchiCode** is a lightweight retro-hacker code editor (v3.0) created as part of my portfolio to demonstrate my frontend development and DOM manipulation skills.  
The goal is to provide an immersive and fast editing tool optimized for mobile devices, focusing on technical implementation rather than commercial use.

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Tech Stack](https://img.shields.io/badge/Tech-HTML_JS_&_CSS-orange.svg)](#tech-stack)
[![Status](https://img.shields.io/badge/Status-Active-brightgreen.svg)](#)

---

## 🚀 Live Demo

Access the editor directly here:  
👉 [ManchiCode V3.0 on GitHub Pages](https://stevemanchado.github.io/ManchiCode/)

---

## ✨ Features

- 📟 **Retro Aesthetics** → UI inspired by classic terminals with a CRT scanline effect.
- 📱 **Mobile Optimized** → Integrated quick keyboard for programming symbols (`{`, `}`, `>`, etc.).
- 🔢 **Dynamic Gutter** → Line numbering system that automatically adjusts to text wrapping.
- 📖 **Data Indexing** → Real-time scanning of functions, classes, and IDs for quick navigation.
- 🔊 **Audio Feedback** → Synthetic typing and clicking sounds generated via Web Audio API.
- 🌐 **Multilingual & Themes** → Support for Spanish/English and Light (Vintage Paper) / Dark (Phosphor Green) modes.
- ▶️ **HTML Runner** → Instant preview for `.html` files in a new window.

---

## 🛠️ Technologies Used

- **HTML5** → Semantic structure and editor containers.
- **CSS3** → Modern variables, terminal animations, and responsive design (Flexbox/Grid).
- **Vanilla JavaScript (ES6+)** → Core logic without external libraries:
  - **Web Audio API** → Procedural sound generation.
  - **Regex Engine** → Structure scanning for the index.
  - **File System API** → File reading and downloading management.
  - **Dynamic Mirroring** → Mirroring technique for line height calculation.

---

## 📂 Project Structure

├── index.html # Main application (Monolithic for maximum portability)

└── README.md # Project documentation


---

## ⚙️ How It Works

1. **Initialize or Load** - Create a new file from scratch or load an existing script from your device.

2. **Code with Style** - Enjoy the visual and auditory immersion while you type.  
   - Use the bottom quick keyboard if you are on a mobile device.

3. **Navigate Structure** - Open the **Index** to jump directly to a specific function or ID within your code.

4. **Run and Save** - If working on HTML, use the **RUN** button to see the result.  
   - Download your final work directly using the **SAVE** button.

---

## 📈 Future Improvements

- 🔄 Support for custom Syntax Highlighting.
- 💾 `localStorage` persistence to prevent data loss on refresh.
- 🎨 Theme editor for custom colors and fonts.
- 📂 Multi-file explorer support.
- 📡 Basic integration with GitHub repositories (Gists).

---

⚠️ This project is for **portfolio demonstration purposes only**. Developed by **Steven Arias** (2025).
