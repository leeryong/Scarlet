<div align="center">

# 🎩 Scarlet

### A multi-agent knowledge-exploration & reasoning system

<p>
  <img alt="Python" src="https://img.shields.io/badge/python-3.12+-3670A0?logo=python&logoColor=ffdd54">
  <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white">
  <img alt="LLM" src="https://img.shields.io/badge/LLM-Claude%20%7C%20OpenAI%20%7C%20Ollama-D97757">
</p>

🇰🇷 [한국어](README.md)

<img src="scarlet_concept.png" alt="Scarlet concept" width="880"/>

</div>

---

## 🔎 Overview

> *"Unravelling the scarlet thread that runs through the colourless skein of life"* — Sherlock Holmes

**Scarlet is a multi-agent knowledge-exploration system that autonomously explores and organizes diverse documents and data, then generates answers through evidence-grounded reasoning.**

Inspired by the **Holmes–Watson partnership** of *A Study in Scarlet*, two agents divide the work — **Watson organizes, Holmes reasons.**

---

## 🧩 Composition

### 🎩 Holmes — search & reasoning
- Understands the question and searches for the key clues
- Generates answers by connecting evidence and reasoning over it
- A **self-thought** capable agent
- **Memory** — a history of continuous thought, a memory graph
- **Autonomous tool use** (currently: RAG, web)

> Searches the Watson Journal for evidence related to the question → selects clues → connects and compares concepts, context, and causality → verifies the logic through multi-step reasoning → produces a **trustworthy, evidence-grounded answer**

### 🩺 Watson — data collection & knowledge-building
- Collects and parses documents and data (text, tables, images, charts, metadata)
- Structures extracted information into semantic units and organizes their relationships
- Stores as Vector Index · Graph Links · Full Text · Metadata
- Integrates diverse stores — VectorDB · relational DB · NoSQL · search engines · MCP · local files · Obsidian
- Builds, manages, and indexes knowledge bases

> **Watson Journal** — a refined knowledge base that Watson builds by linking the data it has collected, parsed, and structured to a VectorDB and the original sources. It manages documents, chunks, metadata, and processing state, serving as the foundation Holmes uses for evidence search and reasoning.

```
data  →  🩺 Watson (collect · parse · structure)  →  📚 Watson Journal  →  🎩 Holmes (search · multi-step reasoning)  →  grounded answer
```

---

## 🖥️ Screenshot

<div align="center">
  <img src="scarlet_home_2.png" alt="Scarlet dashboard" width="860"
       style="border:1.5px solid #333; border-radius:8px;" />
</div>

---

## 📞 Contact
- Yong Lee (ryonglee@kisti.re.kr)

---

## 👥 Team BLUESKY
- Yong Lee (ryonglee@kisti.re.kr)
- Raeyoung Jang (raezero@kisti.re.kr)
- Jahyeon Gu (jahyeongu@kisti.re.kr)
