# 🚀 FetcherPY

> A fully vibe-checked, modern, and snappy `neofetch` alternative written in Python using the `Rich` library. Crafted specifically for those who crave TrueColor gradients and pure aesthetic in their terminal.

---

## ✨ Features

* 🎨 **TrueColor Gradients:** None of that depressing 8-bit color nonsense — only juicy 16-million Hex gradients.
* ⚡ **Blazing Fast:** Minimalist system info gathering powered by `psutil`.
* 📦 **Package Manager Support:** Counts your `pacman` and `flatpak` packages right out of the box.
* 🖥️ **Smart GPU Detection:** Laser-focused `lspci` parsing without any useless clutter in your graphics card line.
* 🎛️ **Gorgeous TUI:** Separate, neatly bordered panels for ASCII art and system stats.

---

## 📸 Screenshot
<img width="1101" height="375" alt="image" src="https://github.com/user-attachments/assets/032e51ac-cd42-49d1-9ca7-5b54357bd93d" />

---

## 🛠️ System Requirements

To get this running smoothly, you'll need:
* **Python** >= 3.10
* Libraries: `pip install rich psutil`
* *Optional:* `wmctrl` (for proper WM detection in X11 sessions)

---

## 🚀 Installation & Running

### Clone the repository
```bash
git clone [https://github.com/i114rk/FetcherPY.git](https://github.com/i114rk/FetcherPY.git)
cd fetcherpy
```

## Environment Setup (Recommended)
```bash
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```
(Don't forget to create a requirements.txt file with rich and psutil inside)

## Run it
```bash
python fetcherpy.py
```

## 📄 License

This project is licensed under the IDGAF license, reddit.com/r/UnixPorn is in the house, the project is open source.

P.S. Even this README was written by an AI, except for this P.S.
