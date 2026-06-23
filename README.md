# Virtual Air Writing AI 🖊️✨

[![Python](https://img.shields.io/badge/Python-3.11+-blue.svg)](https://www.python.org/)
[![OpenCV](https://img.shields.io/badge/OpenCV-4.8+-green.svg)](https://opencv.org/)
[![MediaPipe](https://img.shields.io/badge/MediaPipe-Latest-orange.svg)](https://mediapipe.dev/)
[![EasyOCR](https://img.shields.io/badge/EasyOCR-ML-red.svg)](https://github.com/JaidedAI/EasyOCR)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

An advanced, production-quality desktop application that allows users to write in the air using only their index finger and a webcam. Leveraging state-of-the-art Computer Vision (MediaPipe) and Deep Learning (EasyOCR), this tool transforms hand gestures into digital text, documents, and voice output.

---

## 📺 Live Demo & Preview
> **Interactive Preview:** If you are viewing this in the Arena.ai agent mode, open `index.html` and click **Preview** to launch the browser-based live demo immediately.

---

## 🚀 Key Features

### 🖐️ Advanced Hand Tracking & Gestures
- **Index Finger Up**: Smooth drawing on the virtual canvas.
- **V-Sign (Index + Middle)**: Hover mode (cursor movement without ink).
- **Spider-Man Pose**: Cycle through brush colors.
- **Pinch (Thumb + Pinky)**: Dynamic brush resizing.
- **Open Palm**: Instant canvas clear.
- **Thumb Up**: Auto-save current progress.
- **Three Fingers**: Undo last stroke.

### 🎨 Creative Tools
- **Smoothing Engine**: Real-time line interpolation for professional handwriting.
- **Multi-Mode**: Pencil, Highlighter, Brush, and Eraser modes.
- **Infinite Canvas**: New page functionality with grid/background options.

### 🧠 Intelligence & Accessibility
- **OCR Engine**: Recognizes handwritten English using EasyOCR with high confidence.
- **Voice Synthesis**: Reads recognized text aloud with adjustable speed.
- **Multi-Format Export**: Save as TXT, DOCX, PDF, Markdown, or PNG.

### 💻 Professional UI/UX
- **Dual Themes**: Polished Dark and Light modes.
- **Statistics Dashboard**: Real-time FPS, drawing time, word count, and confidence scores.
- **Settings Panel**: Fully customizable camera, brush, and audio settings.

---

## 🛠️ Technology Stack

| Category | Tools |
| :--- | :--- |
| **Vision** | OpenCV, MediaPipe |
| **Deep Learning** | EasyOCR, PyTorch |
| **GUI** | Tkinter, CustomTkinter (Themes) |
| **File Processing** | python-docx, ReportLab, Pillow |
| **Audio** | Pyttsx3 |
| **Utilities** | NumPy, Pytest, Logging |

---

## 📦 Installation

### Prerequisites
- Python 3.11 or higher
- A working webcam

### Step-by-Step
1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/Virtual-Air-Writing.git
   cd Virtual-Air-Writing
   ```

2. **Setup Virtual Environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Launch Application**
   ```bash
   python main.py
   ```

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
| :--- | :--- |
| `Ctrl + S` | Save File |
| `Ctrl + Z` | Undo |
| `Ctrl + Y` | Redo |
| `Ctrl + N` | New Page |
| `Ctrl + Q` | Exit Application |

---

## 📂 Project Structure

```text
Virtual-Air-Writing/
├── src/                # Modular Source Code
│   ├── camera.py       # Webcam Logic
│   ├── hand_tracker.py # MediaPipe Integration
│   ├── ocr.py          # AI Text Recognition
│   ├── drawing.py      # Graphics Engine
│   └── gui.py          # Tkinter Interface
├── docs/               # System Architecture & Guides
├── tests/              # Pytest Unit Tests
├── output/             # Exported Notes & Images
├── main.py             # App Entry Point
└── index.html          # Web-based Live Demo
```

---

## 🤝 Contributing
Contributions are welcome! Please read the `CONTRIBUTING.md` for details on our code of conduct and the process for submitting pull requests.

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🌟 Acknowledgments
- MediaPipe for the incredible hand tracking API.
- JaidedAI for the EasyOCR framework.
- The Python Open Source Community.
