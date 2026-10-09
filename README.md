# BridgeAI — Digital Literacy Tutor & Scam Detector

> **Hack-the-Campus: AI for Good**  
> AI-powered digital literacy tutor and scam detector for first-time smartphone and internet users in underserved communities (targeting Africa and South Asia). Powered by **Groq**.

---

## 🌟 Overview

Millions of first-time smartphone users and underserved communities lack access to safe, plain-language guidance on navigating the internet, using mobile money, and protecting themselves against online financial predators.

**BridgeAI** bridges this digital divide with:
- **No jargon, warm analogies** grounded in everyday life (marketplaces, farming, buses, family).
- **Adaptive learning**: Automatically adjusts explanation complexity based on user experience (`Beginner` vs `Intermediate`).
- **Multi-language support**: English, Swahili (Kiswahili), Hindi (हिन्दी), French (Français), and West African Pidgin (Naija).
- **Instant scam detection**: Paste suspicious SMS, WhatsApp messages, or links to get plain-language risk analysis, warning signs, and action steps.
- **Offline 5-step quick lessons**: Practical step-by-step guides for sending first emails, mobile money safety (M-Pesa, MoMo), WhatsApp verification, and searching for legitimate jobs.
- **Audio accessibility (Read Aloud)**: Native Text-to-Speech support for learners with low reading literacy.

---

## ⚡ Powered by Groq

BridgeAI connects to **Groq** for high-speed, low-latency AI inference:
- **Dynamic Model Auto-Discovery**: Automatically queries `https://api.groq.com/openai/v1/models` on startup to detect and select the best available live chat model (excluding audio and guardrail models).
- **Direct OpenAI-Compatible Schema**: Zero external server dependencies; client-side direct API interaction.
- **Raw Transparent Error Reporting**: Real-time server diagnostics if keys or network limits are exceeded.

---

## 🚀 Getting Started

### 1. Run Locally
BridgeAI is a single, zero-dependency HTML file (`index.html`).

Open `index.html` directly in any web browser, or serve it using Python / Node:

```bash
# Python
python -m http.server 8080

# Or Node.js
npx serve .
```

### 2. Enter Your Groq API Key
1. Get a free API key at [console.groq.com](https://console.groq.com/keys).
2. Enter your key in the setup dialog.
3. BridgeAI will auto-detect the live available model and start learning!

---

## 🛡️ Key Features

| Feature | Description |
|---|---|
| 🎓 **Learn Digital Skills** | Interactive AI tutor answering questions about email, WhatsApp, mobile money, and internet safety. |
| 🚨 **Scam Detector** | Analyzes suspicious messages with clear risk verdict badges, red flags, and exact protective steps. |
| 🌍 **Language Switcher** | Multi-lingual switch for English, Kiswahili, Hindi, French, and Pidgin. |
| 📋 **Quick Lessons** | 5 offline interactive guides covering SMS scams, first email creation, WhatsApp 2FA, mobile money PIN safety, and online job hunting. |
| 🔊 **Read Aloud (TTS)** | Text-to-speech support for low-literacy users. |

---

## 📄 License
MIT License. Built for **Hack-the-Campus — AI for Good**.
