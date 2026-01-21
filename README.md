# 🚀 Antigravity Awesome Skills

> A curated collection of 200+ reusable AI agent skills for Antigravity-powered development workflows.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Skills](https://img.shields.io/badge/Skills-200%2B-blue.svg)](#-skill-categories)

[English](#-quick-start) | [한국어](#-한국어-가이드)

---

## ✨ What is this?

This repository contains **modular skill definitions** that give AI agents expert-level capabilities in specific domains (full-stack development, design, security testing, etc.). Think of it as a **shared skill library** that any project can plug into.

### Why use shared skills?

| ❌ Copy-paste approach | ✅ Shared skills approach |
|------------------------|--------------------------|
| Skills duplicated in every project | Skills defined once |
| Update one = update all copies | Update once, sync everywhere |
| Version drift and inconsistency | Single source of truth |

---

## 🚀 Quick Start

### Option 1: Git Submodule (Recommended)

Add this repository as a submodule to your project's `.agent` directory:

```bash
# In your project root
git submodule add https://github.com/YOUR_USERNAME/antigravity-awesome-skills .agent
```

Your project structure will look like:
```
your-project/
├── .agent/
│   ├── skills/          ← This repository's skills folder
│   │   ├── 3d-web-experience/
│   │   ├── react-best-practices/
│   │   └── ...
│   ├── README.md
│   └── LICENSE
├── src/
└── ...
```

### Option 2: Direct Clone (to .agent)

```bash
git clone https://github.com/YOUR_USERNAME/antigravity-awesome-skills .agent
```

---

## 📂 Skill Structure

Each skill follows this structure:

```
skills/
└── skill-name/
    ├── SKILL.md        # Core skill definition (required)
    ├── scripts/        # Helper scripts (optional)
    ├── examples/       # Usage examples (optional)
    └── resources/      # Templates, assets (optional)
```

### SKILL.md Format

```yaml
---
name: skill-name
description: "Brief description of what this skill does"
source: original-source (license)
---

# Skill Name

Detailed instructions, patterns, and anti-patterns...
```

---

## 📚 Skill Categories

### 🎨 Creative & Design
| Skill | Description |
|-------|-------------|
| `algorithmic-art` | Create generative art with p5.js |
| `canvas-design` | Design posters and artwork (PNG/PDF) |
| `frontend-design` | Production-ready UI components |
| `ui-ux-pro-max` | Professional UI/UX design system |
| `theme-factory` | Generate consistent themes |

### 🛠️ Development & Engineering
| Skill | Description |
|-------|-------------|
| `react-best-practices` | React patterns and conventions |
| `typescript-expert` | TypeScript best practices |
| `nextjs-best-practices` | Next.js development guide |
| `test-driven-development` | TDD workflow |
| `systematic-debugging` | Structured debugging approach |

### 🔒 Security & Pentesting
| Skill | Description |
|-------|-------------|
| `sql-injection-testing` | SQL injection testing |
| `xss-html-injection` | XSS vulnerability testing |
| `aws-penetration-testing` | AWS security testing |
| `red-team-tactics` | Red team methodologies |

### 📄 Documentation & Office
| Skill | Description |
|-------|-------------|
| `docx` | Create/edit Word documents |
| `xlsx` | Create/edit Excel spreadsheets |
| `pptx` | Create/edit PowerPoint |
| `pdf` | PDF processing and editing |

### 📅 Planning & Workflow
| Skill | Description |
|-------|-------------|
| `brainstorming` | Structured ideation |
| `writing-plans` | Detailed execution plans |
| `planning-with-files` | File-based planning system |

[View all 200+ skills →](./scripts/)

---

## 🔄 Keeping Skills Updated

If using as a submodule:

```bash
# Update to latest version
git submodule update --remote

# Commit the update
git add .agent
git commit -m "chore: update shared skills"
```

---

## 🛠️ Utility Scripts

| Script | Purpose |
|--------|---------|
| `scripts/generate_index.py` | Generate skills index JSON |
| `scripts/validate_skills.py` | Validate skill format |
| `scripts/skills_manager.py` | Manage skill collection |

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

# 🇰🇷 한국어 가이드

## 이게 뭔가요?

여러 프로젝트에서 **공용으로 사용하는 AI 에이전트 스킬 모음집**입니다.

프로젝트마다 스킬을 복사하는 대신, 이 저장소를 **서브모듈로 연결**해서 사용하세요!

## 사용 방법

### 1단계: 프로젝트에 연결

```bash
# 프로젝트 루트 폴더에서 실행
git submodule add https://github.com/YOUR_USERNAME/antigravity-awesome-skills .agent
```

### 2단계: 스킬 사용

대화창에서 `@skill-name` 또는 `/skill-name`으로 호출:

```
/canvas-design 블로그 표지 디자인해줘. 테마는 AI 기술, 스타일은 모던하게.
```

### 3단계: 업데이트

```bash
git submodule update --remote
git add .agent
git commit -m "스킬 업데이트"
```

## ⚠️ 주의사항

- `.agent/skills/` 폴더 안에서 **직접 수정하지 마세요**
- 수정이 필요하면 **이 저장소에서 수정** 후 업데이트하세요

---

Made with ❤️ for the Antigravity community
