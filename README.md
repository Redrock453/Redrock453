# REDROCK453

## Senior Tactical Systems Engineer · AI/LLM · FPV Defense Systems

> *"In contested environments, autonomy is resilience."*

---

### 🔧 Stack

| Domain | Tools |
|--------|-------|
| AI/LLM | DeepSeek · GPT-4o · Gemini · Groq · Claude · Ollama · OpenRouter · MiniMax |
| Vector DB | Qdrant · sentence-transformers · OpenAI embeddings |
| Backend | Python · TypeScript · **Hono** · Node.js · FastAPI · aiogram · Drizzle ORM |
| DevOps | Docker · systemd · Tailscale · WireGuard · PostgreSQL · BATMAN-adv |
| RF/SDR | HackRF · RTL-SDR · GNU Radio · LoRa (SX1262) |
| Coding | OpenCode (DeepSeek) · Claude Code |
| Drones | ГРІМ-5 · ArduPilot · RadioMaster TX12 · EdgeTX · MAVLink · CRSF · ELRS |

---

## 📂 All Projects

### 🎯 Flagship — 105-Server Orchestrator Ecosystem

| Project | Description |
|---------|-------------|
| **[orchestrator-gateway](https://github.com/Redrock453/orchestrator-gateway)** | ⚡ Hono API gateway. Unifies Qdrant + PostgreSQL + LLM fallback for fleet of Telegram bots. Port 4200 |
| **[105-infra](https://github.com/Redrock453/105-infra)** | 📋 Infrastructure docs, system prompt, config templates for 100.70.82.105 |

### 🤖 Bot Fleet (all routed through orchestrator-gateway)

| Project | Description |
|---------|-------------|
| **[vika_ok](https://github.com/Redrock453/vika_ok)** | 💙 Vika — Personal AI Agent. Multi-provider LLM (6 providers), RAG (Qdrant), voice, Telegram + Signal |
| **[ecc-tg-bot](https://github.com/Redrock453/ecc-tg-bot)** | 🧠 ECC Telegram Bot — aiogram interface routing through Hono gateway, Qdrant RAG |
| **[monitor-bot](https://github.com/Redrock453/monitor-bot)** | 🖥️ System health monitor. Telegram bot with /health, /status, systemd service |
| **[tg-media-bot](https://github.com/Redrock453/tg-media-bot)** | 🎬 Video → Audio → Transcription bot. YouTube/TikTok/Instagram, Groq + OpenAI Whisper |

### 🎯 FPV Drone Systems

| Project | Description |
|---------|-------------|
| **[grim-fpv-ai](https://github.com/Redrock453/grim-fpv-ai)** | AI platform for ГРІМ-5. ArduCopter SITL, FastAPI + WebSocket, PID auto-tuner, Multi-AI, YOLOv8 + ByteTrack, OpenVINS SLAM |
| **[grim-world-model](https://github.com/Redrock453/grim-world-model)** | World Model for FPV drones — trajectory prediction, collision avoidance, simulation |
| **[Tactical-HeadTrack-FPV](https://github.com/Redrock453/Tactical-HeadTrack-FPV)** | Отказоустойчивая система отслеживания головы для FPV. NRF24 + оптоволокно. Защита от РЭБ |
| **[beast-fpv-webapp](https://github.com/Redrock453/beast-fpv-webapp)** | Beast FPV web application |

### 🔐 Tactical & Defense Systems

| Project | Description |
|---------|-------------|
| **[tactical-fiber-network](https://github.com/Redrock453/tactical-fiber-network)** | SpiderLink — DAS/piezo sensors (11 target types), Zero-RF, BATMAN-adv mesh, OSPF, FastAPI C2 + UI |
| **[TacticalMesh](https://github.com/Redrock453/TacticalMesh)** | Decentralized tactical mesh network on LoRa. 5-10 km range, FHSS, AES-256-GCM, ATAK integration |
| **[BAS-SUPERGROK](https://github.com/Redrock453/BAS-SUPERGROK)** | BAS Tactical AI Systems — Multi-Agent Orchestration for Defense |
| **[heath-strike](https://github.com/Redrock453/heath-strike)** | Heath Strike — AI gimbal tracker (FPV tactical complex) |
| **[bas-antenna-tracker](https://github.com/Redrock453/bas-antenna-tracker)** | ESP32-based antenna tracker for UAV communications |
| **[bas-tactical-interface](https://github.com/Redrock453/bas-tactical-interface)** | Tactical UI for Android AMOLED devices |
| **[bas-kwgt-widget](https://github.com/Redrock453/bas-kwgt-widget)** | BAS Tactical Interface KWGT Widget |

### 🛡️ Security & OSINT

| Project | Description |
|---------|-------------|
| **[metasploit-mcp-server](https://github.com/Redrock453/metasploit-mcp-server)** | MCP server for Metasploit + Claude AI integration |
| **[osint-toolkit](https://github.com/Redrock453/osint-toolkit)** | Professional OSINT toolkit: SpiderFoot, Recon-ng, theHarvester, GitLeaks |
| **[AutoRecon](https://github.com/Redrock453/AutoRecon)** | Multi-threaded network recon tool. Parallel scanning, plugin system, CTF/pentesting |
| **[gsm-fake-points-guide](https://github.com/Redrock453/gsm-fake-points-guide)** | GSM security research: protocol analysis, rogue BTS detection, countermeasures |
| **[rf-anomaly-detector](https://github.com/Redrock453/rf-anomaly-detector)** | RF anomaly detector |

### 🤖 AI Agents & Systems

| Project | Description |
|---------|-------------|
| **[agenticSeek](https://github.com/Redrock453/agenticSeek)** | Fully Local Autonomous AI Agent — No APIs Required |
| **[openclaw](https://github.com/Redrock453/openclaw)** | Your own personal AI assistant. Any OS. Any Platform |
| **[carrie-ai-agent-ecosystem](https://github.com/Redrock453/carrie-ai-agent-ecosystem)** | CARRIE AI — Complete Security Agent Ecosystem (12+ Tools) |
| **[strategic-intelligence-ai](https://github.com/Redrock453/strategic-intelligence-ai)** | Document AI & OSINT automation. Multi-agent orchestration (LangChain, AutoGen), OCR, RAG |
| **[opencode-mobile](https://github.com/Redrock453/opencode-mobile)** | OpenCode AI coding agent for mobile (Termux). Full code with plugins, multi-LLM |

### 🌐 Network & Infrastructure

| Project | Description |
|---------|-------------|
| **[deployment-infrastructure](https://github.com/Redrock453/deployment-infrastructure)** | Deployment infrastructure |
| **[cluster-management-sdk](https://github.com/Redrock453/cluster-management-sdk)** | Cluster management SDK |
| **[coordination-hub](https://github.com/Redrock453/coordination-hub)** | Coordination hub |
| **[access-control-framework](https://github.com/Redrock453/access-control-framework)** | Access control framework |

### 📱 Mobile & Termux

| Project | Description |
|---------|-------------|
| **[opencode-config](https://github.com/Redrock453/opencode-config)** | OpenCode configuration |
| **[Tabletcodex](https://github.com/Redrock453/Tabletcodex)** | TabletCodex |
| **[termux-full-config](https://github.com/Redrock453/termux-full-config)** | Complete Termux configuration with remote management and security features |
| **[termux-gemini-system](https://github.com/Redrock453/termux-gemini-system)** | Complete Termux Gemini Session Management System |

### ⚙️ Configs & Scripts

| Project | Description |
|---------|-------------|
| **[setup-scripts](https://github.com/Redrock453/setup-scripts)** | Setup scripts |
| **[system-history](https://github.com/Redrock453/system-history)** | System history |
| **[ai-scripts](https://github.com/Redrock453/ai-scripts)** | AI scripts collection |
| **[pc-optimization-suite](https://github.com/Redrock453/pc-optimization-suite)** | PC optimization suite |

---

## 🧹 Cleanup Status

| Category | Result |
|----------|--------|
| 🗑️ Deleted | **30 repos** removed from GitHub |
| 🔄 Merged | archives consolidated into main repos |
| ✅ Remaining | **~50 active repos** |

> ✅ Cleanup complete 2026-05-17. Details: [CLEANUP_LIST.md](CLEANUP_LIST.md)

---

### 📊 GitHub Stats

- **50+ active repositories**
- **7 stars**
- **3 followers**

---

### 🛠 Tech Overview

**FPV/Drones:**
- ГРІМ-5 combat FPV drones
- RadioMaster TX12, EdgeTX
- ArduPilot, Betaflight, iNAV
- MAVLink, CRSF, ELRS

**RF/SDR:**
- HackRF One, RTL-SDR
- GNU Radio
- LoRa (SX1262)
- Antenna development

**AI/ML:**
- Python, TypeScript, Hono
- Qdrant (vector DB), PostgreSQL
- LangChain, AutoGen
- YOLOv8, OpenVINS

**DevOps:**
- Docker, systemd
- Tailscale VPN
- PostgreSQL
- CI/CD

---

*Last updated: May 18, 2026*
