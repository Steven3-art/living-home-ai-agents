# living-home-ai-agents
Multi-AI agents on Cloud Run give life to IoT sensors with real personalities
# 🏠 Living Home - AI Agents for IoT

> **A home that listens, thinks, and saves lives through 6 AI agents with real personalities.**

Built for **Google Cloud Run Hackathon 2024** - AI Agents Category

---

## 🚀 Project Status

**🚧 UNDER ACTIVE DEVELOPMENT 🚧**

This project is being built over 21 days for the Cloud Run Hackathon.

- ✅ Phase 1: Google Cloud Setup (Complete)
- ✅ Phase 2: Hardware Assembly (Complete)
- 🚧 Phase 3: ESP32 Firmware (In Progress - Week 1)
- ⏳ Phase 4: Cloud Run Agents (Week 2)
- ⏳ Phase 5: Frontend (Week 3)
- ⏳ Phase 6: Video Demo (Week 3)

**Live Demo:** Coming soon (Week 3)  
**Video Demo:** Coming soon (Week 3)

---

## 🎯 What is Living Home?

Living Home transforms your house into a sentient space through **6 specialized AI agents**, each with unique personalities:

- 🌡️ **Thermie** (DHT22) - Climate scientist, anxious about calibration
- 🌫️ **Dusty** (GP2Y10) - Protective air quality guardian
- 👁️ **Radar** (LD2410) - Secret agent presence detector
- 💡 **Lux** (LDR + Relays) - Energy economist who controls real lamps
- 📱 **Texter** (SIM800) - SMS backup communication hero
- 💾 **Scribe** (SD Card) - Silent forensics archivist

---

## 🛠️ Tech Stack

**Cloud:**
- Google Cloud Run (deployment)
- Google Agent Development Kit (AI agents)
- Gemini API (LLM)
- Firestore (database)

**Hardware:**
- ESP32-WROOM
- DHT22, SHARP GP2Y10, HLK-LD2410, LDR
- 3× 5V Relays (control real lamps!)
- SIM800 GSM, SD Card

**Backend:**
- Python, FastAPI, MQTT, WebSocket, Docker

**Frontend:**
- React, TailwindCSS, Progressive Web App

---

## 📂 Repository Structure
```
living-home-ai-agents/
├── esp32/              # ESP32 firmware (C++)
├── backend/            # Cloud Run services (Python)
│   ├── agents/         # 6 ADK agents
│   ├── mqtt_broker/    # MQTT service
│   └── websocket/      # Real-time server
├── frontend/           # React PWA
├── docs/               # Documentation & diagrams
└── README.md
```

*(Folders will be populated progressively during development)*

---

## 🎥 Demo Video

Coming soon! (Week 3 of development)

---

## 📜 License

MIT License - See [LICENSE](LICENSE) file

---

## 🏆 Hackathon

Built for [Google Cloud Run Hackathon 2024](https://cloudrun.devpost.com)

**Category:** AI Agents  
**Developer:** [Belinga Belinga Steve]

---

## 📧 Contact

- 
- Email: stevebelingabelinga1@gmail.com

---

**⭐ Star this repo to follow development progress!**

*Last updated: [10/11/2025]*
