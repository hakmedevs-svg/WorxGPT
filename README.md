# WorxGPT

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub Stars](https://img.shields.io/github/stars/hakmedevs-svg/WorxGPT?style=flat-square)](https://github.com/hakmedevs-svg/WorxGPT/stargazers)
[![GitHub Issues](https://img.shields.io/github/issues/hakmedevs-svg/WorxGPT?style=flat-square)](https://github.com/hakmedevs-svg/WorxGPT/issues)
[![GitHub Forks](https://img.shields.io/github/forks/hakmedevs-svg/WorxGPT?style=flat-square)](https://github.com/hakmedevs-svg/WorxGPT/network/members)
[![Last Commit](https://img.shields.io/github/last-commit/hakmedevs-svg/WorxGPT?style=flat-square)](https://github.com/hakmedevs-svg/WorxGPT/commits)
[![Rating](https://img.shields.io/badge/Rating-⭐⭐⭐⭐⭐-brightgreen?style=flat-square)](https://github.com/hakmedevs-svg/WorxGPT)

---

<div align="center">

## 🚀 WorxGPT

### Your AI Workspace for Work, Code, Research, and Creation

**An advanced, production-ready AI platform that combines conversational AI, project analysis, web intelligence, and intelligent agent workflows into a unified workspace.**

[**🌐 Demo**](https://demo.worxgpt.io) • [**📖 Documentation**](https://docs.worxgpt.io) • [**📦 Releases**](https://github.com/hakmedevs-svg/WorxGPT/releases) • [**🤝 Telegram**](https://t.me/hhyr10) • [**💬 Discussions**](https://github.com/hakmedevs-svg/WorxGPT/discussions) • [**📋 Issues**](https://github.com/hakmedevs-svg/WorxGPT/issues)

</div>

---

## ✨ Overview

WorxGPT transcends traditional chatbots by addressing the fragmentation of modern development and research workflows. Instead of juggling multiple tools—chatbots, IDEs, research platforms, integrations, and project management systems—WorxGPT unifies them into one intelligent, powerful workspace.

### 🎯 What Makes WorxGPT Different?

| Feature | Description |
|---------|-------------|
| 🏗️ **Project-Aware Intelligence** | Upload entire codebases and let WorxGPT understand your architecture, dependencies, and coding patterns |
| 🌐 **Web Research Agent** | Autonomous AI that researches, synthesizes, and integrates information from across the web |
| 🔐 **Smart Integrations** | Secure OAuth-based connections to GitHub, Slack, Google Workspace, Notion, Jira, and more |
| 📦 **Workspace Organization** | Manage conversations, projects, files, and workflows separately for different contexts |
| 🤖 **AI Agent Workflows** | Build intelligent, multi-step agent chains that solve complex problems |
| 🌍 **Multilingual & Responsive** | Work in your language on any device with adaptive, modern interface |

---

## 🎨 Features Showcase

### 💬 Advanced AI Chat
- **Real-time streaming responses** from multiple AI providers
- **Context-aware conversations** with memory and retrieval
- **Model switching** mid-conversation
- **Conversation branching** for exploration

### 🧠 Multiple AI Models
- OpenAI GPT-4 & GPT-3.5
- Anthropic Claude
- Google Gemini
- Local model support (Ollama, LLaMA)
- Provider failover and load balancing

### 📁 File Upload & Analysis
- Multi-format support (PDF, DOCX, TXT, JSON, CSV, images)
- Document parsing and extraction
- Code snippet understanding and refactoring
- Image recognition and analysis
- Contextual file injection into conversations

### 🏗️ Uploaded Project System
The cornerstone of WorxGPT's power—upload entire projects for AI-driven development:

**Capabilities:**
- Automatic project structure mapping and visualization
- Dependency analysis and vulnerability detection
- Codebase review with quality suggestions
- Architecture understanding and documentation
- Automated error identification and fix generation
- File modification and intelligent code generation
- Build and deployment preparation

**Supported Project Types:**
```
✓ Node.js / JavaScript / TypeScript
✓ Python (Django, Flask, FastAPI)
✓ Go, Rust, and compiled languages
✓ Full-stack projects (monorepos)
✓ Container-based applications (Docker)
✓ Infrastructure-as-Code (Terraform, Kubernetes)
```

### 🌐 Web Agent & Research
- **Autonomous browsing** across the internet
- **Multi-source synthesis** into coherent findings
- **Fact verification** across sources
- **Real-time data collection** with citations
- **Use cases:** Competitor analysis, API discovery, trend tracking

### 🔌 Integrations & OAuth
Securely connect external platforms without exposing credentials:
- **GitHub** - Repository management, CI/CD
- **Slack** - Team notifications and commands
- **Google Workspace** - Drive, Docs, Sheets
- **Notion** - Workspace documentation
- **Jira** - Project tracking
- **Stripe** - Payment data and insights
- **Custom REST APIs** - via OAuth 2.0

**Security Model:** Encrypted token storage, automatic refresh, granular permissions, audit logging

### 🏢 Workspaces
Organize work across multiple contexts without data mixing:

| Feature | Benefit |
|---------|---------|
| **Isolation** | Independent conversation histories per workspace |
| **Access Control** | Role-based permissions for team members |
| **Customization** | Per-workspace AI models and integration settings |
| **Collaboration** | Shared resources and templates |

### 📝 Conversation Management
- Full-text search across conversation history
- Pinning, favorites, and tagging
- Export to PDF, Markdown, JSON
- Conversation sharing and collaboration
- Automatic summarization

### 🛠️ AI Coding Assistance
- Code generation from natural language specs
- Code review and refactoring suggestions
- Bug detection with fix recommendations
- Automated unit test generation
- Documentation generation
- Performance optimization
- Security vulnerability scanning

### 📊 Project Management
- Task creation from AI conversations
- Automatic issue identification and logging
- AI-assisted milestone planning
- Resource allocation recommendations
- Progress visualization

### 🌍 Multilingual Interface
Full support for: English, Spanish, French, German, Chinese, Japanese, Arabic, and more

### 🎨 Dark & Light Theme
System-level detection with manual toggle, high-contrast options, and custom schemes

### 📱 Responsive UI
- Desktop, tablet, and mobile optimization
- Progressive Web App (PWA) capabilities
- Offline mode support
- Touch-friendly interface
- Performance-optimized rendering

### 🤖 AI Agent Workflows
- Drag-and-drop workflow builder
- Conditional logic and branching
- Parallel task execution
- Tool integration and function calling
- Workflow scheduling and automation
- Performance monitoring

---

## 🏗️ Architecture

```mermaid
graph TB
    subgraph Client["🖥️ Client Layer"]
        UI["Web UI<br/>React + TypeScript"]
        PWA["PWA / Offline"]
    end

    subgraph API["🔌 API Layer"]
        Gateway["API Gateway<br/>Express / FastAPI"]
        Auth["Authentication<br/>OAuth 2.0 / JWT"]
        Chat["Chat Service<br/>WebSocket / gRPC"]
    end

    subgraph Core["⚙️ Core Services"]
        Conv["Conversation Manager"]
        Project["Project Analyzer"]
        Agent["Web Agent Engine"]
        Integration["Integration Hub"]
    end

    subgraph AI["🧠 AI & LLM Layer"]
        Router["Model Router"]
        OpenAI["OpenAI GPT-4"]
        Claude["Anthropic Claude"]
        Gemini["Google Gemini"]
        Local["Local Models"]
    end

    subgraph Data["💾 Data Layer"]
        Cache["Redis Cache"]
        DB["PostgreSQL"]
        VecDB["Vector DB"]
        Storage["Object Storage<br/>S3"]
        Search["ElasticSearch"]
    end

    subgraph External["🌐 External"]
        Web["Web Crawling"]
        OAuth["OAuth Providers"]
        Tools["External APIs"]
    end

    UI --> Gateway
    PWA --> Gateway
    Gateway --> Auth
    Gateway --> Chat
    Chat --> Conv
    Chat --> Project
    Chat --> Agent
    Conv --> Router
    Project --> Router
    Agent --> Router
    Router --> OpenAI
    Router --> Claude
    Router --> Gemini
    Router --> Local
    Conv --> Cache
    Conv --> DB
    Conv --> VecDB
    Project --> Storage
    Project --> Search
    Agent --> Web
    Integration --> OAuth
    Integration --> Tools

    style Client fill:#e1f5ff,stroke:#01579b,stroke-width:2px
    style API fill:#f3e5f5,stroke:#4a148c,stroke-width:2px
    style Core fill:#e8f5e9,stroke:#1b5e20,stroke-width:2px
    style AI fill:#fff3e0,stroke:#e65100,stroke-width:2px
    style Data fill:#fce4ec,stroke:#880e4f,stroke-width:2px
    style External fill:#f1f8e9,stroke:#33691e,stroke-width:2px
```

---

## 🛠️ Technology Stack

| Layer | Technologies |
|-------|--------------|
| **Frontend** | React 18+, TypeScript 5+, Tailwind CSS, Redux/Zustand |
| **Backend** | Node.js 18+ / Python 3.10+, Express / FastAPI, WebSocket |
| **Database** | PostgreSQL 14+, Redis 7+, Vector DB (Pinecone/Weaviate) |
| **Search** | ElasticSearch 8+ |
| **Auth** | OAuth 2.0 (RFC 6749), JWT (RS256) |
| **AI Providers** | OpenAI API, Anthropic API, Google Gemini, Ollama |
| **Storage** | AWS S3 / MinIO |
| **Deployment** | Docker, Kubernetes 1.27+, Docker Compose |
| **Monitoring** | Prometheus, Grafana, Sentry |

---

## 📂 Project Structure

```
WorxGPT/
├── frontend/                    # React web application
│   ├── src/
│   │   ├── components/         # Reusable UI components
│   │   ├── pages/              # Page components
│   │   ├── services/           # API services
│   │   ├── store/              # State management
│   │   ├── hooks/              # Custom hooks
│   │   ├── utils/              # Utilities
│   │   └── styles/             # Tailwind & CSS
│   ├── public/
│   └── package.json
│
├── backend/                     # API server
│   ├── src/
│   │   ├── api/                # Routes & controllers
│   │   ├── services/           # Business logic
│   │   ├── models/             # Data models
│   │   ├── middleware/         # Express/FastAPI middleware
│   │   ├── auth/               # Authentication
│   │   ├── integrations/       # Third-party services
│   │   ├── ai/                 # AI model interfaces
│   │   ├── agents/             # AI agent implementations
│   │   ├── analyzers/          # Project analysis
│   │   ├── database/           # DB connection
│   │   └── utils/              # Helpers
│   ├── config/
│   ├── migrations/
│   ├── tests/
│   └── Dockerfile
│
├── docs/                        # Documentation
│   ├── api/                    # OpenAPI/Swagger
│   ├── guides/                 # User guides
│   ├── architecture/           # Architecture docs
│   └── contributing.md
│
├── .github/
│   ├── workflows/              # CI/CD pipelines
│   ├── ISSUE_TEMPLATE/
│   └── PULL_REQUEST_TEMPLATE.md
│
├── docker-compose.yml
├── .env.example
├── .gitignore
├── LICENSE
├── CONTRIBUTING.md
├── CHANGELOG.md
└── README.md
```

---

## 🚀 Quick Start

### Prerequisites
- **Node.js** 18+ or **Python** 3.10+
- **Docker** & **Docker Compose**
- **PostgreSQL** 14+ (or use Docker)
- **Redis** 7+ (or use Docker)

### Option 1: Docker Compose (Recommended)

```bash
# 1. Clone repository
git clone https://github.com/hakmedevs-svg/WorxGPT.git
cd WorxGPT

# 2. Configure environment
cp .env.example .env
# Edit .env with your API keys

# 3. Start all services
docker-compose up -d

# 4. Initialize database
docker-compose exec backend npm run migrate

# 5. Access application
open http://localhost:3000
```

### Option 2: Local Development

```bash
# Clone repository
git clone https://github.com/hakmedevs-svg/WorxGPT.git
cd WorxGPT

# Frontend setup
cd frontend
npm install
npm run dev

# Backend setup (in new terminal)
cd backend
npm install
cp .env.example .env
npm run migrate
npm run dev

# Access at http://localhost:3000
```

---

## 🔧 Configuration

### Environment Variables

```env
# Application
NODE_ENV=development
PORT=5000
FRONTEND_URL=http://localhost:3000
BACKEND_URL=http://localhost:5000

# Database
DATABASE_URL=postgresql://user:password@localhost:5432/worxgpt
REDIS_URL=redis://localhost:6379

# AI Providers
OPENAI_API_KEY=sk-YOUR_KEY_HERE
OPENAI_MODEL=gpt-4
ANTHROPIC_API_KEY=sk-ant-YOUR_KEY_HERE
GOOGLE_API_KEY=YOUR_KEY_HERE

# Authentication
JWT_SECRET=YOUR_SECURE_SECRET_HERE
JWT_EXPIRATION=24h

# Integrations (OAuth)
GITHUB_CLIENT_ID=YOUR_ID
GITHUB_CLIENT_SECRET=YOUR_SECRET
SLACK_CLIENT_ID=YOUR_ID
SLACK_CLIENT_SECRET=YOUR_SECRET
GOOGLE_CLIENT_ID=YOUR_ID
GOOGLE_CLIENT_SECRET=YOUR_SECRET

# Storage
AWS_ACCESS_KEY_ID=YOUR_KEY
AWS_SECRET_ACCESS_KEY=YOUR_SECRET
AWS_S3_BUCKET=worxgpt-files

# Security
RATE_LIMIT_REQUESTS=100
RATE_LIMIT_WINDOW=15m
CORS_ORIGIN=http://localhost:3000
```

**⚠️ Important:** Never commit `.env` to version control!

---

## 💡 Usage Guide

### Start a Conversation
1. Navigate to Chat interface
2. Select your AI model (GPT-4, Claude, Gemini)
3. Type your message and press Enter
4. Stream responses in real-time

### Upload Files
1. Click "Upload" button
2. Select documents, code, images, or datasets
3. Reference with `@filename` in conversations
4. AI automatically analyzes and provides insights

### Upload a Project
1. Click "Upload Project"
2. Select project directory or Git repository
3. WorxGPT indexes entire codebase
4. Ask questions, request fixes, or generate features
5. Export modified files

### Create Workspaces
1. Click "+" next to Workspaces
2. Enter name and description
3. Configure AI models and integrations
4. Invite team members
5. Switch between workspaces

### Use Web Agent
```
In conversation, type: "Research: [your query]"
→ Agent autonomously browses and synthesizes
→ Results with source citations returned
→ Use findings in further workflow
```

### Connect Integrations
1. Settings → Integrations
2. Click "Connect" for desired service
3. Authorize via OAuth
4. Grant permissions
5. Start using in conversations

---

## 🗺️ Roadmap

### ✅ Completed
- [x] Core chat with streaming responses
- [x] Multiple AI models support
- [x] File upload and analysis
- [x] Workspace management
- [x] Project upload
- [x] Conversation history & search
- [x] Dark/Light theme
- [x] Responsive design
- [x] OAuth integrations
- [x] GitHub integration

### 🚀 In Progress
- [ ] Advanced project AST parsing
- [ ] Web Agent autonomous research
- [ ] Workflow builder (drag-and-drop)
- [ ] Code patches with git integration
- [ ] Team collaboration features
- [ ] Performance optimization
- [ ] Kubernetes templates

### 📋 Planned
- [ ] Voice input & audio processing
- [ ] Custom model fine-tuning
- [ ] Plugin marketplace
- [ ] Advanced analytics & reporting
- [ ] Mobile apps (iOS/Android)
- [ ] Offline-first architecture
- [ ] Blockchain audit logging
- [ ] Enterprise SSO & RBAC
- [ ] GraphQL API
- [ ] Real-time collaborative editing

---

## 🔒 Security

### Core Security Measures

#### API Key Protection
- ✅ AES-256-GCM encryption for API keys
- ✅ Automatic credential rotation
- ✅ Per-user encrypted vaults
- ✅ Zero-knowledge architecture

#### OAuth Token Management
- ✅ Encrypted at rest and in transit
- ✅ Automatic server-side refresh
- ✅ Granular permission scoping
- ✅ Instant revocation capability

#### User Authentication
- ✅ Cryptographically signed JWT tokens
- ✅ Session invalidation on logout
- ✅ HTTPS-only production deployments
- ✅ CSRF protection on all mutations

#### File Upload Security
- ✅ ClamAV virus scanning
- ✅ MIME type validation
- ✅ Configurable size limits
- ✅ Sandboxed analysis
- ✅ Access control per user/workspace

#### Rate Limiting
- ✅ 100 requests/15 minutes per user
- ✅ Fair-use model limits
- ✅ WebSocket connection limits
- ✅ DDoS protection (Cloudflare recommended)

### Deployment Best Practices
1. **Enable HTTPS** with Let's Encrypt
2. **Strong JWT Secret** (32+ characters)
3. **Database Encryption** at rest
4. **Network Security** (Firewalls, VPCs)
5. **Audit Logging** and alerting
6. **Regular Updates** of dependencies
7. **Penetration Testing**
8. **Incident Response Plan**

---

## 📋 Issues & Bug Reports

Found a bug or have a feature request? We'd love to hear from you!

### How to Report Issues
1. **Search existing issues** before opening new ones
2. **Be descriptive** with clear reproduction steps
3. **Include environment details** (OS, Node version, etc.)
4. **Attach logs or screenshots** if relevant
5. **Use issue templates** for consistency

### View Issues
👉 [**Browse All Issues**](https://github.com/hakmedevs-svg/WorxGPT/issues)

---

## 💬 Community & Feedback

We value your feedback and engagement! Here's how to connect:

### Discussion Forum
💭 [**GitHub Discussions**](https://github.com/hakmedevs-svg/WorxGPT/discussions) - Share ideas, ask questions, and connect with the community

### Direct Contact
📱 [**Telegram: @hhyr10**](https://t.me/hhyr10) - Connect with HakmeDev directly for support and feedback

### Report Issues
🐛 [**GitHub Issues**](https://github.com/hakmedevs-svg/WorxGPT/issues) - Report bugs and request features

### Community Guidelines
- Be respectful and constructive
- Search before asking to avoid duplicates
- Provide detailed context and examples
- Help other community members
- Follow our [Code of Conduct](./CONTRIBUTING.md#code-of-conduct)

---

## ⭐ Star & Rating

If you find WorxGPT helpful, please consider:
- ⭐ **Starring the repository** on [GitHub](https://github.com/hakmedevs-svg/WorxGPT)
- 📢 **Sharing** with your network
- 💬 **Providing feedback** via issues or discussions
- 🤝 **Contributing** to the project

Your support helps us improve and grow!

---

## 🤝 Contributing

We welcome contributions of all kinds! Please read our [Contributing Guide](./CONTRIBUTING.md) for details.

### How to Contribute
1. **Fork** the repository
2. **Create** feature branch: `git checkout -b feature/your-feature`
3. **Make changes** and commit: `git commit -m 'feat: add feature'`
4. **Push** to branch: `git push origin feature/your-feature`
5. **Open Pull Request** with clear description

### Types of Contributions
- 🐛 Bug fixes
- ✨ New features
- 📚 Documentation
- 🧪 Tests
- ♿ Accessibility
- 🌍 Translations

### Development Standards
- **Linting**: ESLint (JS), Pylint (Python)
- **Formatting**: Prettier
- **Type Safety**: TypeScript
- **Testing**: Jest/pytest (80%+ coverage)

### Commit Convention
Follow [Conventional Commits](https://www.conventionalcommits.org/):
```
feat(scope): description
fix(scope): description
docs: description
style: description
test: description
```

---

## 📄 License

WorxGPT is licensed under the **MIT License**. You are free to:

- ✅ Use for commercial purposes
- ✅ Modify the code
- ✅ Distribute
- ✅ Use privately

With the condition that you include a copy of the license and original copyright notice.

See [LICENSE](./LICENSE) for full text.

---

## 📝 Changelog

Track all changes and releases in our [CHANGELOG](./CHANGELOG.md)

Latest releases and updates: [**GitHub Releases**](https://github.com/hakmedevs-svg/WorxGPT/releases)

---

## 🙏 Credits & Acknowledgments

### WorxGPT
A modern AI workspace platform built with modern technologies and best practices.

**Repository**: https://github.com/hakmedevs-svg/WorxGPT

### Developer
**HakmeDev** - AI/Web Development & Open Source

- 🐙 **GitHub**: [@hakmedevs-svg](https://github.com/hakmedevs-svg)
- 🌐 **Website**: [hakmdev.io](https://hakmdev.io)
- 📱 **Telegram**: [@hhyr10](https://t.me/hhyr10)
- 📧 **Email**: dev@hakmdev.io

### Special Thanks
- The open-source community for incredible frameworks and tools
- OpenAI, Anthropic, and Google for world-class AI models
- All contributors and users helping improve WorxGPT
- The developers behind React, TypeScript, Node.js, and all technologies used

### Technologies & Libraries
- [React](https://react.dev) - UI library
- [TypeScript](https://www.typescriptlang.org) - Type safety
- [Node.js](https://nodejs.org) - Runtime
- [Express](https://expressjs.com) - Web framework
- [PostgreSQL](https://www.postgresql.org) - Database
- [Redis](https://redis.io) - Caching
- [Tailwind CSS](https://tailwindcss.com) - Styling
- [Docker](https://www.docker.com) - Containerization

---

## 📞 Support & Help

### Documentation
📖 [**Full Documentation**](https://docs.worxgpt.io)

### Getting Help
- 📖 Read the [documentation](https://docs.worxgpt.io)
- 🔍 Search [existing issues](https://github.com/hakmedevs-svg/WorxGPT/issues)
- 💬 Ask in [GitHub Discussions](https://github.com/hakmedevs-svg/WorxGPT/discussions)
- 📱 Contact on [Telegram @hhyr10](https://t.me/hhyr10)

### Stay Updated
- 🌟 Star the repository for updates
- 🔔 Watch for releases
- 📧 Subscribe to our [changelog](https://github.com/hakmedevs-svg/WorxGPT/releases)

---

## 🎯 Project Stats

| Metric | Status |
|--------|--------|
| **License** | MIT |
| **Status** | Active Development |
| **Node Version** | 18+ |
| **Python Version** | 3.10+ |
| **Last Updated** | 2026-10-03 |
| **Contributors** | Open to contributions |
| **Code Coverage** | Improving continuously |

---

<div align="center">

## 🌟 WorxGPT

### Your AI Workspace for Work, Code, Research, and Creation

**Empowering developers and teams with intelligent AI assistance**

---

### Quick Links

[🌐 Homepage](https://worxgpt.io) • [📖 Docs](https://docs.worxgpt.io) • [🎮 Demo](https://demo.worxgpt.io) • [📱 Telegram](https://t.me/hhyr10) • [💬 Discussions](https://github.com/hakmedevs-svg/WorxGPT/discussions) • [🐛 Issues](https://github.com/hakmedevs-svg/WorxGPT/issues) • [⭐ Star Us](https://github.com/hakmedevs-svg/WorxGPT)

---

### Follow the Developer

**HakmeDev** - Passionate about AI, Web Development & Open Source

[GitHub](https://github.com/hakmedevs-svg) • [Telegram](https://t.me/hhyr10) • [Website](https://hakmdev.io)

---

Made with ❤️ by [HakmeDev](https://github.com/hakmedevs-svg)

**Building the future of AI-powered development, one line of code at a time.**

---

### Give us a Star ⭐

If you find WorxGPT useful, please consider giving us a star on GitHub. It helps us grow and motivates the team!

[⭐ Star WorxGPT](https://github.com/hakmedevs-svg/WorxGPT/stargazers)

</div>
