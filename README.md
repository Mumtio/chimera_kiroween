# Chimera Protocol 🧟‍♂️

**Kiroween Hackathon 2025 - Frankenstein Category**

A neural-themed AI memory management system that stitches together multiple LLM providers, 3D brain visualization, and MCP (Model Context Protocol) into one monstrous creation.

![Chimera Protocol](https://img.shields.io/badge/Chimera-Protocol-cyan)
![Kiroween](https://img.shields.io/badge/Kiroween-Frankenstein-purple)
![License](https://img.shields.io/badge/license-MIT-green)
![Django](https://img.shields.io/badge/Django-5-green)
![React](https://img.shields.io/badge/React-18-blue)
![TypeScript](https://img.shields.io/badge/TypeScript-5-blue)
![Three.js](https://img.shields.io/badge/Three.js-3D-orange)

## ⭐ Watch the [Promo Video](https://youtu.be/5OHoeqZk0Es)

## 🧬 Why Chimera Protocol is the Ultimate Frankenstein Project

In Greek mythology, the Chimera was a monstrous creature made of parts from different animals - a lion's head, a goat's body, and a serpent's tail. **Chimera Protocol** embodies this spirit by stitching together competing AI providers that were never meant to work together into one unified, collaborative system.

### The Monster We Built

The AI industry is fragmented. OpenAI, Anthropic, Google, xAI, and DeepSeek all operate in isolation - different APIs, different strengths, different ecosystems. Users are forced to choose one provider or juggle multiple accounts and interfaces.

**Chimera Protocol stitches them all together.**

### What Makes It Monstrous

| The Problem | Our Frankenstein Solution |
|-------------|---------------------------|
| AI providers don't talk to each other | **Unified Multi-LLM Router** - One interface to rule them all |
| Each model has different strengths | **Model Switching** - Use GPT-4 for code, Claude for writing, Gemini for analysis, Grok for real-time info |
| AI has no persistent memory | **Memory Injection System** - Store knowledge and inject it into any model |
| Teams can't share AI context | **Collaborative Workspaces** - Teams share memories, conversations, and API keys |
| API keys scattered everywhere | **Encrypted Key Vault** - One secure place for all provider credentials |

### The Chimera's Many Heads

```
        🧠 OpenAI (GPT-4o, GPT-4)
       /
      🧠 Anthropic (Claude 3.5 Sonnet)
     /
🦁--🧠 Google (Gemini 2.0 Flash)
     \
      🧠 xAI (Grok-2)
       \
        🧠 DeepSeek (DeepSeek Chat)
```

Each "head" is a different AI provider, but they all share:
- **The same memory bank** - Inject context into any model
- **The same workspace** - Team members collaborate across providers
- **The same conversation history** - Switch models mid-conversation
- **The same secure storage** - One encrypted vault for all API keys

### Why This Matters

Most "multi-LLM" tools just let you pick a model. Chimera Protocol goes further:

1. **True Interoperability** - Memories created with Claude can be injected into GPT-4 conversations
2. **Team Collaboration** - Your team shares a unified AI workspace, not individual accounts
3. **Provider Agnostic** - Add a new provider? It instantly gets access to all your memories and context
4. **MCP Integration** - Model Context Protocol makes our memory system accessible to any MCP-compatible tool

This isn't just model switching - it's **AI unification**. We took competing, incompatible AI ecosystems and surgically combined them into one collaborative platform.

## 🧠 Overview

Chimera Protocol is a full-stack AI memory management platform that allows you to:

- **Chat with multiple AI models** - OpenAI, Anthropic, Google, DeepSeek, Grok
- **Store and manage memories** - Create, search, and organize AI context
- **Inject memories into conversations** - Provide persistent context to AI models
- **Visualize AI connections** - Interactive 3D brain with glowing model nodes
- **Collaborate with teams** - Workspace isolation with role-based access

## 📦 Repository Structure

This repository contains two submodules:

```
Chimera_Protocol/
├── Backend/     # Django REST API (Mad_Scientist)
└── Frontend/    # React/TypeScript UI (Necromancer)
```

| Component | Tech Stack | Description |
|-----------|------------|-------------|
| **Backend** | Django 5, Python 3.11+, PostgreSQL | REST API, LLM routing, memory storage, MCP tools |
| **Frontend** | React 18, TypeScript 5, Three.js, Tailwind | 3D brain visualization, chat interface, memory management |

## ⚡ How Kiro Was Used
Both [Frontend](Frontend) and [Backend](Backend) has /.kiro directories.

Kiro was instrumental in building Chimera Protocol, leveraging multiple features throughout development:

### Spec-Driven Development

The entire project was architected using Kiro's spec-driven approach. We created detailed specifications for:

- **Backend API Design** - Defined all endpoints, authentication flow, and data models in specs before implementation
- **Frontend Components** - Specified the 3D brain visualization, chat interface, and memory management UI
- **MCP Integration** - Documented the Model Context Protocol tools and their expected behaviors

The spec-driven approach allowed us to:
- Think through the architecture before writing code
- Generate consistent, well-structured implementations
- Iterate on designs with clear acceptance criteria
- Maintain documentation that stays in sync with code

### Steering Documents

We leveraged steering docs to maintain consistency across the codebase:

- **Code Style Guidelines** - Ensured consistent Python/TypeScript patterns
- **API Response Formats** - Standardized JSON structures across all endpoints
- **Component Architecture** - Defined reusable patterns for React components
- **Security Practices** - Embedded security requirements into every generation

### Agent Hooks

Automated workflows improved our development velocity:

- **Test Generation** - Hooks to auto-generate tests when new endpoints were created
- **Documentation Updates** - Automatic README updates when features changed
- **Migration Checks** - Validation hooks for database schema changes

### Vibe Coding Highlights

Some impressive code generations Kiro helped with:

- **LLM Router** - Generated the multi-provider routing logic that handles OpenAI, Anthropic, Google, DeepSeek, and Grok with a unified interface
- **3D Brain Visualization** - Created the Three.js scene with animated neural nodes and connection lines
- **Memory Injection System** - Built the context injection pipeline that seamlessly adds memories to AI conversations
- **Fernet Encryption Service** - Implemented secure API key storage with proper key rotation support

### MCP Integration

Kiro's MCP capabilities were essential for:

- Designing the memory tools (`remember`, `search`, `inject`, `listMemories`)
- Testing MCP endpoints during development
- Documenting the protocol for external integrations

## ✨ Features

### Multi-LLM Support
| Provider | Models | Status |
|----------|--------|--------|
| OpenAI | GPT-4o, GPT-4, GPT-3.5-turbo | ✅ |
| Anthropic | Claude 3.5 Sonnet, Claude 3 | ✅ |
| Google | Gemini 2.0 Flash, Gemini Pro | ✅ |
| DeepSeek | DeepSeek Chat, DeepSeek Coder | ✅ |
| Grok | Grok-2, Grok-2 Mini | ✅ |

### Memory System
- **Manual Creation** - Create memories with titles, content, and tags
- **URL Import** - Scrape and store content from web pages
- **File Import** - Import from documents
- **Auto-Extraction** - Extract memories from closed conversations
- **Semantic Search** - Find relevant memories by content

### 3D Brain Visualization
- Interactive Three.js brain model
- AI models displayed as glowing nodes
- Real-time connection visualization
- Cyberpunk-inspired neural theme

### Workspace & Team
- Isolated workspaces per project
- Team collaboration with invites
- Role-based access control
- Encrypted API key storage

## 🚀 Quick Start

### Clone with Submodules

```bash
git clone --recurse-submodules https://github.com/ahammadshawki8/Chimera_Protocol.git
cd Chimera_Protocol
```

If you already cloned without submodules:
```bash
git submodule update --init --recursive
```

### Backend Setup

```bash
cd Backend

# Create virtual environment
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Configure environment
cp .env.example .env
# Edit .env with your settings

# Generate encryption key
python generate_key.py

# Run migrations
python manage.py migrate

# Start server
python manage.py runserver
```

### Frontend Setup

```bash
cd Frontend

# Install dependencies
npm install

# Configure environment
cp .env.example .env.local
# Set VITE_API_BASE_URL=http://127.0.0.1:8000/api

# Start development server
npm run dev
```

## 🔧 Environment Variables

### Backend (.env)
```env
SECRET_KEY=your-django-secret-key
DEBUG=True
ALLOWED_HOSTS=localhost,127.0.0.1
DATABASE_URL=postgres://user:pass@localhost:5432/chimera
ENCRYPTION_KEY=your-fernet-key
GROK_API_KEY=your-grok-api-key
```

### Frontend (.env.local)
```env
VITE_API_BASE_URL=http://127.0.0.1:8000/api
```

## 🔌 API Highlights

| Endpoint | Description |
|----------|-------------|
| `POST /api/auth/register` | User registration |
| `POST /api/auth/login` | JWT authentication |
| `GET /api/workspaces` | List workspaces |
| `POST /api/conversations/{id}/messages` | Send chat message |
| `POST /api/conversations/{id}/inject-memory` | Inject memory context |
| `POST /api/memories/search` | Search memories |
| `POST /api/mcp/remember` | MCP: Store memory |
| `POST /api/mcp/inject` | MCP: Inject context |


## 🛠️ Development

### Backend
```bash
cd Backend
python manage.py runserver          # Start server
python manage.py makemigrations     # Create migrations
python manage.py migrate            # Apply migrations
python manage.py test               # Run tests
```

### Frontend
```bash
cd Frontend
npm run dev          # Development server
npm run build        # Production build
npm run lint         # Linting
npm run typecheck    # Type checking
npm run test         # Run tests
```

## 🔐 Security

- JWT authentication with refresh tokens
- Fernet encryption for API keys at rest
- CORS configuration
- Input validation
- SQL injection prevention via ORM

## 📄 License

MIT License - see [LICENSE](LICENSE) file

## 📚 Documentation

- [Backend README](Backend/README.md)
- [Frontend README](Frontend/README.md)
---

Built with 🧠 and ⚡ for **Kiroween Hackathon 2025** by [ahammadshawki8](https://github.com/ahammadshawki8) & [mumtio](https://github.com/Mumtio)