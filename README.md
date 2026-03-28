# 🎤 Roast My Prompt Battle — VYOM 2026

> **An interactive AI prompt engineering competition** organized by **GfG Campus Body – RIU** as part of the **VYOM 2026 Annual Fest**.

🌐 **Live Site:** [project-rnvmr.vercel.app](https://project-rnvmr.vercel.app)

---

## 📌 About

**Roast My Prompt Battle** is a fun, beginner-friendly competition where participants compete to craft the most creative, funny, or technically impressive prompts for AI tools like **ChatGPT**, **DALL·E**, and **Midjourney**.

The event introduces students to **prompt engineering** — one of the most valuable skills in modern AI — while keeping it entertaining, engaging, and open to everyone regardless of coding experience.

### Objectives
- Introduce students to AI tools and prompt engineering
- Encourage creativity and critical thinking
- Create an interactive and entertaining tech fest activity
- Promote awareness about AI technologies

---

## 🗂️ Project Structure

```
vyom-prompt-arena/
├── index.html       # Main event page (single-page application)
├── logo.png         # Prompt Arena logo
└── gfglogo.png      # GeeksforGeeks Campus Body logo
```

---

## ⚙️ Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Page structure |
| CSS3 | Styling & animations |
| Vanilla JavaScript | Interactivity & logic |
| Google Sheets (CSV) | Live shortlist & winner updates |
| Vercel | Hosting & deployment |

---

## 🏆 Event Format

### Participant Funnel

```
All Registered Students
        ↓  (Top 20 advance)
    Round 2 — 20 Students
        ↓  (Top 5 advance)
  Final Round — 5 Finalists
        ↓
     🏆 3 Winners Crowned
```

### Round 1 — Creative Prompt Challenge *(All Students · 20 min)*
Participants receive a creative theme and write a prompt, then generate output using ChatGPT or DALL·E. Judged on creativity, prompt detail, and output quality.

**Example themes:** *Cyberpunk version of our college · Robot street food vendor in India · Futuristic classroom in 2050*

### Round 2 — Prompt Engineering Challenge *(Top 20 · 20 min)*
Participants receive a basic prompt and must improve it with details, style, environment, and context. Top 5 advance to the Final.

**Example:** `"Create a robot."` → `"Create a highly detailed futuristic robot chef cooking samosas in a neon cyberpunk street market at night."`

### ⭐ Final Round — Roast Battle *(Top 5 · 15 min)*
Finalists tackle a surprise prompt live on stage with audience engagement and crowd voting. 3 winners announced at the end.

---

## ⏰ Timeline

| Time | Event |
|---|---|
| 10:00 AM | Registrations & Check-in |
| 10:20 AM | Round 1 begins |
| 10:40 AM | Round 1 ends |
| 11:00 AM | Round 2 begins |
| 11:20 AM | Round 2 ends |
| 11:40 AM | Final Round begins |
| 12:00 PM | Winners announced 🏆 |

---

## 🎯 Judging Criteria

| # | Criterion | Description |
|---|---|---|
| 01 | **Creativity & Prompt Design** | Uniqueness and cleverness of the prompt structure |
| 02 | **Humor & Audience Engagement** | How entertaining the prompt and output are |
| 03 | **Technical Relevance** | Understanding of prompting techniques — context, constraints, detail |
| 04 | **Confidence & Delivery** | Stage presence and clarity when presenting |
| 05 | **Quality of AI Output** | Effectiveness and impressiveness of the generated result |

---

## 🏅 Prizes

| Place | Prize |
|---|---|
| 🥇 1st | Certificate + GfG Goodies |
| 🥈 2nd | Certificate + GfG Goodies |
| 🥉 3rd | Certificate + GfG Goodies |

> All participants receive a **Participation Certificate**. Top performers may be featured on GfG Campus Body social media.

---

## 📋 Rules

- No personal attacks, hate speech, or offensive language of any kind
- Humor must focus on technology and developer culture only
- Participants must keep their roast strictly within the time limit
- Judges' or audience poll decision will be final and binding
- Individual participation only — solo registration required
- AI tools must be used as specified per round (ChatGPT, DALL·E, or Midjourney)

---

## 🛠️ Organizer Features

The site includes a **password-protected admin panel** that allows organizers to:

- Connect a Google Sheet to update **shortlisted candidates** per round in real time (auto-refreshes every 30 seconds)
- Connect a Google Sheet to publish **winner names** to the podium instantly after the event

### Google Sheet Setup (Shortlist)
1. Create a sheet with columns: `Round`, `Name`
2. Publish as CSV via **File → Share → Publish to web**
3. Paste the URL into the admin panel and click **Load Shortlisted Candidates**

### Google Sheet Setup (Winners)
1. Create a sheet with columns: `Place`, `Name`, `Handle`
2. Publish as CSV and paste the URL into the admin panel
3. Click **Load Winners** — the podium updates instantly

---

## 🚀 Running Locally

No build tools needed — it's pure HTML!

```bash
git clone https://github.com/HarshitXDev/vyom-prompt-arena.git
cd vyom-prompt-arena
# Open index.html in your browser
open index.html
```

---

## 🌐 Deployment

The project is deployed on **Vercel** with 20+ deployments and also hosted via **GitHub Pages**.

[![Vercel](https://img.shields.io/badge/Deployed%20on-Vercel-black?logo=vercel)](https://project-rnvmr.vercel.app)

---

## 🤝 Organized By

**GfG Campus Body – RIU** in association with **GeeksforGeeks**  
Part of the **VYOM 2026 Annual Fest**

---

## 📄 License

This project is open source. Feel free to fork and adapt it for your own college events!
