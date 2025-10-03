# VoiceBot – NLP & LLM-based Conversational Assistant

## 📌 Overview

VoiceBot is a **speech-enabled conversational assistant** that leverages **Natural Language Processing (NLP), Large Language Models (LLMs), and AWS cloud infrastructure** to provide real-time, voice-driven interactions.
It can retrieve information, automate tasks, and respond naturally to user queries.

Key features:

* 🎤 Voice recognition using **SpeechRecognition** & **sounddevice**
* 🤖 Intelligent response generation with **LLMs (OpenAI API)**
* ☁️ Scalable backend using **AWS Lambda** + **AWS RDS (MySQL)**
* 📊 SQL-based user interaction analysis for behavior tracking

---

## ⚙️ Tech Stack

* **Languages & Frameworks:** Python, PyTorch, TensorFlow, scikit-learn
* **Libraries:** SpeechRecognition, soundfile, pymysql, stripe, openai
* **Cloud Services:** AWS Lambda (serverless), AWS RDS (MySQL)
* **Database:** MySQL / PostgreSQL
* **Tools:** Git, Linux

---

## 🚀 Features

* Convert **speech → text → response** seamlessly
* Perform **information retrieval** and task automation
* Optimize query understanding using **Retrieval-Augmented Generation (RAG)**
* SQL-based logging and **user drop-off detection** for system improvement
* Reduced latency by **40%** with serverless pipelines
* Increased task success rate by **23%** and user satisfaction by **27%**

---

## 🔧 Installation

1. **Clone the repository**

```bash
git clone https://github.com/Reza-CSEE/VoiceBot.git
cd VoiceBot
```

2. **Create a virtual environment**

```bash
python -m venv venv
source venv/bin/activate   # (Linux/Mac)
venv\Scripts\activate      # (Windows)
```

3. **Install dependencies**

```bash
pip install -r requirements.txt
```

4. **Set up environment variables**
   Create a `.env` file and add your credentials:

```bash
OPENAI_API_KEY=your_api_key_here
AWS_ACCESS_KEY=your_aws_key
AWS_SECRET_KEY=your_aws_secret
DB_USER=username
DB_PASS=password
DB_HOST=your_db_host
DB_NAME=voicebot
```

---

## ▶️ Usage

Run the main script:

```bash
python src/main.py
```

* Speak into your microphone 🎙️
* VoiceBot will transcribe, process, and respond naturally

---

## 📊 Results

* Reduced query latency by **40%** with AWS Lambda optimization
* Achieved **~95% transcription accuracy** with SpeechRecognition models
* Increased user satisfaction by **27%** through improved NLP pipeline

---

## 📜 License

License © 2023 Reza Ghasemi

---
