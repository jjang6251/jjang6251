### 안녕하세요, 백엔드 개발자 장성원입니다 👋

직접 만든 서비스를 실제 사용자에게 운영하며, 배포부터 보안·AI 기능까지 책임지고 있습니다.<br>
소프트웨어학과에서 정보보안공학을 복수전공했고, 보안을 알고 만드는 개발을 지향합니다.

<br>

## Portfolio

### 치뽀 (Chwippo)

취준생을 위한 취업 일정 관리 서비스 — 공고 마감·서류·면접 일정을 한 곳에서 관리합니다.

- 웹사이트 → [chwippo.com](https://chwippo.com) · [로그인 없이 둘러보기](https://chwippo.com/demo)
- iOS 앱 → [App Store에서 다운로드](https://apps.apple.com/kr/app/id6789707709)
- Android 앱 → [Google Play에서 다운로드](https://play.google.com/store/apps/details?id=com.chwippo.app)
- 사용자 → 470+

| 운영 배포 | 데이터 유실 | 앱 스토어 심사 | AI 호출 |
|:---:|:---:|:---:|:---:|
| **162회** | **0건** | **두 스토어 첫 심사 승인** | **18종을 한 계층에서 관리** |

**맡은 범위** 기획·설계 · 백엔드 · 웹 · 모바일 앱 · 배포·운영<br>
**기술** NestJS · TypeScript · PostgreSQL · Redis · React · Expo(React Native) · Railway · Cloudflare · GitHub Actions

**주요 작업**

- **배포** — DB 마이그레이션은 CI에서 적용·되돌리기를 검증한 뒤 반영
- **보안** — 리소스 소유권 이중 검증(IDOR 차단), LLM 호출 전 AI 활용 동의 확인·개인정보 마스킹(12종)
- **요청 제한** — 여러 서버가 같은 횟수를 보도록 Redis로 집계, Cloudflare 헤더로 실제 방문자 IP 식별
- **AI 운영** — 호출마다 기능·모델·토큰·비용 기록, 제공사 일시 장애에만 대체 모델 전환, 성공한 호출에만 코인 차감
- **AI 활용 개발** — Claude Code에 규칙 문서·명령·스킬을 두고, 커밋 전 정적 분석·테스트·보안 점검을 거쳐 반영

<br>

### 그 밖의 프로젝트

| 프로젝트 | 내용 |
|---|---|
| **IoT 침입 방지 시스템 연구** (2024) | 블록체인 DID 신원인증 백엔드·아키텍처 설계 · 5인 공저 · **KCSE 2025 우수학부생논문상** |
| **[우아정](https://github.com/jjang6251/wooajung-contract)** (2025) | 블록체인 에스크로 중고거래 · 3인 팀 팀장 · 에스크로 컨트랙트(Solidity)·AI 크롤링 서버(FastAPI) |

<br>

📄 **포트폴리오** → [jjang6251.github.io/portfolio](https://jjang6251.github.io/portfolio/)
