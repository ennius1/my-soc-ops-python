# 🎱 Soc Ops

> **Social Bingo for in-person mixers** — find five people who match the prompts and shout BINGO!

[![Python 3.13+](https://img.shields.io/badge/Python-3.13%2B-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.115%2B-009688?logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![HTMX](https://img.shields.io/badge/HTMX-powered-3D72D7?logo=htmx&logoColor=white)](https://htmx.org/)
[![uv](https://img.shields.io/badge/uv-package%20manager-DE5FE9)](https://docs.astral.sh/uv/)

---

## ✨ What is Soc Ops?

Soc Ops is a **live, browser-based Social Bingo game** built for team mixers, onboarding events, and icebreakers. Every player gets a unique randomised 5×5 board filled with prompts like *"bikes to work"* or *"speaks more than 2 languages"*. Walk the room, find matches, mark your squares — first to five in a row wins!

```
┌──────────┬──────────┬──────────┬──────────┬──────────┐
│ bikes to │ has a    │ plays an │ loves    │ does     │
│  work    │   pet    │instrument│ cooking  │  yoga    │
├──────────┼──────────┼──────────┼──────────┼──────────┤
│ speaks   │ has run  │ was born │ has met  │  can     │
│ 2+ langs │marathon  │elsewhere │celebrity │ juggle   │
├──────────┼──────────┼──────────┼──────────┼──────────┤
│ traveled │  left-   │  FREE ⭐  │  has a   │ plays    │
│ to Asia  │  handed  │  SPACE   │  twin    │  games   │
├──────────┼──────────┼──────────┼──────────┼──────────┤
│ has been │ collects │  read a  │ knows    │  has a   │
│ skydiving│ something│book/mo   │sign lang │  garden  │
├──────────┼──────────┼──────────┼──────────┼──────────┤
│ hidden   │ loves    │ been     │ has been │prefers   │
│ talent   │spicy food│  on TV   │ abroad   │  tea ☕  │
└──────────┴──────────┴──────────┴──────────┴──────────┘
```

---

## 🚀 Quick Start

```bash
# 1. Install dependencies
uv sync --dev

# 2. Run tests
uv run pytest

# 3. Start the dev server
uv run uvicorn app.main:app --reload --host 0.0.0.0 --port 8000
```

Open **http://localhost:8000** and start playing!

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Backend | [FastAPI](https://fastapi.tiangolo.com/) + Python 3.13 |
| Templating | [Jinja2](https://jinja.palletsprojects.com/) |
| Interactivity | [HTMX](https://htmx.org/) — no JavaScript framework needed |
| Styling | Custom CSS utility classes |
| Package manager | [uv](https://docs.astral.sh/uv/) |
| Testing | [pytest](https://pytest.org/) + [httpx](https://www.python-httpx.org/) |

---

## 📚 Lab Guide

This repo doubles as a **GitHub Copilot workshop**. Work through the parts in order:

| Part | Title |
|------|-------|
| [**00**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=00-overview) | Overview & Checklist |
| [**01**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=01-setup) | Setup & Context Engineering |
| [**02**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=02-design) | Design-First Frontend |
| [**03**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=03-quiz-master) | Custom Quiz Master |
| [**04**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=04-multi-agent) | Multi-Agent Development |

> 📝 Lab guides are also available in the [`workshop/`](workshop/) folder for offline reading.

Start at **[Part 00: Overview & Checklist](https://copilot-dev-days.github.io/agent-lab-python/step.html?step=00-overview)** for prerequisites and setup instructions.
