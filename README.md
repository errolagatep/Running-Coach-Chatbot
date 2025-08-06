# 🤖 Telegram AI Assistant with Media Handling (n8n Workflow)

This repository contains an **n8n** workflow that builds a multi-modal **AI-powered Telegram assistant**. The bot supports handling of **text**, **audio**, and **image** messages, and responds intelligently using a custom AI agent powered by OpenAI.


## 🚀 Features

- 📝 **Text Input**  
  Directly processed and sent to the AI Agent for intelligent response.

- 🎤 **Audio Input**  
  Audio files are fetched, transcribed via OpenAI Whisper, then analyzed and responded to.

- 🖼️ **Image Input**  
  Images are processed through an AI image analyzer before forming a response.

- 💡 **AI Agent with Tools**  
  Integrates multiple tools for enhanced AI capability:
  - OpenAI Chat Model
  - Memory via Zep
  - Web search via SerpAPI
  - Knowledge access via Wikipedia

- 📩 **Telegram Integration**  
  Fully integrated with Telegram Bot API to send and receive messages seamlessly.


## 🛠️ Workflow Overview

1. **Telegram Trigger**: Listens for incoming messages.
2. **Switch Node**: Routes input based on type: text, audio, or image.
3. **Input Processing**:
   - Text → Direct to AI
   - Audio → Transcription → AI
   - Image → Analysis → AI
4. **AI Agent**: Central logic for generating intelligent replies.
5. **Send Message**: Returns AI-generated response to user via Telegram.

## 📦 Requirements

- [n8n](https://n8n.io/)
- Telegram Bot Token
- OpenAI API Key
- SerpAPI Key (for web search)
- Zep Memory Server (optional)
- Wikipedia API (optional)


## 🧠 Use Cases

- AI-powered customer service bot  
- Media-aware Telegram assistant  
- Prototyping multi-modal AI tools  
- Educational demo for AI + automation

## 🙋‍♂️ Author

Created by - Errol Ace Agatep
Contributions welcome via issues or pull requests.
