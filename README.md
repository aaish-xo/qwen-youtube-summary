# 🎥 Qwen YouTube Transcript Summarizer

This notebook extracts transcripts from YouTube videos, restores punctuation, and generates summaries using the **Qwen-1.8B Chat** model from Alibaba, running through Hugging Face Transformers.

---

## 🧠 What It Does

- 📼 Extracts YouTube transcript (if available)
- ✍️ Adds punctuation using [`rpunct`](https://github.com/babthamotharan/rpunct)
- 🤖 Generates a summary using Qwen via Hugging Face
- ✅ Works in **Google Colab** or **locally**

---

## ⚠️ Important Notes

> **YouTube may rate-limit or block transcript requests when running in Colab or other cloud environments.**

If this happens:
- You’ll get an error like: `RequestBlocked`
- Workaround: **run the notebook locally** or **upload a transcript file manually**

---

## 🚀 Usage Instructions

### 1. Clone or open the notebook
Open the notebook directly in Google Colab:

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/your-username/qwen-youtube-summary/blob/main/qwen_youtube_summary.ipynb)


