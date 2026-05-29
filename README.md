<div align="center">

# 🎩 Scarlet

<p>
  <img alt="Python" src="https://img.shields.io/badge/python-3.12+-3670A0?logo=python&logoColor=ffdd54">
  <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white">
  <img alt="LLM" src="https://img.shields.io/badge/LLM-Claude%20%7C%20OpenAI%20%7C%20Ollama-D97757">
</p>

🇺🇸 [English](README.en.md)

</div>

---

## 🔎 개요

### **Scarlet — 멀티에이전트 RAG 시스템**

> *"무채색 인생의 실타래 속을 가로지르는 주홍빛 실(scarlet thread)을 풀어내는 것"* — 셜록 홈즈

**흩어진 데이터 속에서 답으로 이어지는 주홍빛 실을 찾아 풀어내는 지식 탐색 시스템**

- *A Study in Scarlet*의 **홈즈–왓슨 콤비**를 모티프로 한 멀티에이전트 구조
- 두 에이전트가 역할을 나눠 협업 — **왓슨이 정리하고, 홈즈가 추론**
- 기관 내부 문서를 기반으로 **근거(출처)와 함께 답하는** 로컬 RAG 환경

---

## 🧩 구성

| 에이전트 | 역할 |
| --- | --- |
| 🎩 **홈즈 (Holmes)** | 검색·추론 에이전트. 질문을 받아 지식베이스에서 근거를 찾아 **출처와 함께** 답합니다. |
| 🩺 **왓슨 (Watson)** | 지식베이스 관리 에이전트. 데이터를 **수집·정리·색인**해 탐색의 토대를 마련합니다. |

```
데이터  →  🩺 왓슨 (정리·색인)  →  지식베이스  →  🎩 홈즈 (검색·추론)  →  근거 기반 답변
```

---

## 🖥️ 화면

<div align="center">
  <img src="scarlet_home_2.png" alt="Scarlet 대시보드" width="860"
       style="border:1.5px solid #333; border-radius:8px;" />
</div>

---

## 📞 문의
- 이용 (ryonglee@kisti.re.kr)

---

## 👥 팀 BLUESKY
- 이용 (ryonglee@kisti.re.kr)
- 장래영 (raezero@kisti.re.kr)
- 구자현 (jahyeongu@kisti.re.kr)
