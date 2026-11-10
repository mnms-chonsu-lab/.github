<div align="center">
  <h2>촌수의사 · M&amp;M's</h2>
  <p>고령·소규모 한우농가가 말로 남긴 농장 일지를, 신고할 때 접수자(축협·방역기관)에게 한 장 요약으로 함께 전달하는 신고·기록·방역 업무 지원 AI</p>
  <p>
    <img src="https://img.shields.io/badge/React-TypeScript-61DAFB?logo=react&logoColor=white" alt="React" />
    <img src="https://img.shields.io/badge/Vite-PWA-646CFF?logo=vite&logoColor=white" alt="Vite PWA" />
    <img src="https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white" alt="FastAPI" />
    <img src="https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white" alt="PostgreSQL" />
    <img src="https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white" alt="PyTorch" />
    <img src="https://img.shields.io/badge/OpenAI-412991?logo=openai&logoColor=white" alt="OpenAI" />
    <img src="https://img.shields.io/badge/MLflow-0194E2?logo=mlflow&logoColor=white" alt="MLflow" />
    <img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white" alt="Docker" />
    <img src="https://img.shields.io/badge/AWS-232F3E?logo=amazonaws&logoColor=white" alt="AWS" />
    <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white" alt="GitHub Actions" />
  </p>
  <sub>공모전 본선 MVP</sub>
</div>

---

## 핵심 기능

| # | 기능 | 설명 |
| --- | --- | --- |
| ① | 말로 쓰는 농장 일지 | 음성·사진으로 남기면 일지로 정리 |
| ② | 신고 기한 알림 + 신고서 초안 | 기한을 알려주고 신고서 초안을 채움 |
| ③ | 기존 신고 경로로 연결 | 이상이 의심되면 전화·사이트·축협으로 기록과 함께 연결 |
| ④ | 접수자용 한 장 요약 보기 | 접수자가 웹에서 요약 카드를 열람 |

**원칙**: 질병·신고 여부를 판정하지 않습니다 · `[바로 신고]`는 모든 화면에 항상 노출 · 안내 문구는 공식 지침(SOP·법령) 원문만 · 농가가 승인한 기록만 전달

---

## 레포

> 레포는 private이라 링크는 조직 멤버만 열 수 있습니다.

| 레포 | 역할 | 담당 |
| --- | --- | --- |
| [mnm-dev](https://github.com/mnms-chonsu-lab/mnm-dev) | 농가 앱 · 접수자 웹 · FastAPI 백엔드 · 배포 인프라 · 전체 `docker-compose` | 이유민, 이인서 |
| [mnm-ai](https://github.com/mnms-chonsu-lab/mnm-ai) | LLM 에이전트 3개 · 규칙 코드 · 인식 모델 추론 · 학습·평가·MLflow | 박명훈 (MLOps는 이인서 공동) |
| [mnm-data](https://github.com/mnms-chonsu-lab/mnm-data) | DB 마이그레이션 · 공공데이터 수집 · SOP·법령 지식베이스 · 시드 | 서인교 |

---

## 팀

| 이름 | 역할 | GitHub |
| --- | --- | --- |
| 이유민 | PM · Frontend | [@kkamret](https://github.com/kkamret) |
| 이인서 | Backend · Infra · MLOps | [@dooooing](https://github.com/dooooing) |
| 박명훈 | AI | [@parkmyeonghun](https://github.com/parkmyeonghun) |
| 서인교 | Data | [@tjdlsry](https://github.com/tjdlsry) |

---

## 일정

| 날짜 | 내용 |
| --- | --- |
| 11/21 | 기능 개발 마감 (이후 버그 수정만) |
| 11/22 | 운영 배포 |
| 11/22 ~ 27 | QA · 안정화 |
| 11/28 | 제출 |
