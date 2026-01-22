# 🚀 Antigravity Awesome Skills (miny_agent)

> 200개 이상의 유용한 AI 에이전트 스킬과 **한국어 명령어 시스템**이 통합된 Antigravity 개발 워크플로우 저장소입니다.  
> 원본 스킬 출처: [antigravity-awesome-skills](https://github.com/sickn33/antigravity-awesome-skills/)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Skills](https://img.shields.io/badge/Skills-200%2B-blue.svg)](#-skill-categories)
[![GitHub](https://img.shields.io/badge/GitHub-miny__agent-black.svg)](https://github.com/miny5/miny_agent)

[English](#-quick-start) | [한국어](#-한국어-명령어-시스템-사용-가이드)

---

## 🇰🇷 한국어 명령어 시스템 사용 가이드

영어로 된 복잡한 스킬 이름 대신, 직관적인 **한국어 키워드**로 기능을 바로 호출할 수 있습니다.

### 1단계: 프로젝트에 연결 (Submodule)

```bash
# 프로젝트 루트 폴더에서 실행
git submodule add https://github.com/miny5/miny_agent .agent
```

### 2단계: 한국어 명령어 사용

대화창에서 `@키워드` 또는 `/kr 키워드` 형태로 요청하세요.

| 카테고리 | 주요 키워드 | 설명 (연동 스킬/도구) |
| :--- | :--- | :--- |
| **개발/디자인** | `디자인`, `백엔드`, `코드수정` | 웹 UI 제작, API 서버 설계, 코드 클린업 |
| **특수 기술** | `3D`, `게임개발`, `AI에이전트` | Three.js, 게임 아키텍처, 자율 에이전트 설계 |
| **보안** | `보안`, `해킹테스트` | 웹 취약점 분석, 윤리적 해킹 방법론 |
| **업무 자동화** | `자동화`, `슬랙봇`, `데이터분석` | n8n 워크플로우, Slack 연동, 엑셀 분석 |
| **가장 유용한** | `추천` | **현재 대화 맥락에 꼭 필요한 스킬을 에이전트가 추천** |

### 3단계: 커스텀 명령어 추가

`.agent/korean_commands.json` 파일을 수정하여 나만의 한국어 명령어와 스킬을 매핑할 수 있습니다.

---

## ✨ What is this? (English Guide)

This repository contains **modular skill definitions** and a **Korean Command System** that give AI agents expert-level capabilities in specific domains.

### Why use shared skills?

| ❌ Copy-paste approach | ✅ Shared skills approach |
|------------------------|--------------------------|
| Skills duplicated in every project | Skills defined once |
| Update one = update all copies | Update once, sync everywhere |
| Version drift and inconsistency | Single source of truth |

---

## 📂 Skill Structure

```
skills/
└── skill-name/
    ├── SKILL.md        # Core skill definition (required)
    ├── scripts/        # Helper scripts (optional)
    ├── examples/       # Usage examples (optional)
    └── resources/      # Templates, assets (optional)
```

---

## 📚 Skill Categories (Detailed)

### 🎨 Creative & Design
`algorithmic-art`, `canvas-design`, `frontend-design`, `ui-ux-pro-max`, `theme-factory`

### 🛠️ Development & Engineering
`react-best-practices`, `typescript-expert`, `nextjs-best-practices`, `test-driven-development`, `systematic-debugging`

### 🔒 Security & Pentesting
`sql-injection-testing`, `xss-html-injection`, `aws-penetration-testing`, `red-team-tactics`

---

## 🤝 Contributing

1. Fork this repository
2. Create a new skill folder with `SKILL.md`
3. Follow the existing format
4. Submit a pull request

---

## 📜 License

MIT License - see [LICENSE](./LICENSE) for details.

---

Made with ❤️ for the Antigravity community
