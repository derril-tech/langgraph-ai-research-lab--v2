# 🔬 AI Research Lab
**Powered by LangGraph + OpenAI**

🌐 **[View Live Application](https://langgraph-ai-research-lab.vercel.app)**

> **Turn complex research questions into structured briefs. Ask any question, watch the AI pipeline orchestrate literature search, critical analysis, and evidence evaluation—delivering comprehensive research briefs with competing viewpoints and confidence scores in seconds.** ⚡

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.11+-blue.svg)](https://www.python.org/downloads/)
[![Next.js](https://img.shields.io/badge/Next.js-16-black.svg)](https://nextjs.org/)
[![React](https://img.shields.io/badge/React-19.2-61DAFB.svg)](https://react.dev/)
[![LangGraph](https://img.shields.io/badge/LangGraph-AI_Agents-purple.svg)](https://langchain-ai.github.io/langgraph/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.3-blue.svg)](https://www.typescriptlang.org/)
[![Vercel](https://img.shields.io/badge/Deploy-Vercel-black.svg)](https://vercel.com/)

---

## ✨ What It Does

AI Research Lab transforms unstructured research queries into comprehensive, structured briefs through a sophisticated multi-agent workflow:

1. **Literature Search** — Discovers relevant papers and web sources via SerpAPI integration
2. **Synthesis & Clustering** — GPT-4.1-mini synthesizes findings into coherent narratives
3. **Critical Analysis** — Identifies competing viewpoints, limitations, and areas of disagreement
4. **Confidence Assessment** — Evaluates evidence strength using multi-factor analysis

All orchestrated by LangGraph in a single, elegant interface with real-time progress tracking.

---

## 🎯 Core Features

### 🤖 **AI-Powered Research Pipeline**
- **Multi-Agent Orchestration** — LangGraph coordinates 4 specialized research agents
- **Advanced Prompt Engineering** — Carefully tuned prompts for high-quality outputs
- **Real-time Progress** — Live visualization of pipeline execution with node-by-node status
- **Evidence-Based Confidence** — Multi-factor confidence scoring with detailed reasoning

### 📊 **Structured Research Outputs**
- **Executive Summaries** — Comprehensive 3-5 paragraph syntheses that directly address research questions
- **Competing Viewpoints** — Identifies 2-4 distinct alternative interpretations with methodological critiques
- **Annotated Citations** — Expandable source cards with snippets, metadata, and quick access
- **Confidence Metrics** — Animated visual gauges with multi-factor breakdowns and actionable recommendations

### 🎨 **Modern User Experience**
- **Real-Time Pipeline Visualization** — Watch the research graph execute with node-by-node status updates
- **Tabbed Results Viewer** — Organized presentation of summaries, views, citations, and scores
- **Research History Sidebar** — Quick access to past briefs with search and filtering
- **Export & Share** — Download briefs as Markdown/PDF/HTML or generate shareable links
- **Template Library** — Pre-configured research templates for literature reviews, market analysis, and more

### 📱 **Production-Ready Interface**
- **Responsive Design** — Mobile-first approach with 44px+ touch targets and tabbed layouts
- **Accessible Themes** — Seamless dark/light mode with system preference detection
- **Immersive Experience** — Video hero backgrounds with optimized performance
- **Keyboard Shortcuts** — Power-user productivity with customizable keybindings
- **Mobile Navigation** — Bottom nav and full-screen drawers for optimal mobile UX

---

## 🏗️ Tech Stack

### **Frontend** ⚛️
| Technology | Purpose |
|------------|---------|
| **Next.js 16** | App Router with React Server Components |
| **TypeScript** | Type-safe development with strict mode |
| **React 19.2** | Latest React features and concurrent rendering |
| **Mantine UI** | Comprehensive component library with theming |
| **CSS Custom Properties** | Semantic design tokens for light/dark modes |

### **Backend** 🐍
| Technology | Purpose |
|------------|---------|
| **FastAPI** | High-performance async Python API |
| **LangGraph** | Multi-agent workflow orchestration |
| **OpenAI GPT-4.1-mini** | Advanced language model for research synthesis |
| **Pydantic v2** | Runtime type validation and data modeling |
| **Structured Prompts** | Fine-tuned prompts for optimal AI outputs |

### **Data & Infrastructure** 💾
| Technology | Purpose |
|------------|---------|
| **Supabase** | PostgreSQL database with RPC function layer |
| **Upstash Redis** | Distributed caching and rate limiting |
| **SerpAPI** | Web and academic literature search |

### **Deployment** 🚀
| Platform | Service |
|----------|---------|
| **Vercel** | Frontend hosting with edge optimization |
| **Railway** | Backend API deployment with auto-scaling |

---

## 📸 Feature Showcase

### Landing Page
Immersive hero section with video backgrounds, clear value proposition, and smooth theme transitions.

### Research Playground
Interactive workspace featuring:
- **Desktop**: 3-pane layout (Controls | Progress | Results)
- **Mobile**: Tabbed interface for optimal mobile experience
- Real-time pipeline visualization with node status indicators
- Export, share, and template selection capabilities

### Results Dashboard
Saved research briefs with:
- Search and filtering by topic/recency
- Side-by-side comparison view
- Collections organization
- Activity feed with recent research

### Research Templates
Pre-configured templates for:
- Literature reviews
- Market analysis
- Technical comparisons
- Scientific method comparisons
- Business research

---

## 📖 User Guide

### Getting Started

1. **Enter Your Research Question** — Pose any research query on the landing page
2. **Configure Parameters** — Set search depth (1-10) and recency window (days)
3. **Enable Web Search** — Toggle to include web sources beyond academic papers
4. **Run Pipeline** — Watch the LangGraph workflow execute in real-time
5. **Explore Results** — Review summaries, competing views, citations, and confidence scores

### Understanding Your Results

| Section | What It Provides |
|---------|------------------|
| **Summary** | Synthesized narrative addressing your research question (3-5 paragraphs) |
| **Competing Views** | Alternative interpretations, limitations, and areas of disagreement |
| **Citations** | Annotated source cards with titles, snippets, URLs, and source types |
| **Confidence Score** | Evidence strength (0-100%) with multi-factor reasoning |
| **Timeline** | Step-by-step execution history showing each node's contribution |

### Pro Tips

- **Be Specific** — More detailed questions yield better, more focused results
- **Adjust Depth** — Higher depth (7-10) for comprehensive research; lower (3-5) for quick overviews
- **Use Templates** — Pre-configured templates for common research types (literature reviews, market analysis, etc.)
- **Review Competing Views** — These highlight important limitations and alternative perspectives
- **Check Confidence Factors** — Understand what drives the confidence score (source quality, quantity, consensus, etc.)

---

## 🎨 Architecture Highlights

### Multi-Agent Orchestration

The application leverages LangGraph to coordinate specialized AI agents, each with distinct responsibilities:

- **Literature Search Agent** — Aggregates sources from web and academic databases
- **Synthesis Agent** — Transforms raw findings into coherent narratives
- **Critical Analysis Agent** — Identifies gaps, biases, and competing viewpoints
- **Confidence Agent** — Evaluates evidence quality using multiple factors

### Prompt Engineering

Carefully crafted prompts ensure high-quality outputs:
- **System Prompts** — Define agent roles and capabilities
- **Structured Outputs** — JSON formatting for consistent parsing
- **Context-Aware** — Prompts adapt based on source count and research depth
- **Error-Resilient** — Fallback parsing for varied response formats

### State Management

LangGraph maintains state throughout the pipeline:
- Source aggregation
- Intermediate summaries
- Competing viewpoints
- Execution timeline
- Metadata tracking

---

## 📊 Performance

| Metric | Value |
|--------|-------|
| Pipeline Execution | 15-30 seconds (typical) |
| Summary Generation | 5-10 seconds |
| Critical Analysis | 5-10 seconds |
| Confidence Estimation | 3-8 seconds |
| Frontend Bundle | Optimized with Next.js 16 |
| Mobile Performance | 60fps animations, 44px+ touch targets |

---

## 🛡️ Security & Privacy

- ✅ **API Key Protection** — All secrets stored as environment variables
- ✅ **Rate Limiting** — Redis-based rate limiting prevents API abuse
- ✅ **Input Sanitization** — All user inputs validated and sanitized
- ✅ **CORS Protection** — Strict CORS policies for API endpoints
- ✅ **Database Security** — RPC functions prevent direct schema access
- ✅ **Error Handling** — No sensitive data exposed in error messages

---

## 📸 Key Features Showcase

### 🏠 Landing Page
*Immersive hero section with video backgrounds and clear value proposition*

### 🎮 Research Playground
*Interactive 3-pane workspace (desktop) or tabbed interface (mobile) with real-time pipeline visualization*

### 📊 Results Dashboard
*Saved research briefs with filtering, search, and comparison capabilities*

### 📝 Research Templates
*Pre-configured templates for literature reviews, market analysis, technical comparisons, and more*

---

## 🌟 Technical Highlights

This project demonstrates production-ready implementation of:

- **Multi-Agent AI Systems** — LangGraph orchestration with persistent state management across nodes
- **Advanced Prompt Engineering** — Fine-tuned system and user prompts producing structured JSON outputs
- **Modern Full-Stack Architecture** — TypeScript strict mode, Python 3.11+ async/await, Next.js 16 App Router
- **Real-Time UI Updates** — Live pipeline progress tracking with smooth 60fps animations
- **Responsive Design** — Mobile-first CSS with semantic tokens, 44px+ touch targets, and tabbed mobile layouts
- **Cloud-Native Deployment** — Vercel edge optimization + Railway auto-scaling with environment-based config
- **Database Abstraction** — Supabase RPC function layer ensuring secure, maintainable data access patterns
- **Error Resilience** — Comprehensive error handling with graceful degradation and user-friendly messaging
- **Performance Optimization** — Redis caching, rate limiting, and efficient external API usage patterns
- **Accessibility** — WCAG-compliant components with keyboard navigation and screen reader support

---

## 🙏 Acknowledgments

- **[LangGraph](https://langchain-ai.github.io/langgraph/)** — Multi-agent orchestration framework
- **[OpenAI](https://openai.com/)** — GPT-4.1-mini language model
- **[SerpAPI](https://serpapi.com/)** — Web and academic search integration
- **[Supabase](https://supabase.com/)** — PostgreSQL database and RPC functions
- **[Upstash](https://upstash.com/)** — Serverless Redis caching
- **[Vercel](https://vercel.com/)** — Frontend hosting and edge functions
- **[Railway](https://railway.app/)** — Backend API deployment
- **[Mantine](https://mantine.dev/)** — React component library

---

## 📄 License

MIT License — see [LICENSE](LICENSE) for details.

---

<div align="center">

[Live Demo](https://langgraph-ai-research-lab.vercel.app)
Built with ❤️ and ☕

</div>
