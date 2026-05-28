````md
# AI Meeting Assistant – Multilingual Meeting Summarization & Conversational RAG System

AI Meeting Assistant is an end-to-end Generative AI application that transcribes, summarizes, and enables conversational interaction with meeting content from audio, video, and YouTube sources using Retrieval-Augmented Generation (RAG).

---

# Features

- Upload audio/video meeting recordings
- Process YouTube meeting links
- Automatic speech-to-text transcription using Whisper AI
- Multilingual support (English, Hindi, Hinglish)
- AI-generated meeting summaries
- Conversational Q&A over meeting content
- Retrieval-Augmented Generation (RAG) pipeline
- Semantic search using vector embeddings
- Action item and key decision extraction
- PDF/TXT report generation
- Interactive Streamlit dashboard

---

# Tech Stack

## Languages
- Python

## AI/ML & GenAI
- Whisper AI
- LangChain LCEL
- HuggingFace Embeddings
- Mistral AI
- Retrieval-Augmented Generation (RAG)

## Frameworks & Tools
- Streamlit
- ChromaDB
- FastAPI
- YouTube Transcript API
- FFmpeg

## Data Processing
- Pandas
- NumPy

---

# System Architecture

1. User uploads meeting audio/video or YouTube URL
2. Audio extraction and preprocessing
3. Whisper AI transcribes speech into text
4. Text chunks are embedded using HuggingFace embeddings
5. Embeddings stored in ChromaDB vector database
6. LangChain RAG pipeline retrieves relevant context
7. Mistral AI generates summaries and conversational responses
8. Streamlit dashboard displays outputs interactively

---

# Project Structure

```bash
AI-Meeting-Assistant/
│
├── app.py
├── main.py
├── Requirements.txt
│
├── core/
│   ├── extractor.py
│   ├── transcriber.py
│   ├── summarizer.py
│   ├── rag_engine.py
│   └── vector_store.py
│
├── utils/
│   └── audio_processor.py
│
└── README.md
````

---

# Installation

## Clone Repository

```bash
git clone https://github.com/KaushikDasarii/AI-Meeting-Assistant.git

cd AI-Meeting-Assistant
```

---

# Create Virtual Environment

## Windows

```bash
python -m venv venv

venv\Scripts\activate
```

## Linux / Mac

```bash
python3 -m venv venv

source venv/bin/activate
```

---

# Install Dependencies

```bash
pip install -r Requirements.txt
```

---

# Run Application

```bash
streamlit run app.py
```

---

# Future Enhancements

* Speaker diarization
* Real-time meeting transcription
* Cloud deployment
* Team collaboration workspace
* Multi-document conversational memory
* AI-generated meeting analytics dashboard

---

# Skills Demonstrated

* Generative AI
* Large Language Models (LLMs)
* Retrieval-Augmented Generation (RAG)
* NLP & Speech Processing
* Vector Databases
* Prompt Engineering
* AI System Design
* Streamlit Deployment
* FastAPI Backend Development

---

# Author

## Kaushik Dasari

### LinkedIn

https://www.linkedin.com/in/dasari-hari-venkat-kaushik-5061a6342

### GitHub

https://github.com/KaushikDasarii

```
```
