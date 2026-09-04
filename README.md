# ❤️ Heart Forming

A simple animated heart built with mathematics, drawing, and animation.

## ✨ Features

- ❤️ Mathematical heart shape
- ✨ Animated line-by-line formation
- 🎨 Smooth color gradient
- ⚡ Approximately 1.8× the original Python animation speed
- 📱 Responsive HTML Canvas version for mobile and desktop browsers
- 🌐 Can be hosted with GitHub Pages

## 🛠️ Versions

### Python Turtle

The original version uses Python's `turtle` module and creates the heart as a desktop animation.

### Web Version

`index.html` recreates the animation using HTML Canvas and JavaScript, making it accessible from phones, tablets, Windows, and Mac through a web browser.

## 🚀 Run the Web Version

Open `index.html` in a browser, or enable **GitHub Pages** for this repository and open the generated Pages URL.

## 🐍 Run the Python Version

Make sure Python is installed, then run:

```bash
python heart.py
```

## 📦 Windows EXE

The Python version can be packaged as a Windows executable with PyInstaller:

```bash
py -m PyInstaller --onefile --noconsole heart.py
```

The executable will be created inside the `dist` folder.

## 📁 Project Structure

```text
HEART-FORMING/
├── index.html      # Mobile/desktop web version
├── heart.py        # Original Python Turtle version
├── dist/           # Generated Windows executable (if built locally)
└── README.md
```

## 📄 License

This project is available for learning and personal use.

---

Made with ❤️ and Python/JavaScript.
