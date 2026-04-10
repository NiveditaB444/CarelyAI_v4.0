# 🧠 Carely --- AI-Powered Emotional Wellness Companion

Carely is an AI-driven emotional wellness and safety companion designed
to support users through daily check-ins, mood tracking, and proactive
care. It combines conversational AI, memory systems, and safety
guardrails to provide empathetic support while ensuring responsible and
secure interactions.

------------------------------------------------------------------------

## 🚀 Features

### 💬 Conversational AI Companion

-   Chat-based interface powered by Groq LLaMA 3.3 70B
-   Context-aware, empathetic responses
-   Supports both text and voice input

### 🧠 Multi-Layer Memory System

-   Short-term memory: Recent conversations
-   Long-term memory: Vector embeddings (ChromaDB)
-   Episodic memory: Daily summaries
-   Structured memory: Profile, medications, events

### ❤️ Emotional & Sentiment Analysis

-   Mood detection and tracking
-   Trend visualization

### 🚨 Emergency Detection & Alerts

-   Detects critical symptoms
-   Sends alerts via Telegram

### 💊 Medication & Reminder System

-   Medication tracking and reminders
-   Logging via chat

### 🔒 Safety & Privacy

-   PII redaction
-   No medical advice enforcement

------------------------------------------------------------------------

## 🏗️ Tech Stack

-   Streamlit, FastAPI\
-   Groq SDK (LLaMA 3.3 70B)\
-   SQLite, SQLModel, ChromaDB\
-   APScheduler\
-   Telegram API

------------------------------------------------------------------------

## ⚙️ Setup

``` bash
git clone https://github.com/your-username/carely.git
cd carely
pip install -r requirements.txt
```

Create `.env`:

    GROQ_API_KEY=your_key
    TELEGRAM_BOT_TOKEN=your_token

Run:

``` bash
streamlit run main.py
```

------------------------------------------------------------------------

## 🛡️ Safety

-   No diagnosis or medication suggestions\
-   Emergency escalation enabled\
-   PII removed before storage

------------------------------------------------------------------------

## 👥 Contributors

-   Nivedita Bharti
-   Emmima Gnanaraj
-   Srivalli Lanka
-   Jasmitha Duvvuru
