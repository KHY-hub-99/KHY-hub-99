<div align="center">

  <a href="https://github.com/gonida1010">
    <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1e3a8a,50:7c3aed,100:db2777&height=220&section=header&text=Hyeonyong%20Kim's%20Code%20&fontSize=42&fontColor=ffffff&fontAlignY=38&animation=fadeIn" />
  </a>

  <p>
    <a href="https://app.notion.com/p/2e2ddf1ded0b80f6bc0ed85ec629c6b3?v=2e2ddf1ded0b81fe9bfb000ccb650424&source=copy_link" target="_blank"><img src="https://img.shields.io/badge/Tech%20Blog-000000?style=for-the-badge&logo=Notion&logoColor=white"/></a>
    <a href="mailto:multikhy0612@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=Gmail&logoColor=white"/></a>
  </p>

</div>

## About Me

-  **Problem Solving** — 복잡한 문제의 핵심을 파악, 실제 서비스에서 동작하는 해결책 구현
-  **AI System Design** — 모델 성능, 데이터 흐름, 판단 구조를 고려해 AI 시스템 설계
-  **Collaboration** — 팀원들과 소통하고 검증하며, 아이디어를 완성

<br/>

## Pinned Projects
<div align="center">
  <table>
    <tr>
      <td valign="top" width="50%">
        <a href="https://github.com/KHY-hub-99/AgentShield">
          <img src="https://github-readme-stats.shion.dev/api/pin/?username=KHY-hub-99&repo=AgentShield&theme=tokyonight&show_owner=true&hide_description=true" width="100%" />
        </a>
      </td>
      <td valign="top" width="50%">
        <a href="https://github.com/KHY-hub-99/OpenTripPlanner-Backend">
          <img src="https://github-readme-stats.shion.dev/api/pin/?username=KHY-hub-99&repo=OpenTripPlanner-Backend&theme=tokyonight&show_owner=true&hide_description=true" width="100%" />
        </a>
      </td>
    </tr>
    <tr>
      <td valign="top" width="50%">
        <a href="https://github.com/KHY-hub-99/OpenTripPlanner-Front">
          <img src="https://github-readme-stats.shion.dev/api/pin/?username=KHY-hub-99&repo=OpenTripPlanner-Front&theme=tokyonight&show_owner=true&hide_description=true" width="100%" />
        </a>
      </td>
      <td valign="top" width="50%">
        <a href="https://github.com/KHY-hub-99/OpenTripPlanner-ML">
          <img src="https://github-readme-stats.shion.dev/api/pin/?username=KHY-hub-99&repo=OpenTripPlanner-ML&theme=tokyonight&show_owner=true&hide_description=true" width="100%" />
        </a>
      </td>
    </tr>
  </table>
</div>

<br/>

## Team Project

### AgentShield · LLM 보안 검증 플랫폼

<a href="https://github.com/gonida1010/AgentShield" target="_blank">
  <img src="https://img.shields.io/badge/Stack-FastAPI%20·%20Next.js%20·%20LangGraph%20·%20Ollama-7c3aed?style=flat-square"/>
  <img src="https://img.shields.io/badge/Domain-OWASP%20LLM%20Top%2010-0ea5e9?style=flat-square"/>
</a>

> **Red(공격) → Judge(판정) → Blue(방어)** 멀티 에이전트 파이프라인으로 LLM 챗봇의 취약점을 자동 진단·완화하는 SaaS형 보안 검증 플랫폼

- **Red Agent** — 라운드 기반 적응형 공격 프롬프트 생성 (다국어 / 인코딩 회전 / 도메인 컨텍스트)
- **Judge (LangGraph)** — Evidence Scanner · Strict Auditor · Context Auditor 합의 모델로 vulnerable / safe / ambiguous 판정
- **Blue Agent** — Phase 3 방어 규칙 생성 → Phase 4 검증 → **Phase 5 Guardrail Policy Package** 산출
- **Testbed** — Implicit RAG 기반 챗봇 + Tool Gateway + ChromaDB(공개/내부/오염 문서) Docker 통합 환경
- **Monitoring Proxy** — 운영 챗봇 앞단 P1~P4 정책 게이트 + 멀티턴 보존 + tool_trace 추적
- **OWASP LLM Top 10 커버** — LLM01 Prompt Injection · LLM02 Sensitive Info · LLM06 Excessive Agency · LLM07 System Prompt Leakage

