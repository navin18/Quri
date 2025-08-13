# Quri

**Quri** is a full-stack AI-powered voice interface designed for effortless newsletter consumption.  
It allows users to **listen, take notes, search the web, and interact entirely through voice commands**, enabling a completely hands-free experience.

This repository aggregates the core components of Quri, including the iOS frontend, email processing backend, and real-time voice agent.

---

## 🎥 Demo

▶️ [Watch the Quri Demo Video](https://www.loom.com/share/0f2687732df34092a5f51b9f40c9779a?sid=36bef13f-d3d7-4658-942a-9f3f34536710)  
Experience real-time voice interaction with newsletters, note-taking, and app navigation.

---

## 🔗 Project Structure

| Module | Description |
|--------|-------------|
| [Frontend – Swift iOS App](https://github.com/navin18/quri-frontend) | iOS app built with Swift and SwiftUI for voice-based navigation and interaction. |
| [Backend – Email Processing Service](https://github.com/navin18/quri-backend) | FastAPI service that parses emails, extracts newsletters, and prepares content for AI interaction. |
| [Backend – Real-Time Voice Agent](https://github.com/navin18/quri-voice) | Handles LLM integration, WebSocket communication, and real-time voice responses using TTS/STT pipelines. |

---

## 🚀 Tech Stack

- **Frontend:** SwiftUI (iOS), Core Data, Keychain for secure storage  
- **Backend:** FastAPI (Python), WebSockets, WebRTC  
- **Database:** Supabase (PostgreSQL)  
- **Authentication:** Google OAuth, Supabase  
- **Audio Pipeline:** AVFoundation, AVAudioEngine, custom WebSocket channels for live audio I/O with dynamic STT and TTS integration  
- **AI/ML:** Hume TTS, OpenAI GPT models (text generation, transcription)  
- **Integrations:** Gmail API, BeautifulSoup for inbox access, email actions, and content parsing  

---

## 📌 Key Features

- Hands-free newsletter listening with natural voice commands  
- Real-time AI search and interaction within newsletters  
- Automatic note-taking and content organization  
- Email parsing and smart newsletter extraction  
- Secure, fast, and privacy-focused design  

---

## 📄 License

This project is licensed under the MIT License. See the LICENSE file for details.
