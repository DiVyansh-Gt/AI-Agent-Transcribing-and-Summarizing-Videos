# 🎥 AI Agent: Transcribing & Summarizing Videos

![Status](https://img.shields.io/badge/Status-Production_Ready-success?style=for-the-badge)
![Language](https://img.shields.io/badge/Language-Python-blue?style=for-the-badge)
![Framework](https://img.shields.io/badge/UI-Streamlit-red?style=for-the-badge)
![Speech-to-Text](https://img.shields.io/badge/Speech--to--Text-OpenAI_Whisper-green?style=for-the-badge)
![Summarization](https://img.shields.io/badge/Summarization-HuggingFace_BART-orange?style=for-the-badge)
![Deep Learning](https://img.shields.io/badge/Deep_Learning-PyTorch-purple?style=for-the-badge)

> **🚀 AI Agent** is an intelligent AI-powered application that automatically transcribes video content into accurate text and generates concise summaries using **OpenAI Whisper**, **Hugging Face Transformers (BART)**, **PyTorch**, and **Streamlit**. It enables users to extract key insights from lengthy videos within seconds.

---

# 🚀 Overview

Watching long lectures, webinars, meetings, and educational videos often requires significant time to identify important information.

**AI Agent** simplifies this process by automatically converting spoken content into text and generating high-quality summaries using modern transformer-based AI models.

The application combines Speech Recognition, Natural Language Processing, and Deep Learning to provide a complete AI-powered video understanding workflow.

Whether you're a student, researcher, educator, or content creator, AI Agent helps save time while improving accessibility and productivity.

---

# ⚡ System Architecture & Engineering Highlights

The project follows a modular Artificial Intelligence pipeline where each processing stage is isolated into dedicated components.

The complete workflow consists of:

- Video Processing
- Audio Extraction
- Speech Recognition
- Transcript Processing
- AI Summarization
- Result Visualization

The architecture ensures scalability, modularity, and clean separation between each AI processing step.

---

# 🏗️ Architecture Overview

```
                    ┌────────────────────────────┐
                    │     Streamlit Frontend     │
                    │      User Interface        │
                    └──────────────┬─────────────┘
                                   │
                           Upload Video
                                   │
                                   ▼
                    ┌────────────────────────────┐
                    │      Processing Engine     │
                    └──────────────┬─────────────┘
                                   │
        ┌──────────────┬───────────┼───────────────┬──────────────┐
        ▼              ▼           ▼               ▼              ▼
  Video Upload     FFmpeg      Whisper AI     Transcript      BART Model
  Processing    Audio Extract  Speech Model    Chunking     AI Summarizer
                                   │
                                   ▼
                      Transcript + Final Summary
```

---

# 🚀 Engineering Highlights

## 🎬 Intelligent Video Processing

The application automatically processes uploaded videos before passing them through the AI pipeline.

### Features

- Video Upload
- Automatic Processing
- Multiple Video Formats
- Audio Extraction
- Temporary File Management

---

## 🎧 Audio Extraction Engine

The uploaded video is converted into audio using **FFmpeg**.

### Benefits

- Fast Audio Conversion
- Supports Multiple Formats
- High Audio Quality
- Efficient Processing Pipeline

---

## 🗣️ Speech Recognition using OpenAI Whisper

Speech transcription is powered by **OpenAI Whisper**, one of the most accurate open-source speech recognition models.

### Capabilities

- Accurate Speech Recognition
- Multiple Accent Support
- Automatic Punctuation
- Long Audio Processing
- Noise Robustness
- High-quality Transcript Generation

---

## 🧠 AI-powered Text Summarization

The generated transcript is summarized using **facebook/bart-large-cnn** from Hugging Face Transformers.

### Features

- Transformer-based Summarization
- Context Preservation
- Human-readable Output
- Long Document Support
- High-quality Summary Generation

---

## ✂️ Smart Transcript Processing

Long transcripts are automatically divided into smaller chunks before summarization.

### Benefits

- Better Memory Management
- Improved AI Performance
- Handles Long Videos
- Prevents Token Overflow

---

## ⚡ Interactive Streamlit Interface

The application provides a lightweight and responsive graphical interface.

### Features

- Drag & Drop Upload
- One-click Processing
- Interactive Components
- Responsive Layout
- Easy-to-use Interface

---

# ✨ Core Features

- 🎥 Video Upload
- 🎧 Automatic Audio Extraction
- 🗣️ OpenAI Whisper Speech Recognition
- 📝 Accurate Transcript Generation
- 🧠 AI-powered Text Summarization
- ✂️ Transcript Chunk Processing
- 📄 Download-ready Transcript
- ⚡ Streamlit User Interface
- 🔥 PyTorch Deep Learning Backend
- 🤖 Hugging Face Transformers
- 📱 Beginner-friendly Interface
- 🚀 Fast Processing Pipeline

---

# 🎯 Project Goals

The primary objective of **AI Agent** is to build an intelligent AI system capable of:

- Automatically converting spoken video content into text.
- Generating concise AI-powered summaries.
- Reducing the time required to understand lengthy videos.
- Improving accessibility for educational and professional content.
- Demonstrating real-world applications of Speech Recognition and Natural Language Processing.
- Showcasing transformer-based AI models in a practical end-to-end application.

---

# 🛠️ Complete Tech Stack

## 🖥️ Frontend & User Interface

| Technology | Purpose |
|------------|---------|
| **Streamlit** | Interactive web application interface |
| **Python** | Core programming language |
| **HTML/CSS (Streamlit Components)** | UI rendering |

---

## 🤖 Artificial Intelligence & Machine Learning

| Technology | Purpose |
|------------|---------|
| **OpenAI Whisper** | Speech-to-Text Transcription |
| **Hugging Face Transformers** | AI Text Summarization |
| **facebook/bart-large-cnn** | Transformer-based Summarization Model |
| **PyTorch** | Deep Learning Framework |
| **SentencePiece** | NLP Tokenization |
| **Tokenizers** | Efficient Transformer Tokenization |

---

## 🎬 Media Processing

| Technology | Purpose |
|------------|---------|
| **FFmpeg** | Audio Extraction from Videos |
| **Movie Processing Pipeline** | Video Handling |
| **Temporary File Management** | Intermediate Processing |

---

## ⚙️ Python Libraries

| Library | Purpose |
|---------|---------|
| **Streamlit** | User Interface |
| **Torch** | Deep Learning |
| **Transformers** | NLP Models |
| **Whisper** | Speech Recognition |
| **FFmpeg-Python** | Audio Extraction |
| **OS** | File Management |
| **Tempfile** | Temporary Storage |

---

# 📂 Project Structure

```text
AI-Agent-Transcribing-and-Summarizing-Videos/

│

├── app.py

├── requirements.txt

├── ffmpeg.exe

├── README.md

│

├── models/

│

├── utils/

│

├── assets/

│

└── temp/
```

---

# 🚀 Major Project Modules

## 🎥 Video Processing Module

Responsible for handling uploaded videos before AI processing.

### Responsibilities

- Accept video uploads
- Validate file formats
- Prepare media pipeline
- Temporary storage

---

## 🎧 Audio Extraction Module

Uses FFmpeg to separate audio from video.

### Features

- Automatic Extraction
- Fast Processing
- High Audio Quality
- Multiple Format Support

---

## 🗣️ Speech Recognition Module

Powered by **OpenAI Whisper**.

### Capabilities

- Speech Recognition
- Automatic Transcription
- Noise Handling
- Long Audio Support
- Accurate Text Generation

---

## 🧠 AI Summarization Module

Uses **facebook/bart-large-cnn**.

### Features

- AI Summary Generation
- Transformer Models
- Context Preservation
- Human-readable Output

---

## 📄 Output Module

Displays generated transcript and summary.

### Includes

- Transcript Viewer
- AI Summary
- Scrollable Output
- Easy Reading Experience

---

# 📸 Application Screenshots

> Replace these placeholders with actual screenshots after deployment.

## 🏠 Home Screen

```text
screenshots/home.png
```

---

## 🎥 Upload Video

```text
screenshots/upload.png
```

---

## 🗣️ Transcript Generation

```text
screenshots/transcript.png
```

---

## 🧠 AI Summary

```text
screenshots/summary.png
```

---

## ⚙️ Processing

```text
screenshots/processing.png
```

---

# ⚙️ Installation Guide

## 1️⃣ Clone Repository

```bash
git clone https://github.com/DiVyansh-Gt/AI-Agent-Transcribing-and-Summarizing-Videos.git
```

```bash
cd AI-Agent-Transcribing-and-Summarizing-Videos
```

---

## 2️⃣ Create Virtual Environment

### Windows

```bash
python -m venv venv
```

Activate:

```bash
venv\Scripts\activate
```

---

### Linux / macOS

```bash
python3 -m venv venv

source venv/bin/activate
```

---

## 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

# 🔐 Environment Variables

Create a **.env** file in the project root.

```env
OPENAI_API_KEY=your_openai_api_key

HF_TOKEN=your_huggingface_token
```

> **Note:** If your implementation uses only local Whisper and BART models without API keys, you can omit these variables. Keep this section only if your code actually reads them.

---

# ▶️ Run Application

```bash
streamlit run app.py
```

The application will be available at:

```text
http://localhost:8501
```

---

# 🌍 Deployment

## Local Development

```text
http://localhost:8501
```

## Production

Deploy easily on:

- Streamlit Community Cloud
- Hugging Face Spaces
- Render
- Railway

- Railway

---

# 🔄 AI Processing Pipeline

The application follows a sequential AI pipeline that transforms raw video input into meaningful text summaries.

## Complete Workflow

```
User Uploads Video
        │
        ▼
Validate Video File
        │
        ▼
Extract Audio (FFmpeg)
        │
        ▼
Speech Recognition (OpenAI Whisper)
        │
        ▼
Generate Transcript
        │
        ▼
Split Long Transcript
        │
        ▼
Transformer Summarization (BART)
        │
        ▼
Generate Final Summary
        │
        ▼
Display Transcript & Summary
```

---

# 🎥 Video Processing Workflow

```
Video File

     │

     ▼

Upload Validation

     │

     ▼

Temporary Storage

     │

     ▼

FFmpeg Audio Extraction

     │

     ▼

WAV Audio Output
```

---

# 🗣️ Speech Recognition Workflow

```
Extracted Audio

        │

        ▼

OpenAI Whisper

        │

        ▼

Speech Detection

        │

        ▼

Language Understanding

        │

        ▼

Accurate Transcript
```

---

# 🧠 AI Summarization Workflow

```
Transcript

      │

      ▼

Chunk Processing

      │

      ▼

Hugging Face BART

      │

      ▼

Transformer Encoding

      │

      ▼

Summary Generation

      │

      ▼

Final Summary
```

---

# 📄 Output Generation Workflow

```
Transcript

      │

      ├──────────────┐

      ▼              ▼

Display Text     Generate Summary

      │              │

      └──────┬───────┘

             ▼

     Streamlit Interface
```

---

# ⚡ Performance Highlights

- 🚀 Fast Speech Recognition with OpenAI Whisper
- 🧠 Transformer-based Summarization using BART
- 🎧 Automatic Audio Extraction
- 🎥 End-to-End Video Processing
- 📄 High-quality Transcript Generation
- 📚 Context-aware AI Summaries
- ⚡ Lightweight Streamlit Interface
- 🔥 PyTorch Deep Learning Backend
- 🛠️ Modular AI Pipeline
- 📱 Beginner-friendly User Experience

---

# 🔒 Project Highlights

### Artificial Intelligence

- OpenAI Whisper Speech Recognition
- Hugging Face Transformers
- BART Large CNN
- Natural Language Processing
- Deep Learning Models

---

### Video Processing

- Automatic Audio Extraction
- FFmpeg Integration
- Temporary File Handling
- Long Video Support

---

### User Experience

- Interactive Streamlit Dashboard
- Simple Upload Interface
- Fast Processing
- Real-time Results

---

# 🚀 Future Enhancements

The project can be extended with the following features:

- 🌍 Multi-language Translation
- 🎙️ Speaker Identification
- 😊 Emotion Detection
- 📑 PDF Summary Export
- ☁️ Cloud Storage Integration
- 📧 Email Summary Delivery
- 🎥 YouTube URL Processing
- 🔊 Text-to-Speech Summary
- 📱 Mobile Responsive Interface
- 🤖 LLM-based Conversational Chat with Transcript

---

# 🤝 Contributing

Contributions are welcome!

To contribute:

1. Fork the repository

2. Create a feature branch

```bash
git checkout -b feature/NewFeature
```

3. Commit your changes

```bash
git commit -m "Add New Feature"
```

4. Push your branch

```bash
git push origin feature/NewFeature
```

5. Open a Pull Request

---

# 📄 License

This project is licensed under the **MIT License**.

You are free to use, modify, and distribute this project for educational, research, and personal learning purposes.

---

# 👨‍💻 Author

<div align="center">

# **Divyansh Gupta**

### AI • Machine Learning • Python Developer

Building Intelligent Applications using Artificial Intelligence, NLP & Deep Learning.

[![GitHub](https://img.shields.io/badge/GitHub-DiVyansh--Gt-black?style=for-the-badge&logo=github)](https://github.com/DiVyansh-Gt)

<br>

⭐ If you found this project helpful, don't forget to **Star** the repository.

Made with ❤️ using Python, Streamlit, OpenAI Whisper, Hugging Face Transformers & PyTorch.

</div>

---

# 💙 Support

If this project helped you,

⭐ Star this repository

🍴 Fork the repository

📢 Share it with others

Happy Coding 🚀
