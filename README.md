# WorxGPT

<div align="center">
  <img src="https://raw.githubusercontent.com/hakmedevs-svg/WorxGPT/main/assets/worxgpt-logo.svg" alt="WorxGPT Logo" width="140" />
  <br/>
  <img src="https://raw.githubusercontent.com/hakmedevs-svg/WorxGPT/main/assets/worxgpt-banner.svg" alt="WorxGPT Banner" width="100%" />
</div>

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub Stars](https://img.shields.io/github/stars/hakmedevs-svg/WorxGPT?style=flat-square)](https://github.com/hakmedevs-svg/WorxGPT/stargazers)
[![GitHub Issues](https://img.shields.io/github/issues/hakmedevs-svg/WorxGPT?style=flat-square)](https://github.com/hakmedevs-svg/WorxGPT/issues)
[![GitHub Forks](https://img.shields.io/github/forks/hakmedevs-svg/WorxGPT?style=flat-square)](https://github.com/hakmedevs-svg/WorxGPT/network/members)
[![Last Commit](https://img.shields.io/github/last-commit/hakmedevs-svg/WorxGPT?style=flat-square)](https://github.com/hakmedevs-svg/WorxGPT/commits)

<div align="center">

[🇸🇦 العربية](./README_AR.md) • [🇬🇧 English](./README_EN.md)

</div>

---

## Overview

WorxGPT is a modern AI workspace built to deliver a premium, intelligent assistant experience for work, research, code, automation, and project understanding. It brings together conversational AI, file analysis, project inspection, web research, integrations, and multi-step AI workflows in a single platform.

This project is designed for developers, teams, and creators who want a serious AI tool that feels like a complete digital workspace instead of a simple chatbot.

---

## Why WorxGPT?

- AI chat with context-aware conversation
- Upload files and analyze them intelligently
- Review and understand software projects
- Perform web research and analysis
- Connect external systems securely via OAuth
- Organize work inside separate workspaces
- Build agent-based workflows using AI tools

---

## Core Features

### AI Chat
- Conversational interface with streaming responses
- Multiple model support
- Memory and contextual awareness
- Prompt-driven productivity workflows

### Project Analysis
- Upload existing codebases and inspect structure
- Understand project architecture and dependencies
- Identify issues and suggest improvements
- Generate fixes and implementation ideas

### File Intelligence
- Upload documents, PDFs, text, JSON, CSV, images, and code files
- Ask AI to summarize, explain, or transform content

### Web Agent
- Search and research across the web
- Collect relevant information from sources
- Synthesize findings into structured results

### Integrations
- GitHub, Slack, Google Workspace, Notion, Jira, and more
- Secure OAuth-based authorization model
- Safe handling of access tokens

### Workspaces
- Group projects, files, prompts, and chats by purpose
- Keep work separated by team, client, or initiative

---

## Architecture

```mermaid
graph TD
    User[User] --> UI[WorxGPT UI]
    UI --> API[Backend / API]
    API --> AI[AI Models]
    API --> Files[File System / Storage]
    API --> Web[Web Agent]
    API --> Int[Integrations]
    API --> DB[Database]
    Files --> Project[Project Analyzer]
    Web --> Research[Web Research Engine]
    Int --> OAuth[OAuth Providers]
```

---

## Technology Stack

| Layer | Stack |
|---|---|
| Frontend | React, TypeScript, Tailwind CSS |
| Backend | Node.js / Python, REST APIs, WebSockets |
| Data | PostgreSQL, Redis, Vector DB |
| AI Providers | OpenAI, Anthropic, Google Gemini, local models |
| Storage | S3-compatible object storage |
| Auth | OAuth 2.0, JWT |
| Deployment | Docker, Kubernetes, CI/CD |

---

## Project Structure

```text
WorxGPT/
├── assets/
│   ├── worxgpt-logo.svg
│   └── worxgpt-banner.svg
├── README.md
├── README_AR.md
├── README_EN.md
├── .github/
├── docs/
├── frontend/
├── backend/
├── docker-compose.yml
├── .env.example
├── .gitignore
├── LICENSE
├── CHANGELOG.md
├── CONTRIBUTING.md
└── package.json
```

---

## Installation

```bash
git clone https://github.com/hakmedevs-svg/WorxGPT.git
cd WorxGPT
cp .env.example .env
npm install
npm run dev
```

For production or full-stack setup, see the detailed guides in the translated documentation files.

---

## Environment Variables

```env
OPENAI_API_KEY=YOUR_OPENAI_KEY
ANTHROPIC_API_KEY=YOUR_ANTHROPIC_KEY
GOOGLE_API_KEY=YOUR_GOOGLE_KEY
DATABASE_URL=postgresql://user:password@localhost:5432/worxgpt
JWT_SECRET=YOUR_SECRET_KEY
REDIS_URL=redis://localhost:6379
```

---

## Usage

1. Open the app and sign in.
2. Start a new AI chat.
3. Upload documents or project folders.
4. Ask for analysis, code review, or summary.
5. Use the Web Agent for research tasks.
6. Create workspaces to organize tasks and conversations.
7. Connect integrations securely with OAuth.

---

## Roadmap

### Completed
- [x] AI chat foundation
- [x] File upload and analysis
- [x] Workspace concept
- [x] Project review workflows
- [x] Documentation and multilingual support

### In Progress
- [ ] Advanced project analysis
- [ ] Web agent enhancements
- [ ] Workflow automation builder
- [ ] Team collaboration features

### Planned
- [ ] Mobile UI improvements
- [ ] Enterprise integrations
- [ ] Agent marketplace
- [ ] More analytics and reporting

---

## Security

- Protect API keys and secrets in environment files
- Use secure OAuth flows for integrations
- Encrypt tokens and validate permissions
- Limit file uploads and sanitize inputs
- Use HTTPS in production

---

## Issues, Feedback & Community

- Issues: https://github.com/hakmedevs-svg/WorxGPT/issues
- Discussions: https://github.com/hakmedevs-svg/WorxGPT/discussions
- Developer Telegram: https://t.me/hhyr10

---

## Contributing

Pull requests are welcome. Please keep changes clear, documented, and tested.

---

## License

This project is licensed under the MIT License.

---

## Credits

- Project: WorxGPT
- Developer: HakmeDev
- Contact: @hhyr10 on Telegram

---

<div align="center">

## WorxGPT — Your AI Workspace for Work, Code, Research, and Creation

</div>
