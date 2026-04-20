# Triadar — AI-Powered Clinical Trial Intelligence

<p align="center">
  <img src="https://img.shields.io/badge/Type-Single--page%20App-blue?style=for-the-badge" alt="Type">
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License">
  <img src="https://img.shields.io/badge/AI-Groq%7CGemini%7CCerebras%7COrangeRouter-orange?style=for-the-badge" alt="AI Providers">
</p>

> **Search, analyze, and discover clinical trials in seconds — powered by free AI models**

Triadar is an intelligent clinical trial search and analysis platform that combines livetrial data with AI-powered insights. Search by disease, country, sponsor, or therapeutic area — and get instant intelligence on gaps, mechanisms of action, and key opinion leaders.

---

## ✨ Features

### 🔍 Smart Search
- Search by disease, condition, or therapeutic area
- Filter by species (human, veterinary, agricultural, environmental)
- Country-level and global search
- Real-time results from ClinicalTrials.gov

### 🗺️ Interactive Maps
- Global trial distribution visualization
- Disease prevalence mapping
- Regional hotspots and trends

### 🤖 AI-Powered Analysis
- **Gap Analysis** — Discover unmet needs and opportunities
- **MOA Clustering** — Group trials by mechanism of action  
- **KOL Identification** — Find leading investigators with PubMed verification

### 📊 Dashboards
- Disease landscape overview
- Phase distribution tracking
- Sponsor and institution rankings
- Timeline and enrollment trends

---

## 🚀 Getting Started

### Quick Start
1. Open `clinical-trials-ai.html` in any modern browser
2. Enter your API key (required for AI features)
3. Start searching

### API Keys (Free)
| Provider | Free Limits | Speed | Key Starts |
|---------|-----------|-------|------------|
| Groq | 14,400 req/day | 300+ tok/s | `gsk_...` |
| Gemini | 1,500 req/min | Fast | `AIza...` |
| Cerebras | 1M tokens/day | 2,600 tok/s | `csk-...` |
| OpenRouter | 200 req/day | Good | `sk-or-...` |

> **No credit card required** — All providers offer free tiers

---

## 📁 Project Structure

```
clinical-trials-ai/
├── clinical-trials-ai.html   # Main application (single file)
├── README.md                # This file
└── .gitignore               # Excludes node_modules, etc.
```

---

## 🛠️ Technical Details

- **Single HTML file** — No build step, no server required
- **Vanilla JS + Chart.js + Leaflet** — Lightweight frontend
- **Client-side only** — Your API keys stay in your browser
- **Responsive** — Works on desktop and tablet

---

## 🔒 Privacy & Security

- All API calls are made directly from your browser to AI providers
- No data is sent to any intermediate server
- API keys are stored locally in your browser session only
- Clear your browser data to revoke access

---

## 📈 Supported Queries

| Query Type | Example |
|-----------|---------|
| Disease | " typhoid", "TB", "COVID-19" |
| Country | "Nigeria", "India", "Brazil" |
| Sponsor | "Pfizer", "NIH", "University" |
| Phase | Phase 1, Phase 2, Phase 3 |
| Status | Recruiting, Completed, Active |

---

## 📬 Contact

- **Author:** Nour
- **Repo:** https://github.com/nour0810/clinical-trials-ai
- **Issues:** Open a GitHub issue for bugs or feature requests

---

## 📄 License

MIT License — See [LICENSE](LICENSE) for details.

---

<p align="center">
  <strong>Built with 💡 for the clinical research community</strong>
</p>