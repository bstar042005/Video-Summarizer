# AI Video Summarizer

🔗 **Live Demo:** https://video-summarizer-qjnjtkgtzm6ydfe28ccp6t.streamlit.app/

AI Video Summarizer is an AI-powered web application that automatically converts video content into concise, structured summaries. The application extracts audio from uploaded videos, transcribes speech using OpenAI Whisper, and generates high-quality summaries using Groq's Llama 3.3 70B Versatile model.

This enables users to quickly understand lengthy videos without watching them in full.

---

## Features

- Upload video files for summarization
- Automatic audio extraction using MoviePy
- Speech-to-text transcription using OpenAI Whisper
- AI-generated summaries using Groq Llama 3.3 70B Versatile
- Structured summaries with key points and insights
- Fast and efficient processing pipeline
- Simple and intuitive Streamlit interface
- Download generated summaries
- Supports long-form video content

---

## Tech Stack

### Frontend
- Streamlit

### Backend
- Python

### AI & Machine Learning
- OpenAI Whisper
- Groq API
- Llama 3.3 70B Versatile
- Natural Language Processing (NLP)

### Video Processing
- MoviePy
- FFmpeg

### Development Tools
- Git
- GitHub

---

## Project Structure

```text
Video-Summarizer/
│
├── input/                  # Uploaded videos
├── output/                 # Generated audio and summaries
├── .env.example            # Environment variable template
├── app.py                  # Streamlit application
├── main.py                 # Video processing pipeline
├── requirements.txt        # Python dependencies
├── .gitignore
└── README.md
```

---

## Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/bstar042005/Video-Summarizer.git
cd Video-Summarizer
```

### 2️⃣ Create a Virtual Environment

```bash
python -m venv .venv
```

### 3️⃣ Activate the Virtual Environment

#### Windows

```bash
.venv\Scripts\activate
```

#### macOS / Linux

```bash
source .venv/bin/activate
```

### 4️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 5️⃣ Install FFmpeg

Download and install FFmpeg, then add it to your system PATH.

Verify the installation:

```bash
ffmpeg -version
```

### 6️⃣ Configure Environment Variables

Create a `.env` file in the project root.

```env
GROQ_API_KEY=your_groq_api_key
```

### 7️⃣ Run the Application

```bash
streamlit run app.py
```

---

## How It Works

```text
Upload Video
      │
      ▼
Extract Audio (MoviePy)
      │
      ▼
Speech-to-Text (OpenAI Whisper)
      │
      ▼
Generate Summary (Groq Llama 3.3)
      │
      ▼
Display Structured Summary
```

## Support

If you found this project useful, consider giving it a **⭐ Star** on GitHub.

Contributions, suggestions, and feedback are always welcome!

---
