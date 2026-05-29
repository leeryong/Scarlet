<div align="center">

# 🎩 Scarlet

### 멀티에이전트 지식 탐색 및 추론 시스템

<p>
  <img alt="Python" src="https://img.shields.io/badge/python-3.12+-3670A0?logo=python&logoColor=ffdd54">
  <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white">
  <img alt="LLM" src="https://img.shields.io/badge/LLM-Claude%20%7C%20OpenAI%20%7C%20Ollama-D97757">
</p>

🇺🇸 [English](README.en.md)

<img src="scarlet_concept.png" alt="Scarlet 개념도" width="880"/>

</div>

---

## 🔎 개요

> *"무채색 인생의 실타래 속을 가로지르는 주홍빛 실(scarlet thread)을 풀어내는 것"* — 셜록 홈즈

**스칼렛(Scarlet)은 다양한 문서와 데이터를 스스로 탐색·정리하고, 근거 기반 추론으로 답변을 생성하는 멀티에이전트 지식 탐색 시스템입니다.**

*A Study in Scarlet*의 **홈즈–왓슨 콤비**를 모티프로, 두 에이전트가 역할을 나눠 협업합니다 — **왓슨이 정리하고, 홈즈가 추론합니다.**

---

## 🧩 구성

### 🎩 홈즈 (Holmes) — 검색·추론
- 질문 이해 및 핵심 단서 검색
- 근거 연결·추론을 통한 답변 생성
- **자율사고(Self-Thought)** 가 가능한 에이전트
- **기억** — 연속적 사고의 히스토리, 기억 그래프
- **자발적 도구 사용**

> Watson Journal에서 질문과 관련된 근거를 검색 → 단서를 선별 → 개념·맥락·인과관계를 연결·비교 → 다단계 추론으로 논리·근거를 검증 → **근거 기반의 신뢰 가능한 답변** 을 생성

### 🩺 왓슨 (Watson) — 자료 수집·지식화
- 문서·데이터 수집 및 파싱 (텍스트·표·이미지·차트·메타데이터)
- 추출 정보를 의미 단위로 구조화하고 관계를 정리
- Vector Index · Graph Links · Full Text · Metadata 형태로 저장
- 다양한 보관소 통합 — VectorDB · 관계형 DB · NoSQL · 검색엔진 · MCP · 로컬 파일 · Obsidian
- 지식베이스 구축·관리 및 인덱싱

> **Watson Journal** — 왓슨이 수집·파싱·구조화한 데이터를 VectorDB와 원본 소스에 연결해 만든 정련된 지식베이스. 문서·청크·메타데이터·처리상태를 관리하며, 홈즈가 근거 검색과 추론을 수행하는 기반 지식 저장소입니다.

```
데이터  →  🩺 왓슨 (수집·파싱·구조화)  →  📚 Watson Journal  →  🎩 홈즈 (검색·다단계 추론)  →  근거 기반 답변
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