<a href="https://github.com/KHY-hub-99/AgentShield" target="_blank">
  <img src="https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>

<a href="https://app.notion.com/p/AgentShield-36fddf1ded0b80b5aab5ce73a83c7330?source=copy_link" target="_blank">
  <img src="https://img.shields.io/badge/Notion-Document-181717?style=for-the-badge&logo=notion&logoColor=white" />
</a>

---

### OpenTripPlanner · 사용자 일정 맞춤 경로 추천 플랫폼

<a href="https://github.com/KHY-hub-99/OpenTripPlanner-Backend" target="_blank">
  <img src="https://img.shields.io/badge/Stack-Next.js%20·%20FastAPI%20·%20R5PY%20·%20BackTracking%20Algorithm-7c3aed?style=flat-square"/>
  <img src="https://img.shields.io/badge/Domain-Trip%20Place%20%20Public%20Data-0ea5e9?style=flat-square"/>
</a>

> 사용자가 일정을 입력하면 그 날짜와 장소에 맞는 여행지를 추천하는 플랫폼

- **대중교통** — R5PY로 도로망(.pbf) 데이터와 정적 교통망(GTFS) 데이터를 활용하여 A-B 장소에 대한 대중교통 정보 제공
- **커스텀 DFS BackTracking** — 사용자의 조건(고정일정, 가고 싶은 장소 등)에 맞는 알고리즘을 구현하여 최적의 경로 추천
- **인구/교통 분류 ML** — HistGradientBoostingClassifier 모델을 통한 인구/교통 혼잡도 예측(정확도 90.1%)
- **데이터 보관** — PostgreSQL 활용 + DBeaver 툴 활용

<a href="https://github.com/KHY-hub-99/OpenTripPlanner-Backend" target="_blank">
  <img src="https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>

<a href="https://app.notion.com/p/OpenTripPlanner-312ddf1ded0b807fbab9db7abd445d22?source=copy_link" target="_blank">
  <img src="https://img.shields.io/badge/Notion-Document-181717?style=for-the-badge&logo=notion&logoColor=white" />
</a>

---

## Tech Stack

<table>
  <tr>
    <td valign="top" width="50%">

**AI / LLM**
Vision · OCR · Fine-Tuning(LoRA) · LangGraph · RL · Data-Centric · ML

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white"/> <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=PyTorch&logoColor=white"/> <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=OpenCV&logoColor=white"/> <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black"/> <img src="https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white"/>

  </td>
  <td valign="top" width="50%">

**Backend**
Async API · Model Serving · Data Pipeline · RDBMS · Vector DB

<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=FastAPI&logoColor=white"/> <img src="https://img.shields.io/badge/Node.js-339939?style=flat-square&logo=Node.js&logoColor=white"/> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=PostgreSQL&logoColor=white"/> <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=MySQL&logoColor=white"/> <img src="https://img.shields.io/badge/ChromaDB-FF6B6B?style=flat-square&logoColor=white"/>

  </td>
  </tr>
  <tr>
  <td valign="top" width="50%">

**Frontend**
Dynamic UI · GenUI · SPA · 디자인 시스템

<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=Next.js&logoColor=white"/> <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=React&logoColor=black"/> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=TypeScript&logoColor=white"/> <img src="https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white"/> <img src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=Figma&logoColor=white"/>

  </td>
  <td valign="top" width="50%">

**Infra / DevOps**
컨테이너화 · 배포 · 모니터링 · 비용/성능 최적화

<img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white"/> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=Docker&logoColor=white"/> <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=Linux&logoColor=black"/> <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"/>

  </td>
  </tr>
</table>

<br/>

## GitHub Stats

<div align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=KHY-hub-99&theme=tokyonight" />
  <br/>
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=KHY-hub-99&theme=tokyonight" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=KHY-hub-99&theme=tokyonight" />
  <br/>
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=KHY-hub-99&theme=tokyonight" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=KHY-hub-99&theme=tokyonight&utcOffset=9" />
</div>

<br/>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:db2777,50:7c3aed,100:1e3a8a&height=100&section=footer" />
</div>
