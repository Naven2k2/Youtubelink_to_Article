# 🎬 YouTube → Article Generator

A Generative AI project that converts YouTube videos into:

- ⚡ Short summaries  
- 📄 Professional articles  
- 🌐 Ready-to-use HTML webpages  

---

## 📌 Overview

This project extracts transcripts from YouTube videos and uses a Large Language Model (LLM) to transform them into structured, high-quality articles and webpage content.

It is designed for **content repurposing**, helping turn video content into blogs, documentation, or learning materials.

---

## 🚀 Live Demo

👉 https://huggingface.co/spaces/Naveen123hh/yt_article_generator

---

## 🚀 Features

- 🎥 Extract YouTube transcripts automatically  
- 🧠 Generate structured technical articles  
- ⚡ Handle long videos using recursive summarization  
- 🌐 Generate HTML, CSS, and JavaScript files  
- 📦 Export complete website as a ZIP file  
- 🔐 Secure API key handling using `.env`  

---

## 🧠 Tech Stack

- Python 🐍
- LangChain
- Groq (LLM)
- YouTube Transcript API
- dotenv
- Streamlit

---

## 📁 Project Structure

```text
yt_article_generator/
│
├── app.py
├── requirements.txt
├── .env
├── article_generator.py
├── transcript_utils.py
├── templates/
└── README.md
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/yt_article_generator.git
cd yt_article_generator
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

---

## 🔑 Environment Variables

Create a `.env` file and add your API key:

```env
GROQ_API_KEY=your_api_key_here
```

---

## 📌 How It Works

1. User provides a YouTube video link  
2. Transcript is extracted automatically  
3. LLM processes and summarizes the content  
4. Article and webpage content are generated  
5. User can download generated files  

---

## 📊 Applications

- Blog generation  
- Educational content creation  
- Technical documentation  
- Video-to-text conversion  
- Content repurposing  

---

## 📌 Future Improvements

- 🎙️ Multi-language transcript support  
- 🎨 Better webpage templates  
- 🤖 More advanced LLM integration  
- 📱 Mobile-friendly UI  
- ☁️ Cloud database integration  

---

## 👨‍💻 Author

### Mothe Naveen

AI & Machine Learning Enthusiast passionate about Generative AI, NLP, and real-world AI applications.
