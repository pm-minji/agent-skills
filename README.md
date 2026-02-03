# 에이전트 스킬 모음 (Agent Skills)

AI 에이전트(Antigravity, Cursor, Claude Code 등)를 위한 고품질 인스트럭션 및 워크플로우 모음입니다. 웹 개발, 데이터베이스 최적화, 보안 점검에 최적화되어 있습니다.

## 📥 설치 및 사용 방법

본 저장소의 스킬들은 [Agent Skills](https://github.com/google-labs-code/agent-skills) 표준을 따르며, `skills` CLI를 통해 간단히 설치할 수 있습니다.

### 1. 사용 가능한 스킬 목록 확인
프로젝트 터미널에서 아래 명령어를 실행하세요:
```bash
npx -y skills add pm-minji/agent-skills --list
```

### 2. 특정 스킬 설치
원하는 스킬의 이름을 지정하여 설치할 수 있습니다. 예를 들어, 리팩토링 스킬(`kaizen`)을 현재 프로젝트에 추가하려면:
```bash
npx -y skills add pm-minji/agent-skills --skill kaizen
```

*팁: 특정 프로젝트가 아닌 모든 곳에서 사용하려면 명령어 뒤에 `--global`을 붙이세요.*

---

## 🛠 주요 스킬 목록

### 🎨 디자인 및 UI (Design & UI)
- **frontend-design**: 프리미엄 수준의 현대적 웹 인터페이스 구현 가이드.

### 🏗 엔지니어링 및 품질 (Engineering & Quality)
- **kaizen**: 지속적인 개선, 리팩토링 및 실수 방지(Poka-Yoke) 기법 적용.
- **lint-and-validate**: 자동 품질 제어 및 정적 코드 분석 실행.
- **spec-generator**: 포괄적이고 상세한 기술 사양서(Specification) 생성.
- **react-best-practices**: 최신 리액트 패턴 및 성능 최적화 팁.

### 🔐 보안 및 백엔드 (Security & Backend)
- **supabase-postgres-best-practices**: Supabase/PostgreSQL 최적화 및 보안 가이드.
- **top-web-vulnerabilities**: OWASP Top 10 기반 보안 취약점 점검.

### 📈 마케팅 및 SEO
- **seo-audit**: 웹 애플리케이션 검색 엔진 최적화(SEO) 점검.
- **content-creator**: 고품질 마케팅 및 기술 콘텐츠 제작 지원.

---
AI 협업 시대에 맞춘 최적의 개발 워크플로우를 제공합니다.

