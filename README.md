# 🌐 Social Media Content Generator

A clean, modern, and professional README + Architecture documentation for your Gradio-based Social Media Content Generation App.

---

## 📘 Overview

The **Social Media Content Generator** is a lightweight, easy-to-deploy Gradio application powered by **OpenAI's GPT models**. It allows brands, marketers, and creators to instantly generate:

* Engaging social media posts
* 7-day content plans
* Platform-specific captions
* Hashtag sets, hooks, CTAs, and more

This tool helps streamline everyday content creation workflows while maintaining high-quality outputs.

---

## ✨ Features

### ✔️ Generate Post

* Catchy hooks
* Multi-line captions
* Relevant hashtags
* CTAs tailored to brand goals

### ✔️ 7-Day Content Plan

* Day-wise breakdown
* Format suggestions (Reel/Carousel/Post/Story)
* Short description for each day

### ✔️ Modern Gradio UI

* Tab-based navigation
* Clean and responsive layout

---


## ⚙️ Prerequisites

* Python **3.8+**
* OpenAI API Key
* Required packages:

  ```bash
  pip install gradio openai pandas numpy scikit-learn
  ```

---

## 🚀 Setup & Run

### 1. Set OpenAI Key

**Windows PowerShell:**

```powershell
setx OPENAI_API_KEY "sk-XXXX"
$env:OPENAI_API_KEY = "sk-XXXX"
```

**Linux / macOS:**

```bash
export OPENAI_API_KEY="sk-XXXX"
```

### 2. Run Application

```bash
python app.py
```

Gradio will launch at:

```
http://127.0.0.1:7860/
```

If `share=True` is enabled, you’ll also receive a **public URL**.

---

## 🧠 How It Works

1. User submits form (brand, platform, tone, goal…)
2. Gradio passes inputs into Python functions
3. Functions call OpenAI Chat Completions API
4. GPT model returns structured content
5. Output is displayed in the UI


