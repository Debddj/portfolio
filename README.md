# Debnil Dey — Personal Portfolio & Agentic Systems Showcase

> High-performance, dark-mode developer portfolio showcasing autonomous multi-agent AI systems, real-time ML infrastructure, computer vision pipelines, and interactive WebGL experiences.

![Portfolio Status](https://img.shields.io/badge/System-Online-4FD1C5?style=for-the-badge&logo=statuspage)
![License](https://img.shields.io/badge/License-MIT-FF9E2C?style=for-the-badge)

---

## ⚡ Overview

This repository contains the source code for my personal developer portfolio site — engineered with a terminal-inspired, dark-mode aesthetic featuring live clock/uptime telemetry, custom CSS animations, smooth scroll reveals, and a zero-dependency responsive architecture.

- **Developer**: Debnil Dey (B.Tech CSE - AI @ IEM Kolkata)
- **Live Demo**: [debddj.github.io/portfolio](https://debddj.github.io/portfolio) *(or debddj.github.io)*
- **GitHub Profile**: [@Debddj](https://github.com/Debddj)
- **LinkedIn**: [debnil-dey](https://www.linkedin.com/in/debnil-dey-359a25393/)

---

## 🛠️ Deployed Systems & Projects Showcased

### 🛡️ Flagship Project: Aegis
An autonomous multi-agent system for ML infrastructure reliability. When a production model fails, a 4-agent pipeline automatically triages and remediates the incident:
1. **Agent 01 (Sentry)**: Detects production drift & incident triggers.
2. **Agent 02 (Sleuth)**: Traces root cause across logs and metrics.
3. **Agent 03 (Medic)**: Applies auto-remediation scripts.
4. **Agent 04 (Scribe)**: Generates detailed incident postmortems.
- *Tech*: Google ADK, Gemini, FastAPI, React/TS, ChromaDB, gRPC, Docker
- 🔗 [Live Demo](https://aegis-dun-rho.vercel.app) | 🔗 [Repository](https://github.com/Debddj/Aegis)

### 📡 Other Highlighted Projects
- **Sentinel**: Real-time ML observability platform running PSI, KS, CUSUM & Isolation Forest engines. ([Repo](https://github.com/Debddj/Sentinel))
- **Sanctum**: Real-time AR VFX engine using MediaPipe, PyTorch, custom CUDA kernels, TensorRT & Three.js. ([Repo](https://github.com/Debddj/Sanctum))
- **Stadium Copilot**: GenAI operations layer for FIFA World Cup 2026 with 12-language grounded RAG & accessibility features. ([Live Demo](https://stadium-copilot-ruby.vercel.app) | [Repo](https://github.com/Debddj/stadium-copilot))
- **MagnoGlove Pro**: Browser-native 3D AR hand tracking with electromagnetic physics simulation via MediaPipe & Three.js. ([Live Demo](https://debddj.github.io/MagnoGlove-Demo/) | [Repo](https://github.com/Debddj/MagnoGlove-Demo))
- **ChronoSpatial Engine**: Real-time video stream telemetry scoring risk frame-by-frame. ([Repo](https://github.com/Debddj/ChronoSpatial-Engine))
- **Aura Pitch 2026**: Multi-Agent RL tactical football intelligence on a 3D pitch. ([Repo](https://github.com/Debddj/Aura-Pitch-2026))
- **LiverInsight CDSS**: Clinical decision support system (91% recall XGBoost + SHAP). ([Repo](https://github.com/Debddj/LiverInsight-CDSS-Clinical-Decision-Support-System-))

---

## 🎨 Tech Stack & Design System

- **Frontend**: Semantic HTML5, Modern Vanilla CSS (Variables, Flexbox, CSS Grid, Keyframe Animations), Vanilla JavaScript (IntersectionObserver, Live IST Clock, Session Uptime Telemetry)
- **Typography**: Space Grotesk (Headings), JetBrains Mono (Terminal/Code), Inter (Body)
- **Palette**: Dark Mode Void (`#0A0D12`), Amber Accent (`#FF9E2C`), Teal Accent (`#4FD1C5`)
- **Performance**: Zero build step required, 100% lightweight & mobile-responsive.

---

## 🚀 Quick Start (Local Setup)

To run this portfolio locally:

```bash
# Clone the repository
git clone https://github.com/Debddj/portfolio.git

# Navigate into project folder
cd portfolio

# Open directly in browser or launch with Python HTTP server
python -m http.server 8000
```
Then visit `http://localhost:8000`.

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.
