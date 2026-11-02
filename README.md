# 🌸 YUNA — Your Local AI Companion with a Living Face

**YUNA v1.3 is here!** A voice-enabled desktop AI companion featuring animated Live2D characters, real agentic tools, customizable personalities, and local AI support.

[![Version](https://img.shields.io/badge/version-1.3-64b5f6?style=for-the-badge)](https://github.com/Dril-V000/yuna-AI/releases/tag/1.3v)
[![Platform](https://img.shields.io/badge/platform-Windows%2010%20%7C%2011-0078D6?style=for-the-badge&logo=windows)](https://www.microsoft.com/windows)
[![License](https://img.shields.io/badge/license-Proprietary-red?style=for-the-badge)](./LICENSE)
[![Price](https://img.shields.io/badge/price-from%20%2410-34d399?style=for-the-badge)](https://yunaai.online/)

**[🌐 Website](https://yunaai.online/) · [⬇️ Download v1.3](https://github.com/Dril-V000/yuna-AI/releases/tag/1.3v) · [💬 Discord](https://discord.gg/ARg6yujhdc) · [▶️ YouTube](https://www.youtube.com/@code7kjt)**

---

## ✨ What Is YUNA?

YUNA is a Windows desktop AI companion combining natural voice conversations, AI-powered responses, and animated Live2D characters.

Choose local AI with Ollama or connect a supported cloud AI provider using your own API credentials.

- 🛠️ **Agentic tools** — YUNA can search the live web, open links, and save notes directly on your PC.
- 🎙️ **Voice conversations** — speak naturally and hear YUNA respond.
- 🎭 **Live2D animation** — animated characters with blinking, lip-sync, and emotional expressions.
- 🧠 **Conversation memory** — up to 8,000 characters of rolling memory, plus conversation history.
- 🎨 **Character customization** — create personalities, prompts, and custom backgrounds.
- 📦 **Custom Live2D models** — upload compatible ZIP archives and custom thumbnails.
- 🧙 **MAJO** — a new character introduced in v1.2.
- 🌑 **Premium black theme** — refreshed interface and UI improvements.
- 🔊 **High-quality voice** — natural-sounding speech that talks out loud smoothly.
- ⚡ **GPU optional** — run supported local models on CPU, depending on your hardware.

## 🆕 What's New in v1.3?

| Feature | Description |
|---|---|
| **Agentic tools** | Search the live web, open links & websites, and save notes to local files directly from chat. |
| **Expressive Live2D** | YUNA's face now shows emotion based on what she says, alongside blinking and lip-sync. |
| **Smarter personality** | Instant answers in a warm, playful, to-the-point tone — no more "let me check…". |
| **High-quality voice** | Natural-sounding speech with seamless out-loud playback. |
| **Full customization** | Change background, voice, persona prompt, and upload your own custom Live2D model. |
| **Multi-character memory** | Improved memory handling so each character keeps its own context. |
| **Premium black theme** | Refined dark theme and interface refinements. |

**[View the v1.3 release](https://github.com/Dril-V000/yuna-AI/releases/tag/1.3v)**

---

## 🎬 Demo

Watch YUNA in action:

**[▶ Watch the YUNA Demo](https://www.youtube.com/watch?v=5nRFN7Nl7O4)**

---

## 🖥️ System Requirements

| Component | Minimum | Recommended |
|---|---|---|
| Operating system | Windows 10 64-bit | Windows 11 |
| CPU | Intel Core i5 6th gen or AMD Ryzen 5 1600 | Modern Intel Core i7 or AMD Ryzen 7 |
| RAM | 8 GB | 16 GB or more |
| Storage | Allow several GB for the app and model | 10 GB free |
| GPU | Not required | Optional |

Actual performance depends on your hardware, selected AI model, and voice configuration. Larger models generally require more RAM and processing power.

## 📥 Installation

Getting started with YUNA is simple. The app guides you through the setup process automatically.

1. **Download YUNA** from the [official v1.3 release page](https://github.com/Dril-V000/yuna-AI/releases/tag/1.3v).
2. **Extract the downloaded archive** to a folder on your PC.
3. **Launch `YUNA.exe`**.
4. **Enter your license key** to activate YUNA.
5. **Install Ollama:** If Ollama is not installed, YUNA automatically opens the official Ollama download page so you can install it.
6. **Choose your AI model:** YUNA displays a list of available local AI models.
7. **Download your model:** Select a model, and YUNA downloads it automatically.
8. **Start chatting!** Enjoy voice conversations with your animated AI companion.

### 🤖 Recommended Local AI Models

| Model | Best For |
|---|---|
| `qwen2.5:3b` | Lower-memory PCs and faster responses |
| `qwen2.5:7b` | A balance of response quality and performance |
| `llama3.1:8b` | General conversation and reasoning |
| `gemma2:9b` | Writing and conversational tasks |

**Tip:** If your PC has limited RAM or a weaker CPU, start with a smaller model such as `qwen2.5:3b`. Larger models generally require more resources and may respond more slowly.

**Note:** An internet connection is required during initial setup to download Ollama, the selected AI model, and any required components. Once everything is installed, local AI conversations can work offline, provided all required local services are available.

## 🎭 Characters

| Character | Description | Availability |
|---|---|---|
| 🌸 Yuna | Main companion | Built-in |
| 🌿 Haru | Alternative companion | Built-in |
| 🧙 MAJO | New character in v1.2 | Built-in |
| ✨ Custom characters | Your own name, personality, and prompt | Supported |
| 🎭 Custom Live2D models | Import compatible models and thumbnails | Supported in v1.2+ |

### Importing a Custom Live2D Model

1. Open **Character Manager**.
2. Locate the Live2D model or skin options.
3. Upload a compatible model ZIP archive.
4. Optionally upload a thumbnail image.
5. Save the character and verify that the model displays correctly.

Not every Live2D model is guaranteed to work. Compatibility depends on its structure, assets, and requirements. Ensure you have permission to use any model you import.

## 🤖 AI Providers

YUNA supports local AI through Ollama and supported API-based providers.

| Provider | Connection | Requirements |
|---|---|---|
| Ollama | Local | Compatible model installed on your computer |
| OpenAI | Cloud | Your own API credentials |
| Anthropic | Cloud | Your own API credentials |
| DeepSeek | Cloud | Your own API credentials |
| Google Gemini | Cloud | Your own API credentials |
| Groq | Cloud | Your own API credentials |

Provider availability depends on the application's current configuration and API compatibility. Cloud providers may charge separately for usage.

## 🔒 Privacy

YUNA supports local AI, but privacy depends on your selected configuration.

- **Local Ollama mode:** prompts are processed by the local model on your computer.
- **Cloud API mode:** prompts and associated request data are sent to the provider you select.
- **Agentic tools:** web searches and file operations are performed locally or via your chosen search provider.
- **Initial setup:** internet access may be needed for activation and model downloads.
- **Offline use:** local conversations can work offline once required models and services are installed.
- **No YUNA subscription:** purchasing a license does not require recurring YUNA payments.

Cloud AI usage fees, where applicable, are separate from the YUNA purchase price.

## 💰 Pricing

YUNA uses a one-time payment model.

| Plan | Price | Includes |
|---|---:|---|
| **Basic** | **$10 USD** | App access, voice, Live2D, agentic tools, supported AI providers, memory, and customization |
| **Pro** | **$15 USD** | Basic features plus direct support and setup assistance |

No recurring YUNA subscription or renewal fee. Cloud AI API fees, if applicable, are separate.

**[Visit the official website to purchase YUNA](https://yunaai.online/)**

Follow the website's current payment instructions. License keys are delivered after payment verification.

## ❓ FAQ

### Does YUNA require a GPU?

No. A dedicated GPU is optional. Performance depends on the selected model, CPU, available RAM, and compatible hardware acceleration.

### Can I use my own AI model?

YUNA supports model selection through Ollama and supported API providers. Individual models have different resource and compatibility requirements.

### Can I create my own characters?

Yes. You can customize character names, personalities, prompts, and other supported settings.

### Can I import custom Live2D models?

Yes. v1.3 supports uploading compatible model ZIP archives and thumbnails.

### Does YUNA work offline?

Local AI can work offline once the required models and dependencies are available. Initial activation, downloads, and cloud providers may require internet access.

### Does YUNA support macOS or Linux?

The current release targets Windows 10 and Windows 11. Check the official website for future platform announcements.

### Need help?

Visit the [Discord community](https://discord.gg/ARg6yujhdc). When reporting an issue, include relevant error messages and your system specifications. Never share your license key or API secrets publicly.

---

## 🔗 Links

- **Website:** https://yunaai.online/
- **Latest release:** https://github.com/Dril-V000/yuna-AI/releases/tag/1.3v
- **Discord:** https://discord.gg/ARg6yujhdc
- **YouTube:** https://www.youtube.com/@code7kjt

---

**YUNA — Your local AI companion with a living face.**

Built by **CODE-7**.

Copyright © 2026 CODE-7. All rights reserved.

YUNA is proprietary software. Unauthorized redistribution is prohibited.
