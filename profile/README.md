# 🍚 당당 (DangDang)
**병원에서 받은 관리 기준을, 매일 빠뜨리지 않게 — 임신성 당뇨 맞춤 관리 웹앱**

공공데이터 식품영양 DB · 병원 기준 맞춤 측정 알림 · 진료 전 리포트 · 산후 검사 관리

<br/>

2026.10.08 ~ 2026.12.09


### 💡 프로젝트 요약

**해결하고자 하는 문제**
> 임신성 당뇨 유병률은 2013년 7.6%에서 2023년 12.4%로 늘었지만,  
> 식사 → 식후 혈당 측정 → 기록 → 진료로 이어지는 흐름이 일상에서 **자주 끊어집니다.**

> 출산 후 1년 안에 혈당 검사를 받는 비율은 42.9%에 그쳐,  
> 산후 당뇨 위험 관리까지 이어지지 못합니다.

<br>

**서비스 개요**

> **당당**은  
> '식사 시작' 한 번으로 병원이 정한 시점에 측정 알림을 보내고,  
> 기록을 진료용 리포트로 정리하며, 출산 후 검사 일정까지 이어 주는  
> **임신성 당뇨 맞춤 관리 서비스**입니다. AI는 판단하지 않고 기록만 돕습니다.

**주요 기능**
- [ ] 공공데이터 식품영양 DB 기반 식사 기록 (사진 선택)
- [ ] 식후 1·2시간 측정 알림 · 재알림
- [ ] 식사 맥락과 연결된 혈당 타임라인
- [ ] 진료 전 리포트 (PDF)
- [ ] 진료 후 지시사항 정리 → 확인한 항목만 관리 기준에 반영
- [ ] 산후 혈당 검사 · 정기 검진 일정 관리

<br>

**기대 효과**
> 임신부는 병원 기준대로 **빠뜨리지 않고** 관리하고,  
> 의료진은 진료 전에 **정리된 기록**을 받아 상담 시간을 아끼며,  
> 출산 후 검사까지 이어져 **산후 당뇨 조기 발견**에 기여합니다.

<br><br>

<!-- 🏗️ 아키텍처 · 🗄️ ERD · 🎬 시연 이미지는 완성 후 여기에 -->

### Contributors

| FE · BE Developer | PM · AI · Infra |
|:---:|:---:|
| [김승민](https://github.com/seungminng123) | [임다현](https://github.com/dahyun0423) |
| <img src="https://avatars.githubusercontent.com/seungminng123" width="150" /> | <img src="https://avatars.githubusercontent.com/dahyun0423" width="150" /> |

<br><br>

## Tech Stack

### Environment
![VSCode](https://img.shields.io/badge/VSCode-0078D7?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ%20IDEA-000000?style=for-the-badge&logo=intellijidea&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

### Frontend
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![TanStack Query](https://img.shields.io/badge/TanStack%20Query-FF4154?style=for-the-badge&logo=reactquery&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-443E38?style=for-the-badge&logoColor=white)
![React Hook Form](https://img.shields.io/badge/React%20Hook%20Form-EC5990?style=for-the-badge&logo=reacthookform&logoColor=white)
![Zod](https://img.shields.io/badge/Zod-3E67B1?style=for-the-badge&logo=zod&logoColor=white)
![PWA](https://img.shields.io/badge/PWA-5A0FC8?style=for-the-badge&logo=pwa&logoColor=white)

### Backend
![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![Flyway](https://img.shields.io/badge/Flyway-CC0200?style=for-the-badge&logo=flyway&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)

### Database
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=for-the-badge&logo=redis&logoColor=white)

### AI
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white)
![uv](https://img.shields.io/badge/uv-DE5FE9?style=for-the-badge&logo=uv&logoColor=white)

### Infra
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS EC2](https://img.shields.io/badge/AWS%20EC2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white)
![AWS S3](https://img.shields.io/badge/AWS%20S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Let's Encrypt](https://img.shields.io/badge/Let's%20Encrypt-003A70?style=for-the-badge&logo=letsencrypt&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

### Monitoring / Test
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![JUnit5](https://img.shields.io/badge/JUnit5-25A162?style=for-the-badge&logo=junit5&logoColor=white)
![Testcontainers](https://img.shields.io/badge/Testcontainers-291A3F?style=for-the-badge&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)
![Gatling](https://img.shields.io/badge/Gatling-FF9E2A?style=for-the-badge&logoColor=white)

### Public Data / External APIs
![공공데이터포털](https://img.shields.io/badge/공공데이터포털-0B57D0?style=for-the-badge&logoColor=white)
![Kakao](https://img.shields.io/badge/Kakao-FFCD00?style=for-the-badge&logo=kakao&logoColor=black)

### Communication
![Discord](https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white)
