<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:1a1a2e,100:16213e&height=200&section=header&text=Vishwajeet%20Vikram%20Borade&fontSize=42&fontColor=58a6ff&fontAlignY=38&desc=Builder%20%E2%80%A2%20Hacker%20%E2%80%A2%20Founder-in-Progress&descAlignY=58&descColor=8b949e" />

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&pause=1000&color=58A6FF&center=true&vCenter=true&random=false&width=600&lines=Building+Nexus+%E2%80%94+AI+Game+Backend+Platform;Shipping+Echoes+of+Truth+%E2%80%94+AI+Interrogation+Game;Python+%C2%B7+FastAPI+%C2%B7+React+%C2%B7+C%2B%2B+%C2%B7+Go;From+India+%F0%9F%87%AE%F0%9F%87%B3+%E2%80%94+Targeting+YC+Startup+School)](https://git.io/typing-svg)

<br/>

<a href="https://alphascope.netlify.app/" target="_blank">
  <img src="https://img.shields.io/badge/AlphaScope-%E2%86%97%20Live-00C853?style=for-the-badge&logo=netlify&logoColor=white" />
</a>
&nbsp;
<a href="https://nse-trading-system-6117.onrender.com" target="_blank">
  <img src="https://img.shields.io/badge/NSE%20Trading-%E2%86%97%20Live-0078D4?style=for-the-badge&logo=render&logoColor=white" />
</a>
&nbsp;
<a href="https://stockflow-obza.onrender.com" target="_blank">
  <img src="https://img.shields.io/badge/StockFlow-%E2%86%97%20Live-FF6F00?style=for-the-badge&logo=render&logoColor=white" />
</a>
&nbsp;
<a href="https://Vishwajeet2005.github.io/SentinelX/" target="_blank">
  <img src="https://img.shields.io/badge/SentinelX-%E2%86%97%20Demo-8B0000?style=for-the-badge&logo=github&logoColor=white" />
</a>

<br/><br/>

![Profile Views](https://komarev.com/ghpvc/?username=Vishwajeet2005&color=58a6ff&style=flat-square&label=Profile+Views)
[![GitHub followers](https://img.shields.io/github/followers/Vishwajeet2005?label=Followers&style=flat-square&color=58a6ff)](https://github.com/Vishwajeet2005)

</div>

---

## 👨‍💻 About Me

```yaml
name:        Vishwajeet Vikram Borade
location:    India 🇮🇳
focus:       Full-Stack · AI/ML · Game Backend · AI-Integrated Games · Animation
currently:   Building Nexus (AI Game Backend Platform)
             + Echoes of Truth (AI Interrogation Game)
philosophy:  "Building things that I actually like and want to use."
learning:    FastAPI internals · Multiplayer architecture · AI NPC systems · Animation
```

I'm a self-taught developer who learns by shipping. I don't do tutorial projects — every repo here was built for a real purpose: a hackathon submission, a live product, or a problem I personally wanted solved. My work spans fintech, game infrastructure, cybersecurity, and AI — tied together by one thread: I build full systems, not just frontends.

---

## 🔭 Current Focus — Nexus & Echoes of Truth

<table>
<tr>
<td width="50%" valign="top">

### 🎮 Nexus
**AI Game Backend Platform**

A managed backend platform for multiplayer game developers — think AWS GameLift but with AI-native NPCs built in. Nexus handles:
- Multiplayer session infrastructure
- AI NPC service with dynamic behaviour
- Developer-facing SDK and APIs

*Status: Active development*
*Stack: Python · FastAPI · React · WebSockets*

</td>
<td width="50%" valign="top">

### 🕵️ Echoes of Truth
**AI Interrogation Game**

The flagship game built on Nexus that proves the platform. Players interrogate an AI suspect whose backstory, emotional state, and responses adapt dynamically to pressure and questioning style.

- Powered by the Nexus NPC service
- Demonstrates real AI-driven gameplay
- Live demo planned at launch

*Status: Co-development with Nexus*

</td>
</tr>
</table>

---

## 🚀 Projects

<details open>
<summary><b>🛡️ SentinelX — Enterprise Anti-Cheat Infrastructure</b></summary>
<br/>

> **Zero-Allocation Native SDK · High-Throughput Ingestion · Real-Time ML · Engine-Native SOC Dashboard**

[![Demo](https://img.shields.io/badge/Live%20Demo-%E2%86%97-8B0000?style=flat-square)](https://Vishwajeet2005.github.io/SentinelX/)
[![Repo](https://img.shields.io/badge/GitHub-SentinelX-181717?style=flat-square&logo=github)](https://github.com/Vishwajeet2005/SentinelX)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)

**What it does:**
Industry-grade anti-cheat infrastructure designed for high-concurrency Unreal Engine and Unity deployments. Engineered for absolute minimal performance impact while providing extreme real-time visibility and ML-driven anomaly detection.

**Architecture:**
| Layer | Technology | Role |
|---|---|---|
| Client SDK | C / C++ (C-ABI) | Zero-allocation ring buffer, HMAC-SHA256 signed telemetry, `<0.1ms` overhead |
| Ingest Edge | Golang | High-throughput UDP server, synthetic frame interpolation, jitter mitigation |
| Pipeline | Apache Kafka + Zookeeper | Scalable event streaming for millions of telemetry packets |
| Data Lake | ClickHouse | Columnar DB — queries billions of coordinate events in milliseconds |
| ML Engine | Python + ONNX | Anomaly detection for speedhacks and aim-snapping over rolling coordinate traces |
| SOC Dashboard | React + WebSockets | Live 2D radar of flagged players, instant manual review or auto-termination |

**Key engineering decisions:**
- `extern "C"` ABI on the SDK so it works in both Unreal (C++) and Unity (C# via P/Invoke) without recompilation
- Lockless ring buffer design so the SDK never blocks the game engine's tick loop
- Telemetry signed with HMAC-SHA256 per-session to prevent packet spoofing
- Full Docker Compose stack — one command brings up the entire pipeline locally

</details>

---

<details open>
<summary><b>📈 AlphaScope — NSE Stock Intelligence Terminal</b></summary>
<br/>

> **Dual-Signal Alpha Detection · Live NSE Prices · AI-Powered Briefs · Built for ET AI Hackathon 2026**

[![Live](https://img.shields.io/badge/Live%20App-%E2%86%97-00C853?style=flat-square)](https://alphascope.netlify.app/)
[![Repo](https://img.shields.io/badge/GitHub-AlphaScope-181717?style=flat-square&logo=github)](https://github.com/Vishwajeet2005/AlphaScope)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=flat-square&logo=netlify&logoColor=white)

**What it does:**
AlphaScope cross-validates two independent signal sources to surface high-conviction trade setups. Signals only fire when **both** agents agree simultaneously — dramatically reducing false positives that plague single-indicator systems.

**How the dual-agent system works:**
```
Chart Pattern Agent          Opportunity Radar Agent
─────────────────────        ───────────────────────
52-week breakout             Institutional bulk deals
Golden cross (MA)            Earnings surprises
RSI divergence               Promoter buying
Bollinger squeeze            Contract wins
Support test
         │                            │
         └──────── Alpha Fusion ──────┘
                  (both must fire)
                        │
               AI Brief via Groq
               (refreshed 30 min)
```

**Impact model:**
India has 14 crore+ demat accounts. Most retail investors act on WhatsApp tips and miss institutional signals. AlphaScope surfaces 3–8 confirmed dual-signal setups daily. If 1,000 users each capture a 5% move on ₹50,000 capital once per week → **₹2.5 crore in aggregate alpha per week**.

**Tech decisions:**
- Serverless Netlify Functions (Node.js) — zero infra cost, scales automatically
- Yahoo Finance API for live NSE prices — no API key, no data cost
- JWT sessions with bcrypt for user auth
- JSON file store (designed upgradeable to Netlify Blobs)
- Groq API + web search tool for fresh AI briefs on every signal

</details>

---

<details open>
<summary><b>📊 NSE Trading System — AI Trading Terminal</b></summary>
<br/>

> **Random Forest ML · NLP Sentiment · Telegram Alerts · Human-in-the-Loop Execution**

[![Live](https://img.shields.io/badge/Live%20App-%E2%86%97-0078D4?style=flat-square)](https://nse-trading-system-6117.onrender.com)
[![Repo](https://img.shields.io/badge/GitHub-NSE__Trading-181717?style=flat-square&logo=github)](https://github.com/Vishwajeet2005/NSE_Trading)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)

**What it does:**
A semi-autonomous trading terminal for NSE that blends rule-based technical analysis with ML predictions and live NLP sentiment — then delivers signals to your phone. Zero black boxes: the system proposes, you approve.

**ML Pipeline:**
| Component | Detail |
|---|---|
| Model | Random Forest Classifier |
| Training data | 15 years of NSE historical data |
| Indicators | RSI, ATR, MACD, candlestick patterns |
| Sentiment | VADER NLP on live Yahoo Finance headlines |
| Scheduler | APScheduler — scans watchlist every 30 min during market hours |
| Alerts | Telegram bot → instant buy/sell signal to your phone |
| Execution | Human-in-the-loop — manual approval via dashboard |

**Architecture:**
- Single unified Render web service serving both FastAPI backend and static React frontend
- SQLite (`nse_signals.db`) for tracking active/pending signals
- `render.yaml` blueprint for 1-click deployment
- Glassmorphism dark-mode React frontend with interactive candlestick charts

</details>

---

<details open>
<summary><b>📦 StockFlow — Full-Stack Inventory Management System</b></summary>
<br/>

> **2FA (TOTP) · JWT Rotation · Docker · Electron Desktop App · Sunmount Solutions Hackathon**

[![Live](https://img.shields.io/badge/Live%20App-%E2%86%97-FF6F00?style=flat-square)](https://stockflow-obza.onrender.com)
[![Repo](https://img.shields.io/badge/GitHub-StockFlow-181717?style=flat-square&logo=github)](https://github.com/Vishwajeet2005/StockFlow)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

**What it does:**
Enterprise-grade inventory system for SMEs — product catalogue, sales orders, purchase orders, manufacturing/WIP batch tracking, customer & supplier management, and real-time low-stock alerts with CSV export.

**Security architecture (production-grade):**
| Feature | Implementation |
|---|---|
| 2FA | RFC 6238 TOTP — Google Authenticator / Authy |
| Passwords | bcrypt cost-12 |
| Access tokens | JWT — 15 min expiry |
| Refresh tokens | 64-byte random, SHA-256 hashed, rotated on every use |
| Account lockout | 5 failed attempts → locked 15 minutes |
| Rate limiting | 10 login/15min · 300 API calls/min |
| Security headers | helmet (HSTS, X-Frame-Options, XSS protection) |

**Deployment options:**
- `bash deploy.sh` — full Docker one-command deploy
- Render.com web service
- Native Windows `.exe` via Electron — downloadable from GitHub Releases

</details>

---

<details>
<summary><b>🤖 Axiom Research Bot — AI Research Assistant</b></summary>
<br/>

[![Repo](https://img.shields.io/badge/GitHub-Axiom--research--bot-181717?style=flat-square&logo=github)](https://github.com/Vishwajeet2005/Axiom-research-bot)

An AI-powered research assistant bot. Automates multi-source research, synthesizes findings, and delivers structured summaries.

</details>

---

## 🧰 Tech Stack

<div align="center">

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)

**Backend & APIs**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

**Data & Streaming**

![Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC01?style=for-the-badge&logo=clickhouse&logoColor=black)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)

**ML / AI**

![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=for-the-badge&logo=onnx&logoColor=white)

**DevOps & Cloud**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=black)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

</div>

---

## 📊 GitHub Stats

<div align="center">

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Vishwajeet2005&theme=github-dark-blue&hide_border=true&background=0D1117&stroke=58a6ff&ring=58a6ff&fire=ff6b35&currStreakLabel=58a6ff" />

</div>

---

## 🏆 Hackathons & Achievements

| Event | Project | Category |
|---|---|---|
| **ET AI Hackathon 2026** | AlphaScope — NSE dual-signal intelligence terminal | PS6: AI for the Indian Investor |
| **Sunmount Solutions Hackathon** | StockFlow — Inventory management system | App / Web Development |

---

## 🗺️ What's Next

- [ ] Ship **Nexus** v1 — AI game backend platform (Python/FastAPI)
- [ ] Launch **Echoes of Truth** — AI interrogation game on Nexus
- [ ] Open-source a Nexus SDK module
- [ ] Hit 1000 commits in 2026

---

## 📫 Connect

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-Vishwajeet2005-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Vishwajeet2005)

*Open to collaborations on fintech, game infrastructure, and AI projects.*

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:16213e,50:1a1a2e,100:0D1117&height=120&section=footer" />

<sub>Built with ❤️ from India · Last updated May 2026</sub>

</div>
