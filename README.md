<h1 align="center">Neil Banerjee</h1>
<h3 align="center">B.Tech Computer Engineering @ Institute of Advanced Research (IAR), Gandhinagar</h3>
<h4 align="center">Agentic AI Systems · Full-Stack Engineering · Applied ML Research</h4>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&pause=1000&color=00E5FF&center=true&vCenter=true&width=700&lines=Multi-agent+orchestration+with+LangGraph+%26+CrewAI;RAG+pipelines+%7C+FastAPI+%7C+React%2FTypeScript;Deploying+on+GCP%2C+Render+%26+Vercel" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://github.com/neil-data"><img src="https://img.shields.io/badge/GitHub-neil--data-181717?style=for-the-badge&logo=github" /></a>
  <a href="mailto:neilbanerjee2007@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <img src="https://img.shields.io/badge/GDGoC-IAR%20Chapter-4285F4?style=for-the-badge&logo=google&logoColor=white" />
</p>

---

## 📌 Overview

I'm a Computer Engineering undergraduate (Class of 2029) focused on **agentic AI architectures** and **production-grade full-stack systems**. My work spans multi-agent orchestration frameworks, retrieval-augmented generation, real-time backend infrastructure, and applied ML research. I build primarily with **FastAPI**, **LangGraph/CrewAI**, and **React/TypeScript**, deploying across **Render, Vercel, and GCP**.

I'm an active member of **Google Developer Groups on Campus (GDGoC) at IAR**. My practical training includes the **IIT Roorkee ML/AI Training Programme**, a summer training programme, and an internship — building applied ML and full-stack project experience alongside my coursework.

---

## 🧠 Core Competencies

| Domain | Tools & Frameworks |
|---|---|
| **Agentic AI / Orchestration** | LangGraph, CrewAI, multi-agent pipelines, RAG systems |
| **Backend Engineering** | FastAPI, Django + DRF, REST API design, WebSockets, JWT/RBAC auth |
| **Frontend Engineering** | React, TypeScript, Vite, Next.js, GSAP, Tailwind CSS |
| **Data & ML** | PyTorch, XGBoost, LSTM, FinBERT, scikit-learn, pandas-ta |
| **Infrastructure** | Docker, PostgreSQL, TimescaleDB, Redis (Upstash/BullMQ), GCP, Render, Vercel |
| **LLM Providers** | Groq, NVIDIA NIM (Kimi K2.6), Gemini, Claude (via OmniRoute gateway) |

---

## 🚀 Featured Projects

### 🛰️ DeadSat Resurrection
FastAPI + TypeScript satellite operations console, currently in active development.
- LangGraph-based fault-detection agent for satellite telemetry
- Orbital mechanics modeling via `sgp4`
- FastAPI backend with 19 endpoints
- RBAC implementation in progress: JWT role claims with telemetry redaction differentiated by viewer vs. operator roles
- Grew out of hardware research into NOAA APT satellite signal reception

### 🏙️ UrbanMind
Multi-agent smart city backend coordinating five domain-specific agents: **Traffic, Energy, Safety, Environment, and Waste**.
- LLM routing via **Kimi K2.6 on NVIDIA NIM**, with **Groq** as fallback
- Anomaly detection using `IsolationForest`
- FastAPI + WebSocket architecture with an in-memory event bus
- Scoped a 5-month expansion: Ahmedabad as a demo city, PostgreSQL + TimescaleDB, Redis via Upstash, dual-LLM routing
- Prioritized over an earlier chess-coaching platform concept (Tactix), which was shelved to focus engineering effort here

### 📈 FinFusionNet
Undergraduate ML thesis evaluating whether FinBERT-derived sentiment representations improve on price-only baselines for NIFTY50 index prediction.
- Five-experiment ablation design: XGBoost, LSTM, Lexicon+VADER, FinBERT, and FinFusionNet (temporal cross-attention fusion)
- Data pipeline: Yahoo Finance (`yfinance`), `pandas-ta`/`ta` for technical indicators, NewsAPI as a GDELT fallback
- Walk-forward validation across 34 folds; direction accuracy clustered at 49–51% with no statistically significant sentiment effect
- Diagnosed null sentiment results as an artifact of NewsAPI's 30-day free-tier lookback constraint against 19 months of price history — a key methodological finding of the thesis

### 🛡️ Trinetra — Smart India Hackathon 2026
Cybersecurity system built with **Team WannaCry** for Problem Statement **PS-SW-004**.
- Owned four AI/ML workstreams end-to-end: entity resolution, stylometry analysis, false-positive guarding, and evidence quality scoring
- Built and smoke-tested all four modules from scratch
- Resolved three production bugs: incorrect fuzzy matching across entity types, a character n-gram gate miscounting tokens as characters, and a dependency registry key collision
- Authored the team's bug scan report, pitch script, judge Q&A prep, and personal workstream documentation
- Design philosophy: **"AI never makes the final call"** — systems are fail-closed by design

