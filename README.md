# ⚡ GroqChat — AI Chatbot powered by Groq

A beautiful, fast, and feature-rich AI chatbot built with **Streamlit** and powered by **Groq Cloud**.

---

## ✨ Features

- 💬 **Text chat** — fast AI responses using Groq's LPU inference
- 🎙️ **Voice messages** — record your voice, auto-transcribed via Whisper
- 📎 **File uploads** — analyze PDFs, Word docs, Excel, CSVs, images, code files and more
- 🧠 **Multiple models** — Llama 3.3 70B, Mixtral, Gemma 2, and more
- 🎭 **Custom system prompt** — shape the AI's personality
- 🌡️ **Adjustable temperature & token limits**
- 📊 **Live message & token counters**
- 🗑️ **Clear conversation** anytime
- 🔒 **Secure** — API key stored as a secret, never exposed

---

## 📁 File Structure

```
groqchat/
├── app.py              # Main Streamlit application
├── requirements.txt    # Python dependencies
└── README.md           # This file
```

---

## 🚀 Deploying on Streamlit Cloud (Free)

1. Fork or clone this repository to your GitHub account
2. Go to [share.streamlit.io](https://share.streamlit.io) and sign in with GitHub
3. Click **"New app"** → select this repo → set `app.py` as the main file
4. Click **"Deploy"**
5. Once live, go to **Settings → Secrets** and add:
   ```
   GROQ_API_KEY = "gsk_xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
   ```
6. Save — the app restarts and is ready to use!

---

## 🔑 Getting a Free Groq API Key

1. Visit [console.groq.com](https://console.groq.com)
2. Sign up for a free account
3. Go to **API Keys** → click **"Create API Key"**
4. Copy the key (starts with `gsk_...`)
5. Paste it into your Streamlit secrets as shown above

---

## 📎 Supported File Types

| Category | Extensions |
|----------|-----------|
| 📄 Documents | `.pdf`, `.docx`, `.txt`, `.md` |
| 📊 Spreadsheets | `.xlsx`, `.xls`, `.csv` |
| 🖼️ Images | `.png`, `.jpg`, `.jpeg`, `.webp`, `.gif` |
| 💻 Code | `.py`, `.js`, `.ts`, `.html`, `.css`, `.json`, `.sql`, `.yaml` |

---

## 🧠 Available AI Models

| Model | Best For |
|-------|----------|
| `llama-3.3-70b-versatile` | Most capable, recommended for file analysis |
| `llama-3.1-8b-instant` | Fastest responses |
| `mixtral-8x7b-32768` | Long context tasks |
| `gemma2-9b-it` | Lightweight tasks |

---

## 🛠️ Run Locally (Optional)

```bash
pip install -r requirements.txt
streamlit run app.py
```

Then open [http://localhost:8501](http://localhost:8501) in your browser.

---

Built with ❤️ using [Streamlit](https://streamlit.io) and [Groq](https://groq.com)
