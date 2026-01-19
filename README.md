# Chimera Protocol 🧠

## Multi-LLM Memory Management System for AI Collaboration

Chimera Protocol is an innovative neural-themed AI memory management system that seamlessly stitches together multiple AI model providers, offers a persistent memory framework, and integrates various cutting-edge technologies. It combines powerful features into a single, collaborative platform designed to tackle the fragmentation in the AI space.

---

## Why Chimera Protocol is a Game-Changer

The AI landscape is fragmented with different providers such as OpenAI, Anthropic, Google, and others, each with their unique strengths, APIs, and ecosystems. Users often have to navigate these fragmented systems separately, making the user experience inefficient.

Chimera Protocol unifies these diverse AI providers into a single platform that allows for efficient collaboration, memory management, and seamless model switching.

---

## Key Features

### 1. **Multi-LLM Support**
   - **Provider Agnostic:** OpenAI, Anthropic, Google, DeepSeek, and more.
   - **Model Switching:** Seamlessly switch models with specialized capabilities, such as using GPT-4 for code, Claude for writing, and Gemini for analysis.
   - **Persistent Memory:** Store memories and inject them into any model across the platform.

### 2. **Memory Management System**
   - **Manual Memory Creation:** Create and tag memories with titles and content.
   - **Web and File Import:** Scrape content from websites or import documents.
   - **Auto-Extraction:** Extract memories automatically from closed conversations.
   - **Search & Semantic Search:** Find and retrieve relevant memories by their content.

### 3. **Collaborative Workspaces**
   - **Team Collaboration:** Share memories, conversations, and API keys in isolated workspaces.
   - **Role-Based Access:** Manage access and roles for your team members to collaborate securely.

### 4. **3D Brain Visualization**
   - **Interactive 3D Model:** View and interact with the 3D brain model showing AI models as glowing nodes.
   - **Cyberpunk-inspired Theme:** A futuristic, glowing neural theme with connections visualized in real-time.

---

## The Problem and Our Solution

| **The Problem**                            | **Our Solution**                                      |
|--------------------------------------------|-------------------------------------------------------|
| **AI providers operate in isolation.**     | **Unified Multi-LLM Router:** One interface for managing all your AI models. |
| **Each AI model has unique strengths.**     | **Model Switching:** Seamlessly switch models based on task specialization. |
| **Lack of persistent memory.**             | **Memory Injection System:** Store, manage, and inject memory into models. |
| **Teams can't share AI context.**          | **Collaborative Workspaces:** Teams can share context and memory across providers. |
| **API keys scattered across multiple systems.** | **Encrypted Key Vault:** Secure, centralized API key management. |

---

## How It Works

Chimera Protocol combines different AI providers under one system, creating a collaborative and efficient environment for users:

1. **Unified Interface:** Communicate with multiple AI models (e.g., GPT-4, Claude, Gemini, etc.) using a single interface.
2. **Memory Sharing:** Store and share memories with your team, allowing seamless context exchange across different models.
3. **Secure API Keys:** Manage your API keys securely in an encrypted vault, reducing the risk of key leaks.

---

## Technology Stack

### Backend
- **Django 5** - Python 3.11+, PostgreSQL  
  - REST API, multi-LLM routing, memory storage, and encryption.
  
### Frontend
- **React 18**, **TypeScript 5**, **Three.js**, **Tailwind**  
  - 3D brain visualization, interactive UI for managing memories, and AI chat interface.

---

## Repository Structure

This repository contains two main submodules:

```
Chimera_Protocol/
├── Backend/   # Django REST API (Main backend system)
└── Frontend/  # React/TypeScript UI (Frontend interface)
```

---

## Core Features

### **Multi-LLM Support**
- **Supported Providers:**
  - **OpenAI**: GPT-4, GPT-3.5-turbo
  - **Anthropic**: Claude 3.5 Sonnet, Claude 3
  - **Google**: Gemini 2.0 Flash, Gemini Pro
  - **DeepSeek**: DeepSeek Chat, DeepSeek Coder
  - **Grok**: Grok-2, Grok-2 Mini

### **Memory System**
- **Create Memories:** Store, organize, and manage memories across all models.
- **Import from Web/Files:** Automatically extract content to create memories.
- **Search Memories:** Use semantic search to find specific memories.

### **3D Brain Visualization**
- **Interactive Visualization:** View and interact with the 3D brain model showing AI models as glowing nodes.
- **Cyberpunk-inspired Theme:** A futuristic, glowing neural theme with connections visualized in real-time.

### **Collaborative Workspaces**
- **Workspace Isolation:** Isolate projects and teams for better privacy.
- **Team Collaboration:** Team members can share memories and API keys securely.

### **Secure Key Vault**
- **Encrypted Vault:** Store and manage all your API keys in one secure location.

---

## Quick Start Guide

### Clone Repository with Submodules

```bash
git clone --recurse-submodules https://github.com/your-username/Chimera_Protocol.git
cd Chimera_Protocol
```

### Backend Setup

**Create Virtual Environment**

```bash
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
```

**Install Dependencies**

```bash
pip install -r requirements.txt
```

**Configure Environment**

Copy `.env.example` to `.env` and update the configuration as needed.

**Generate Encryption Key**

```bash
python generate_key.py
```

**Apply Migrations**

```bash
python manage.py migrate
```

**Run Server**

```bash
python manage.py runserver
```

### Frontend Setup

**Install Dependencies**

```bash
npm install
```

**Configure Environment**

Copy `.env.example` to `.env.local` and set the API base URL.

**Run Development Server**

```bash
npm run dev
## API Endpoints

| Endpoint | Description |
|----------|-------------|
| `POST /api/auth/register` | User registration |
| `POST /api/auth/login` | JWT authentication |
| `GET /api/workspaces` | List all workspaces |
| `POST /api/conversations/{id}/messages` | Send a chat message |
| `POST /api/conversations/{id}/inject-memory` | Inject memory context |
| `POST /api/memories/search` | Search memories |
| `POST /api/mcp/remember` | Store memory via MCP |
| `POST /api/mcp/inject` | Inject memory via MCP |

---

## Development Setup

### Backend

**Start Server**

```bash
python manage.py runserver
```

**Run Tests**

```bash
python manage.py test
```

### Frontend

**Start Development Server**

```bash
npm run dev
```

**Run Linting**

```bash
npm run lint
```

---

## Security Features

- JWT Authentication with refresh tokens
- Fernet Encryption for API keys at rest
- CORS Configuration and Input Validation
- SQL Injection Prevention via Django ORM

---

## License

MIT License - see [LICENSE](LICENSE) file for details.

## Documentation

- [Backend README](Backend/README.md)
- [Frontend README](Frontend/README.md)


