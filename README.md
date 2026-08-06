<div align="center">
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:1d4ed8,100:06b6d4&height=220&section=header&text=JISANGHYEOK&fontSize=62&fontColor=ffffff&fontAlignY=34&animation=fadeIn&desc=Full-Stack%20Developer%20%C2%B7%20AI-Native%20Engineering&descSize=18&descAlignY=54" />
</div>

<div align="center">
<a href="https://github.com/JISANGHYEOK-0901">
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1200&color=06B6D4&center=true&vCenter=true&width=680&lines=Java+25+%2B+Spring+Boot+4+%2B+Spring+Framework+7;Next.js+16+%2B+React+19+%2B+TypeScript;Nx+%2B+Gradle+Monorepo+%C2%B7+MSA+Ready;AWS+Infrastructure+%C2%B7+EC2+%2F+ALB+%2F+S3+%2F+CloudFront;AI-Native+Development+with+Domain+Sub-Agents" alt="Typing SVG" />
</a>
</div>

<div align="center">
<img src="https://komarev.com/ghpvc/?username=JISANGHYEOK-0901&style=for-the-badge&color=06b6d4" alt="profile views" />
<img src="https://img.shields.io/badge/Focus-Backend%20%26%20AI%20Engineering-1d4ed8?style=for-the-badge" alt="focus" />
</div>

<br/>

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

### AWS &amp; Cloud Infrastructure
- **EC2 서버 토폴로지 설계** — Nginx 리버스 프록시 기반 API·웹 동거 클러스터, 환경별 배포 ref 관리
- **ALB + ACM** HTTPS 종단 및 리스너 규칙 라우팅, ALB 뒤 클라이언트 실 IP 추적(X-Forwarded-For) 처리
- **AWS WAF** 공격 차단 룰 운영, **Security Group** 최소 권한 인바운드 정책 관리
- **S3 + CloudFront** 이미지·정적 자산 업로드/배포 파이프라인과 캐시 정책 구성
- **CloudWatch** 지표·로그 수집(Agent), 임계값 알람 구성, **Lambda** 알림 가공 + **SNS** 배포 알림 연동
- **IAM** 최소 권한 사용자·역할 설계, 정적 액세스 키 제거 후 credential chain 기반 접근으로 전환
- RDS(MySQL) 구성과 서버 전원 상태·비용 운영, 인프라 절차의 문서 정본화

### Architecture &amp; DevOps
- **Nx 22 + Gradle 9** 멀티모듈 모노레포(MSA 확장형) 설계 및 운영
- 프론트/백엔드 공유 TypeScript 타입, Contract Enum 자동 생성 파이프라인
- **GitHub Actions** CI/CD 파이프라인과 배포 전략 문서화
- pnpm 10 워크스페이스, Vite / rolldown-vite 빌드 환경, Docker 로컬 개발 환경

### AI Engineering
> AI를 "쓰는 것"보다, **AI가 정확하게 일할 수 있는 코드베이스와 규칙을 설계하는 것**에 집중합니다.

- **AI-Native 코드베이스 설계** — CLAUDE.md / AGENTS.md 단일 지침서 체계로 아키텍처 16원칙을 문서로 강제하고, 모든 에이전트가 같은 규칙 위에서 작업하도록 표준화
- **도메인 서브에이전트 전략** — 14개 비즈니스 도메인별 전용 서브에이전트로 컨텍스트 윈도우를 분할하고, 메인 에이전트는 오케스트레이터로서 결과 통합 및 공유 라이브러리 영향 교차 검증
- **프롬프트 설계** — 도메인 지침서(엔티티 관계 · API 스펙 · 비즈니스 규칙 · 의존성)를 사전 로드시켜 환각을 줄이고 산출물 일관성 확보
- **멀티 에이전트 운영** — Claude Code / Codex / Cursor / OpenCode / GitHub Copilot Agents 를 목적에 맞게 병행, CI 모니터링 서브에이전트로 파이프라인 자동 점검
- **가드레일 설계** — 에이전트 작업 범위 제한(파일 수정만 허용, commit/PR 분리), 리뷰 게이트, 문서 정본화로 아키텍처 드리프트 방지
- **LLM 애플리케이션 개발** — Google GenAI SDK 연동으로 대시보드 요약·분석 기능 구현

<br/>

## Tech Stack

<div align="center">

**Backend**

<img src="https://skillicons.dev/icons?i=java,spring,hibernate,mysql,gradle,redis&theme=dark" />

**Frontend**

<img src="https://skillicons.dev/icons?i=nextjs,react,ts,tailwind,vite,html&theme=dark" />

**Cloud &amp; DevOps**

<img src="https://skillicons.dev/icons?i=aws,docker,nginx,githubactions,vercel,linux&theme=dark" />

**Tooling &amp; AI**

<img src="https://skillicons.dev/icons?i=nx,pnpm,git,idea,vscode,py&theme=dark" />

<br/>

![Java](https://img.shields.io/badge/Java_25-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot_4.1-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js_16-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black)
![Nx](https://img.shields.io/badge/Nx_22-143055?style=flat-square&logo=nx&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle_9-02303A?style=flat-square&logo=gradle&logoColor=white)
![pnpm](https://img.shields.io/badge/pnpm_10-F69220?style=flat-square&logo=pnpm&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Claude](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=anthropic&logoColor=white)
![Gemini](https://img.shields.io/badge/Google_GenAI-4285F4?style=flat-square&logo=googlegemini&logoColor=white)

</div>

<br/>

## Selected Work

| Project | What I Built | Stack |
| --- | --- | --- |
| Enterprise Monorepo (private) | Nx + Gradle 모노레포에서 user/admin/brand API와 웹을 분리 운영, 공통 백엔드 라이브러리·도메인 코어 설계 | Java 25, Spring Boot 4, Next.js 16, Nx |
| 주문 원장 수집 API (private) | 외부 결제 플랫폼 주문·취소·라인을 멱등 적재하고 상품 매칭까지 처리하는 관리자 동기화 API | Spring Boot, JPA, MySQL |
| AWS 운영 인프라 (private) | EC2 + ALB + WAF + S3/CloudFront + CloudWatch 알람 구성 및 배포 파이프라인 | AWS, Nginx, GitHub Actions |
| [counselor-dashboard](https://github.com/JISANGHYEOK-0901/counselor-dashboard) | 상담 데이터 모니터링 대시보드 — 차트 시각화, 엑셀 리포트, LLM 요약 | React 19, Tailwind, Recharts, Google GenAI |
| [MinjiSuper](https://minji-super.vercel.app) | 커머스 웹 프론트엔드 (Vercel 배포) | React 19, React Router 7, Framer Motion |

<br/>

## Contribution Activity

<div align="center">

<img width="100%" src="https://raw.githubusercontent.com/JISANGHYEOK-0901/JISANGHYEOK-0901/output/snake.svg" alt="contribution snake" />

<img height="170" src="https://github-readme-streak-stats.demolab.com?user=JISANGHYEOK-0901&hide_border=true&theme=react&background=0d1117&ring=06b6d4&fire=06b6d4&currStreakLabel=06b6d4" alt="streak" />

</div>

<br/>

## Contact

<div align="center">

[![Email](https://img.shields.io/badge/wltkdgur123@naver.com-03C75A?style=for-the-badge&logo=naver&logoColor=white)](mailto:wltkdgur123@naver.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/JISANGHYEOK-0901)

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:06b6d4,50:1d4ed8,100:0f172a&height=140&section=footer" />
