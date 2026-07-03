<div align="center">

# 🎩 Scarlet

[한국어](README.md) · **English**

### Multi-Agent Knowledge Exploration and Reasoning System

<p>
  <img alt="Python" src="https://img.shields.io/badge/python-3.12+-3670A0?logo=python&logoColor=ffdd54">
  <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white">
  <img alt="LLM" src="https://img.shields.io/badge/LLM-Claude%20%7C%20OpenAI%20%7C%20Ollama-D97757">
</p>

<img src="scarlet_concept.png" alt="Scarlet concept" width="880"/>

</div>

---

## 🆕 Latest News

> ### 🌐 Now on **TAW** — meet it as an agent!
>
> **Scarlet** has joined **[The Agents Web (TAW)](https://github.com/leeryong/The_Agents_Web_TAW/blob/main/README.md)** as an **agent**. No install needed — with a single **TAW Browser**, meet it **anywhere on PC or mobile** (Windows · macOS · Linux · iOS · Android), via **chat or its web app**.
>
> ➡️ **[The Agents Web (TAW)](https://github.com/leeryong/The_Agents_Web_TAW/blob/main/README.md)** · 🌌 **[KISTI · BLUESKY](https://github.com/leeryong/KISTI_BLUESKY)**


## 🔎 Overview

> *"There's the scarlet thread of murder running through the colourless skein of life, and our duty is to unravel it"* — Sherlock Holmes

**Scarlet is a multi-agent knowledge exploration system that autonomously explores and organizes diverse documents and data, then generates answers through evidence-based reasoning.**

Inspired by the **Holmes–Watson duo** in Conan Doyle's first Sherlock Holmes novel, [*A Study in Scarlet*](https://en.wikipedia.org/wiki/A_Study_in_Scarlet) (1887), two agents divide roles and collaborate — **Watson organizes, Holmes reasons.**

---

## 🩺 Watson — Data Collection · Knowledge Curation

<div align="center">
  <img src="scarlet_watson.png" alt="Watson — Knowledge Curator" width="860"/>
</div>

- **Collect** — gathers diverse documents and data and integrates them as knowledge-curation targets
- **Parse** — parses and interprets text, tables, images, charts, metadata, and more
- **Structure** — structures the extracted information into semantic units and organizes their relationships
- **Store** — stores it as Vector Index · Graph Links · Full Text · Metadata
- **Store integration** — unified management of diverse data stores: VectorDB · relational DB · NoSQL · search engines · MCP · local files · Obsidian, etc.
- **Extractors** — automatically selects the extractor matching the file type: PDF, DOCX, PPTX, HTML, images, media, etc.
- Ultimately builds the **Watson Journal**

> **📚 Watson Journal** — a refined knowledge base built by linking the data Watson collected, parsed, and structured to a VectorDB and the original sources. It manages documents, chunks, metadata, and processing state, and serves as the foundational knowledge store over which Holmes performs evidence search and reasoning.

---

## 🎩 Holmes — Search · Reasoning

<div align="center">
  <img src="scarlet_holmes.png" alt="Holmes — Analytical Reasoner" width="860"/>
</div>

- **Evidence search** — searches the Watson Journal for the key evidence relevant to the user's question
- **Clue selection** — selects meaningful clues from documents, tables, metadata, and relationship information
- **Multi-step reasoning** — connects and compares concepts, context, and causal relationships among clues, and verifies the logic and grounding of the answer
- **Answer generation** — ultimately generates a trustworthy, evidence-based answer

Holmes is an agent equipped with:
- **Self-Thought** capability
- **Memory** — a history of continuous thought, a memory graph
- **Spontaneous tool use**

---

## 💬 Conversation Among Holmes, Watson, and the User

<div align="center">
  <img src="scarlet_conversation.png" alt="Multi-agent conversation" width="860"/>
</div>

The user, Holmes, and Watson converse in one place. When the user asks a question, **Watson points to the relevant material and Holmes connects the evidence to reason**, while Scarlet presents the reasoning trace and the evidence together to produce a trustworthy answer.

```
Data  →  🩺 Watson (collect · parse · structure)  →  📚 Watson Journal  →  🎩 Holmes (search · multi-step reasoning)  →  evidence-based answer
```

---

## 📞 Contact
- Ryong Lee (ryonglee@kisti.re.kr)

---

## 👨‍💻 Development Team

KISTI **BLUESKY** Team — *Harmonizing Human and AI Collaboration* · [github.com/leeryong/KISTI_BLUESKY](https://github.com/leeryong/KISTI_BLUESKY)

- Ryong Lee (ryonglee@kisti.re.kr)
- Raeyoung Jang (raezero@kisti.re.kr)
- Jahyun Gu (jahyeongu@kisti.re.kr)
