<h1 align="center">JISANGHYEOK</h1>
<p align="center">
<b>Full-Stack Developer</b> · Java 25 &amp; Spring Boot 4 · Next.js 16 &amp; React 19 · AI-Native Development
</p>

---

## What I Can Do

### Backend
- **Java 25 / Spring Boot 4.1 / Spring Framework 7** 기반 REST API 설계 및 구현
- **CQRS + Hexagonal Architecture + DDD Vertical Slicing** 으로 도메인 경계 설계
- **Spring Security + JWT** 인증·인가, RBAC 권한 매트릭스, OAuth 소셜 로그인
- **Spring Data JPA** 도메인 모델링, Soft Delete · 감사 로그(Auditable by Default) 설계
- 외부 결제·주문 API 연동과 **멱등(idempotent) 데이터 수집 파이프라인** 구축
- MySQL 스키마 설계, 상태 전이 규칙 기반 정합성 보장
- MessageSource 기반 i18n, 키 기반 Bean Validation 메시지 처리

### Frontend
- **Next.js 16 (App Router) + React 19 + TypeScript** 기반 서비스 개발
- Server Component / Route Handler 를 활용한 SSR 데이터 페칭
- **Tailwind CSS** 디자인 시스템과 공유 UI 라이브러리 구축
- 다국어(i18n), 권한 기반 라우트 가드, 에러 바운더리 UX 설계
- Recharts 데이터 시각화 대시보드, XLSX 리포트 export
- Playwright 기반 E2E 테스트

### Architecture &amp; Infra
- **Nx 22 + Gradle 9** 멀티모듈 모노레포(MSA 확장형) 설계 및 운영
- 프론트/백엔드 공유 TypeScript 타입, Contract Enum 자동 생성 파이프라인
- AWS EC2 / S3 / CloudFront, Nginx 리버스 프록시 기반 배포 토폴로지
- GitHub Actions CI/CD, 배포 전략 문서화
- pnpm 10 워크스페이스, Vite / rolldown-vite 빌드 환경

### AI Engineering
> AI를 "쓰는 것"보다, **AI가 정확하게 일할 수 있는 코드베이스와 규칙을 설계하는 것**에 집중합니다.

- **AI-Native 코드베이스 설계** — CLAUDE.md / AGENTS.md 단일 지침서 체계로 아키텍처 16원칙을 문서로 강제하고, 에이전트가 항상 같은 규칙 위에서 작업하도록 표준화
- **도메인 서브에이전트 전략** — 14개 비즈니스 도메인별 전용 서브에이전트를 정의해 컨텍스트 윈도우를 분할하고, 메인 에이전트는 오케스트레이터로서 결과 통합 및 공유 라이브러리 영향 교차 검증
- **프롬프트 설계** — 도메인 지침서(엔티티 관계 · API 스펙 · 비즈니스 규칙 · 의존성)를 사전 로드시켜 환각을 줄이고 산출물 일관성 확보
- **멀티 에이전트 운영** — Claude Code / Codex / Cursor / OpenCode / GitHub Copilot Agents 를 목적에 맞게 병행, CI 모니터링 서브에이전트로 파이프라인 자동 점검
- **가드레일 설계** — 에이전트의 작업 범위 제한(파일 수정만 허용, commit/PR 분리), 리뷰 게이트, 문서 정본화로 드리프트 방지
- **LLM 애플리케이션 개발** — Google GenAI SDK 연동으로 대시보드 요약·분석 기능 구현

---

## Tech Stack

**Backend**

![Java](https://img.shields.io/badge/Java_25-007396?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot_4-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![JPA](https://img.shields.io/badge/Spring_Data_JPA-59666C?style=for-the-badge&logo=hibernate&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle_9-02303A?style=for-the-badge&logo=gradle&logoColor=white)

**Frontend**

![Next.js](https://img.shields.io/badge/Next.js_16-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React_19-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)

**Infra &amp; Tooling**

![Nx](https://img.shields.io/badge/Nx_22-143055?style=for-the-badge&logo=nx&logoColor=white)
![pnpm](https://img.shields.io/badge/pnpm_10-F69220?style=for-the-badge&logo=pnpm&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

**AI**

![Claude](https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google_GenAI-4285F4?style=for-the-badge&logo=googlegemini&logoColor=white)
![GitHub Copilot](https://img.shields.io/badge/Copilot_Agents-000000?style=for-the-badge&logo=githubcopilot&logoColor=white)

---

## Selected Work

| Project | What I Built | Stack |
| --- | --- | --- |
| Enterprise Monorepo (private) | Nx + Gradle 모노레포 위 user/admin/brand API와 웹을 분리 운영, 공통 백엔드 라이브러리·도메인 코어 설계 | Java 25, Spring Boot 4, Next.js 16, Nx |
| 주문 원장 수집 API (private) | 외부 결제 플랫폼 주문·취소·라인을 멱등 적재하고 상품 매칭까지 처리하는 관리자 동기화 API | Spring Boot, JPA, MySQL |
| [counselor-dashboard](https://github.com/JISANGHYEOK-0901/counselor-dashboard) | 상담 데이터 모니터링 대시보드 — 차트 시각화, 엑셀 리포트, LLM 요약 | React 19, Tailwind, Recharts, Google GenAI |
| [MinjiSuper](https://minji-super.vercel.app) | 커머스 웹 프론트엔드 (Vercel 배포) | React 19, React Router 7, Framer Motion |
| [BaekJoonHub](https://github.com/JISANGHYEOK-0901/BaekJoonHub) | 알고리즘 풀이 아카이브 | Java |

---

## GitHub Stats

<p align="center">
<img height="165" src="https://github-readme-stats.vercel.app/api?username=JISANGHYEOK-0901&show_icons=true&include_all_commits=true&hide_border=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=JISANGHYEOK-0901&layout=compact&hide_border=true" />
</p>

---

## Contact

[![Email](https://img.shields.io/badge/wltkdgur123@naver.com-03C75A?style=for-the-badge&logo=naver&logoColor=white)](mailto:wltkdgur123@naver.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/JISANGHYEOK-0901)
