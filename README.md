<div align="center">

# 🏛️ CivicSentinel

### AI-Powered Civic Conflict Mediation Platform

*Resolving multidimensional urban infrastructure disputes through AI diplomacy, stakeholder mapping, and community consensus*

[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](LICENSE)
[![React](https://img.shields.io/badge/React-19-61DAFB?logo=react)](https://react.dev)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.8-3178C6?logo=typescript)](https://www.typescriptlang.org)
[![Gemini AI](https://img.shields.io/badge/Powered%20by-Gemini%20AI-4285F4?logo=google)](https://ai.google.dev)

</div>

---

## 📖 Overview

**CivicSentinel** is an intelligent civic mediation platform that harnesses the power of **Google Gemini AI** to resolve complex urban infrastructure conflicts. From flooded streets and drainage disputes to wildlife corridor encroachments and telecom tower siting conflicts — CivicSentimal maps all affected stakeholders, generates binding mediation treaties, and produces actionable consensus roadmaps in real time.

The platform supports **bilingual operation** (English & Hindi / Devanagari script) and is designed to serve municipalities, civic bodies, urban planners, and community representatives.

---

## ✨ Key Features

| Feature | Description |
|---|---|
| 🧠 **AI Vision Analysis** | Geospatial hazard detection from uploaded photos with bounding-box object recognition and severity scoring |
| 🗺️ **Interactive Hazard Map** | Leaflet.js-powered live map visualizing all reported civic conflict zones |
| 👥 **Stakeholder Mapping Engine** | Sentiment, influence, and concern matrices for all community groups |
| 🤝 **AI Diplomat Agent** | Generates legally-formatted mediation treaties with phase-by-phase implementation timelines |
| 📊 **Consensus Analytics Dashboard** | Real-time satisfaction indexes, telemetry, and compromise balance tracking |
| 🗳️ **Community Consensus Roadmap** | Voteable, phased action plans with ratification tracking |
| 🌐 **Multilingual Support** | Full UI and treaty translation into Hindi (Devanagari script) |
| 📁 **Report History** | Persistent localStorage-backed hazard report management (active / pending / resolved) |

---

## 🛠️ Tech Stack

- **Frontend**: React 19, TypeScript 5.8, Vite 6
- **Styling**: Tailwind CSS v4
- **Animation**: Motion (Framer Motion)
- **Icons**: Lucide React
- **Maps**: Leaflet.js
- **Charts**: Chart.js
- **Backend**: Express.js + tsx (Node.js dev server)
- **AI**: Google Gemini AI (`@google/genai`)

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or higher)
- A [Google Gemini API Key](https://aistudio.google.com/app/apikey)

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/squirrelk6755-ctrl/civicsentimal.git
cd civicsentimal

# 2. Install dependencies
npm install

# 3. Set up environment variables
cp .env.example .env.local
# Open .env.local and add your Gemini API key:
# GEMINI_API_KEY=your_api_key_here

# 4. Start the development server
npm run dev
```

The app will be available at `http://localhost:3000` (or the port printed in the terminal).

---

## 📂 Project Structure

```
civicsentimal/
├── src/
│   ├── App.tsx                      # Main application & all UI sections
│   ├── data.ts                      # Seed reports, stakeholders & mock data
│   ├── types.ts                     # TypeScript interfaces & types
│   ├── main.tsx                     # React entry point
│   ├── index.css                    # Global styles
│   └── components/
│       ├── AnalyticsDashboard.tsx   # Consensus analytics & charts
│       ├── InteractiveHazardMap.tsx # Leaflet map component
│       └── ImpactScalability.tsx   # Impact & scalability section
├── server.ts                        # Express backend (API proxy for Gemini)
├── index.html                       # HTML entry point
├── vite.config.ts                   # Vite bundler config
├── tsconfig.json                    # TypeScript config
├── .env.example                     # Environment variable template
└── package.json
```

---

## 🔑 Environment Variables

Copy `.env.example` to `.env.local` and fill in your values:

```env
GEMINI_API_KEY=your_google_gemini_api_key_here
```

> ⚠️ **Never commit your `.env.local` file.** It is already excluded via `.gitignore`.

---

## 📜 Available Scripts

| Command | Description |
|---|---|
| `npm run dev` | Start development server (frontend + backend) |
| `npm run build` | Build production bundle |
| `npm run start` | Run the production build |
| `npm run preview` | Preview the production build locally |
| `npm run lint` | Run TypeScript type checks |

---

## 🌍 Supported Conflict Categories

- 🚗 **Transport** — Road damage, detours, transit corridor disputes
- 🛡️ **Safety** — Street lighting, pedestrian hazards, security zones
- ⚡ **Energy** — Telecom towers, solar infrastructure siting
- 🌿 **Environmental** — Wildlife corridors, waste dumping, drainage disputes
- 🏗️ **Infrastructure** — Flooding, drainage, construction conflicts

---

## 🤖 How the AI Works

1. **Ingest** — User submits a hazard report with title, location, category, urgency, and an optional photo
2. **Vision Analysis** — Gemini AI analyzes the photo for physical conflict vectors and generates structured hazard data
3. **Stakeholder Mapping** — The system models sentiment and influence across all affected community groups
4. **AI Diplomat** — An LLM agent compiles a formal mediation treaty with phased timelines and legal safeguards
5. **Consensus Roadmap** — Community members vote on each phase; the Consensus Index rises as groups ratify
6. **Analytics** — Real-time dashboards surface satisfaction trends, cost savings, and resolution timelines

---

## 📄 License

This project is licensed under the [Apache 2.0 License](LICENSE).

---

<div align="center">
Built with ❤️ using <a href="https://ai.google.dev">Google Gemini AI</a>
</div>
