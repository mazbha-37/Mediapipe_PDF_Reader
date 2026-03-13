# 📄 MediaPipe PDF Reader — NLP-Powered Document Interaction

> **CSE442: Artificial Intelligence** — BRAC University  
> **Author:** Mazbha Ul Haque (ID: 22101514)

---

## Overview

**MediaPipe PDF Reader** is an AI-powered application that combines **Natural Language Processing (NLP)** with an intuitive **UI/UX** to create a seamless document reading and interaction experience. The system leverages **Google MediaPipe** and **TensorFlow** to enable gesture-based and intelligent PDF navigation, transforming how users interact with documents.

---

## ✨ Features

- 🖐️ **Gesture-Based Navigation** — Use hand gestures via MediaPipe to flip pages, scroll, and zoom
- 🧠 **NLP Text Processing** — Intelligent text extraction, summarization, and keyword highlighting
- 📊 **Before & After Analysis** — Visual comparison of document processing results
- 🎨 **Clean UI/UX** — Modern, user-friendly interface for smooth document interaction
- 📷 **Model Integration** — Pre-trained models for real-time gesture recognition
- 📑 **PDF Rendering** — Full PDF viewing and manipulation capabilities

---

## 🛠️ Tech Stack

<p align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-0097A7?style=for-the-badge&logo=google&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

</p>

---

## 📁 Project Structure

```
MEDIAPIPE-PDF-READER/
│
├── Dataset Before And After/    # Pre and post-processing data comparison
├── dist/                        # Production build files
├── images/                      # Project images and assets
├── modelPhotos/                 # Model training and result screenshots
├── src/                         # Source code (frontend + NLP logic)
├── tensorflow-ipynb/            # TensorFlow & MediaPipe Jupyter notebooks
│
├── 442_complete_report.pdf      # Complete project report
├── LICENSE.txt                  # License information
└── README.md
```

---

## 🔬 Methodology

```
┌──────────────┐     ┌──────────────┐     ┌──────────────┐     ┌──────────────┐
│  PDF Input   │────▶│  Text & NLP  │────▶│  MediaPipe   │────▶│  Interactive │
│  Document    │     │  Processing  │     │  Gestures    │     │  UI Output   │
└──────────────┘     └──────────────┘     └──────────────┘     └──────────────┘
```

1. **Document Ingestion** — PDF is loaded and parsed for text and layout extraction
2. **NLP Processing** — Text undergoes tokenization, keyword extraction, and summarization
3. **Gesture Recognition** — MediaPipe hand-tracking enables gesture-based document control
4. **UI Rendering** — Processed content is displayed through a clean, responsive interface

---

## 🚀 How to Run

### Prerequisites
```
Python 3.8+  |  pip  |  Webcam (for gesture features)
```

### Installation

```bash
# Clone the repository
git clone https://github.com/mazbha-37/MEDIAPIPE-PDF-READER.git
cd MEDIAPIPE-PDF-READER

# Install dependencies
pip install tensorflow mediapipe opencv-python numpy

# Run the application
cd src
python main.py
```

### Notebooks
Explore the `tensorflow-ipynb/` folder for training notebooks and model experiments.

---

## 📸 Screenshots

> Screenshots and demo visuals are available in the `images/` and `modelPhotos/` directories.

---

## 📋 Course Information

<div align="center">

| | |
|:---:|:---:|
| 📚 **Course** | CSE442: NATURAL LANGUAGE-DRIVEN UI/UX |
| 🏫 **University** | BRAC University |
| 👤 **Student** | Mazbha Ul Haque |
| 🆔 **Student ID** | 22101514 |

</div>

---

## 📄 License

This project is developed for academic purposes as part of the CSE442 coursework at BRAC University. See `LICENSE.txt` for details.

---

<p align="center">
  <i>Built with ❤️ using MediaPipe, TensorFlow & NLP</i>
</p>