### 🧮 4-Year-DSA-Transformation
A structured, long-horizon data structures & algorithms practice repository.
- 36+ LeetCode solutions organized by pattern (Two Pointers, Binary Search, Sliding Window, Hashing, Linked Lists, Prefix Sums, Intervals, 2D Matrices, DP)
- Daily two-problem cadence with a full revision checkpoint scheduled at 50 problems solved

---

## 🗂️ Additional Work

| Project | Description |
|---|---|
| **Quantira** | Financial forensics platform for NSE/BSE equities — Altman-Z, Beneish-M, and Industry-Z scoring; Screener.in scraping; Groq Llama 3.3 70B primary with Gemini fallback; BullMQ + Upstash Redis job queues; Firebase auth; Vite/React/TypeScript frontend deployed on Render |
| **SentinelScan** | Cross-platform malware detection suite built for **E-Rakshak 2026 CTF** with team HackersAPK (Rank 6, qualified for Round 2) — LangGraph multi-agent orchestration, FastAPI backend, React/TypeScript + GSAP frontend, KVM/CAPE sandbox on GCP, two-plane deployment |
| **ASTRA** | Space radiation forecasting system built for the **ISRO Bharatiya Antariksh Hackathon 2026** — FastAPI, PostgreSQL/TimescaleDB, Redis, PyTorch LSTM + XGBoost ensemble, React frontend |
| **FleetFlow** | MERN-stack logistics ERP with RBAC, JWT authentication, and 34 REST endpoints, deployed on Render + Vercel |
| **Startup-AYUSH Portal** | Django + DRF backend, React + Vite + Tailwind frontend, and a dedicated FastAPI AI microservice for scheme matching and application/milestone tracking, deployed via Vercel and Render |
| **DNSGuard AI** | Unified DNS threat detection engine built in a one-week SIH internal round with a 6-person team |
| **GhostWire** | IoT road accident detection system (MQTT, OSRM, Twilio, MongoDB Atlas) built at the FARAWAY hackathon before pivoting to STRATOSENSE for the Space & Aerospace track |
| **TrafficPilot AI** | Multi-agent traffic management system using YOLOv8 for vehicle detection and Raspberry Pi GPIO for real-world signal control |
| **GDGoC IAR Website** | Deployed the chapter's Django + Next.js site to Vercel, resolving legacy adapter incompatibilities, `ALLOWED_HOSTS` misconfiguration, and CSP issues |
| **IIT Roorkee ML/AI Training Programme** | Delivered a submission package (Word report + Jupyter notebooks) covering three ML projects, including a Siamese BiLSTM model for resume–JD matching |

---

## 🧰 Tech Stack

**Languages**
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
</p>

**Backend & APIs**
<p>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white" />
  <img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white" />
</p>

**Frontend**
<p>
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" />
  <img src="https://img.shields.io/badge/GSAP-88CE02?style=flat-square&logo=greensock&logoColor=white" />
</p>

**AI / ML / Agentic Systems**
<p>
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square" />
  <img src="https://img.shields.io/badge/CrewAI-FF6B35?style=flat-square" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/XGBoost-006ACC?style=flat-square" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white" />
  <img src="https://img.shields.io/badge/Groq-F55036?style=flat-square" />
  <img src="https://img.shields.io/badge/NVIDIA%20NIM-76B900?style=flat-square&logo=nvidia&logoColor=white" />
</p>

**Data & Infrastructure**
<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/TimescaleDB-FDB515?style=flat-square" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black" />
</p>

**Deployment**
<p>
  <img src="https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white" />
  <img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" />
  <img src="https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=white" />
</p>

---

## 🎯 Currently Working Toward

- Building a portfolio of **5 strong, production-grade projects** by the end of Year 3
- Completing the **top 5 MERN stack project** benchmark
- A structured entry into applied ML: a 6-week Agentic AI + ML course followed by 1.5 months of dedicated Data Science study

---

## 📫 Contact

<p align="center">
  <a href="mailto:neilbanerjee2007@gmail.com"><img src="https://img.shields.io/badge/Email-neilbanerjee2007%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://github.com/neil-data"><img src="https://img.shields.io/badge/GitHub-neil--data-181717?style=for-the-badge&logo=github" /></a>
</p>

<p align="center"><i>"AI never makes the final call — fail-closed by design."</i></p>
