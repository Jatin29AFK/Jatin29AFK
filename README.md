# Hi, I'm Jatin Shukla
### AI/ML Engineer | GenAI • RAG • AI Agents • ML Systems • Full-Stack AI Products

I build production-ready AI systems that turn machine learning research and GenAI ideas into usable products. My work focuses on **AI agents, RAG systems, predictive ML models, deep learning pipelines, retrieval systems, AI safety, and full-stack AI applications**.

Currently, I work as a **Senior Engineer – AI/ML at Havells India Ltd**, where I build AI/ML solutions for engineering workflows, HR automation, design evaluation, and internal business decision support.

---

## What I Work On

- **Generative AI Applications** using LLMs, prompt orchestration, RAG, and structured generation
- **AI Agents & Multi-Agent Systems** using LangGraph, FastAPI, Groq, tool calling, memory, and human review
- **RAG Pipelines** covering ingestion, chunking, retrieval, source-grounded answers, and evaluation
- **AI Safety & Reliability** through prompt-injection controls, deterministic policy checks, trace logging, and validation
- **Machine Learning Systems** using PyTorch, Scikit-learn, feature engineering, model evaluation, and deployment
- **3D / Point-Cloud ML Workflows** for engineering prediction and design evaluation
- **Full-Stack AI Products** using React, Next.js, Vite, Tailwind CSS, FastAPI, Supabase, and REST APIs

---

## Current Role

### Senior Engineer – AI/ML @ Havells India Ltd

At Havells, I work on production-grade AI/ML systems that support engineering teams, HR workflows, and internal business users.

Some of my work includes:

- Built AI agents for applicant shortlisting, resume screening, JD matching, and candidate ranking, reducing manual review effort by **40%+**
- Developed agentic ideation and research workflows for internal teams, improving early-stage solution turnaround by **30%**
- Built and deployed ML models for fan and LED components, improving engineering prediction accuracy by **18–22%**
- Reduced model inference latency by **35%** through optimized preprocessing, feature scaling, and deployment workflows
- Built UI-driven ML applications using **React, Flask, and VTK.js**, enabling **30+ engineers** to interact with AI outputs
- Designed 3D / point-cloud evaluation workflows handling **10+ design configurations per week**

---

## Featured Projects

### 1. AgentFlow – Multi-Agent AI Orchestration Platform

A full-stack platform that routes complex user tasks across specialist agents for research, coding, writing, and analysis.

**Key Highlights:**
- Orchestrates memory retrieval, supervisor planning, specialist execution, reviewer scoring, and human approval
- Provides workspace-isolated memory, run history, trace logging, and deterministic backend tools
- Captures agent decisions, tool usage, review scores, human actions, and final outputs

**Tech Stack:** FastAPI, LangGraph, Groq, React, SQLite, Tailwind CSS

> [Live Demo](https://agent-flow-five-phi.vercel.app/) • [GitHub Repository](https://github.com/Jatin29AFK/AgentFlow--Multi-Agent-AI-Platform)

---

### 2. Agentic AI Code Review Bot

A multi-agent GitHub pull-request reviewer that analyzes live PR diffs and generates structured, human-reviewable findings.

**Key Highlights:**
- Uses specialist agents for bug detection, security review, code quality, test coverage, aggregation, and autofix drafting
- Produces severity, confidence, category, affected file, risk impact, and suggested fixes for each finding
- Generates unified-diff autofix drafts without automatically modifying the repository
- Supports GitHub comment previews, review history, Docker-based setup, and CI workflows

**Tech Stack:** FastAPI, React, Vite, Tailwind CSS, SQLite, GitHub REST API, Docker, Configurable LLM Providers

> [Live Demo](https://agentic-ai-code-review-bot.vercel.app) • [GitHub Repository](https://github.com/Jatin29AFK/Agentic-AI-Code-Review-Bot)

---

### 3. Nexora – RAG-Based AI Study Assistant

A retrieval-first learning workspace that transforms PDFs and web content into grounded Q&A and interactive quizzes.

**Key Highlights:**
- Ingests PDFs and web pages, extracts content, creates retrievable chunks, and stores them in Supabase
- Generates source-grounded answers through Supabase Edge Functions and Groq
- Supports multiple answer modes, suggested questions, quiz generation, scoring, explanations, and weak-topic detection
- Includes anonymous authentication and persistent source and chunk storage

**Tech Stack:** React, Vite, Supabase Postgres, Supabase Edge Functions, Supabase Auth, Groq, RAG

> [Live Demo](https://nexora-one-ashen.vercel.app) • [GitHub Repository](https://github.com/Jatin29AFK/Nexora--AI_Study_Assistant)

---

### 4. Market Insight AI Agent

A full-stack agentic stock-research assistant that combines live market data, tool calling, streaming responses, and transparent execution traces.

**Key Highlights:**
- Uses a LangGraph agent to select tools for prices, company profiles, financials, dividends, history, and stock comparisons
- Grounds responses in yFinance data and displays tools used through badges and a trace timeline
- Includes historical charts, company snapshots, watchlists, multi-stock comparison, caching, and report export
- Uses educational guardrails and avoids buy, sell, or hold recommendations

**Tech Stack:** Next.js, TypeScript, FastAPI, LangGraph, LangChain, Groq, yFinance, Pandas, Recharts

> [Live Demo](https://market-insight-ai-agent.vercel.app) • [GitHub Repository](https://github.com/Jatin29AFK/Market-Insight-AI-Agent)

---

### 5. HireFit – AI Resume–JD Matcher

An AI-powered resume analysis and safer optimization platform for evaluating role fit, ATS readiness, skill gaps, and shortlist risk.

**Key Highlights:**
- Combines structured JD parsing, TF-IDF similarity, evidence-backed skill validation, and recruiter-style scoring
- Evaluates required skills, experience alignment, ATS quality, unsupported claims, and critical gaps
- Supports multi-JD comparison and generates safer resume improvements without fabricating experience
- Exports optimized content to TXT, DOC, and PDF formats

**Tech Stack:** FastAPI, React, Vite, Tailwind CSS, Scikit-learn, TF-IDF, Cosine Similarity, Gemini API

> [Live Demo](https://ai-resume-job-matcher-beta.vercel.app/) • [GitHub Repository](https://github.com/Jatin29AFK/HireFit---AI_Resume_Job_Matcher)

---

### 6. RefundPilot AI – Safe Refund Decision Agent

A containerized internal support workspace that evaluates e-commerce refund requests through trusted tools and deterministic policy checks.

**Key Highlights:**
- Produces approved, denied, or escalated decisions using order data and a deterministic refund-policy engine
- Detects prompt-injection attempts while preventing user instructions from overriding trusted policy rules
- Records tool calls, policy checks, reason codes, trace IDs, and customer-safe responses for admin review
- Runs without paid LLM access, with optional Groq-based response polishing after the decision is validated

**Tech Stack:** FastAPI, React, TypeScript, SQLite, Docker, Agentic AI, Groq

> [GitHub Repository](https://github.com/Jatin29AFK/refundpilot-ai-agent)

---

### 7. AI Recruiter – Resume Screening & Email Intake Tool

An enterprise-oriented resume intake and screening workflow that helps recruiters collect, validate, queue, and analyze candidate resumes.

**Key Highlights:**
- Accepts resumes through drag-and-drop uploads, Outlook workflows, Power Automate, or optional IMAP polling
- Supports batch intake, pending analysis queues, status tracking, resume validation, and duplicate detection
- Uses authenticated ingestion, SHA-256 deduplication, preserved email metadata, and audit-friendly processing
- Scores queued resumes against job descriptions using NLP and AI-assisted analysis

**Tech Stack:** FastAPI, React, Vite, Tailwind CSS, Scikit-learn, spaCy, RapidFuzz, Gemini API, Power Automate

> [GitHub Repository](https://github.com/Jatin29AFK/AI-Recruiter-Resume-Screening-Tool)

---

### 8. AI Article Rectification Pipeline

A robust batch-processing system that compares AI-generated articles with authoritative sources and applies minimal factual corrections.

**Key Highlights:**
- Processes **104 articles** through a command-line rectification workflow
- Uses surgical JSON-based find-and-replace patches instead of rewriting complete articles
- Preserves correct wording, structure, formatting, tone, and article order wherever possible
- Includes retries, exponential backoff, caching, patch validation, safe fallbacks, output integrity checks, and failure-resilient batch execution

**Tech Stack:** Python, OpenAI-Compatible LLM APIs, Structured Output, Validation Pipelines, CLI Automation

> [GitHub Repository](https://github.com/Jatin29AFK/ZeroAI_Assessment)

---

## Tech Stack

### Programming Languages
![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-025E8C?style=for-the-badge&logo=postgresql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7E017?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![C#](https://img.shields.io/badge/C%23-68217A?style=for-the-badge&logo=csharp&logoColor=white)

### AI / ML / GenAI
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Scikit Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=for-the-badge)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-102230?style=for-the-badge)
![Deep Learning](https://img.shields.io/badge/Deep%20Learning-1E1E1E?style=for-the-badge)
![RAG](https://img.shields.io/badge/RAG-2563EB?style=for-the-badge)
![AI Agents](https://img.shields.io/badge/AI%20Agents-7C3AED?style=for-the-badge)

### Retrieval, NLP & Data
![NLP](https://img.shields.io/badge/NLP-9333EA?style=for-the-badge)
![Semantic Search](https://img.shields.io/badge/Semantic%20Search-0F766E?style=for-the-badge)
![TF-IDF](https://img.shields.io/badge/TF--IDF-334155?style=for-the-badge)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)

### Backend / Deployment
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-111111?style=for-the-badge&logo=flask&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=black)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

### Frontend
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-38BDF8?style=for-the-badge&logo=tailwindcss&logoColor=white)

### Tools & Platforms
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Power Automate](https://img.shields.io/badge/Power%20Automate-0066FF?style=for-the-badge&logo=powerautomate&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

---

## Areas I’m Currently Exploring

- Production-ready AI agents and tool-use systems
- Multi-agent orchestration and agent evaluation
- RAG quality, grounding, and retrieval evaluation
- LLM application reliability, observability, and structured traces
- Prompt-injection defenses and policy-controlled AI workflows
- Full-stack GenAI product development
- MLOps and scalable model deployment
- Human-in-the-loop AI systems

---

## Research Publication

### Post-Harvest Loss Mitigation and Smart Storage Management Using IoT and Azure Digital Twin

Published research on an IoT-enabled digital twin system for reducing post-harvest losses using Raspberry Pi, environmental sensors, Azure IoT services, and ML-based predictive insights.

> [View Publication](https://link.springer.com/chapter/10.1007/978-981-96-9979-7_6)

---

## Connect With Me

I’m open to opportunities in:

- AI Engineer
- GenAI Engineer
- Machine Learning Engineer
- Applied AI Engineer
- AI Software Engineer
- LLM Engineer

I’m especially interested in roles involving **LLMs, RAG systems, AI agents, AI safety, ML deployment, predictive modeling, and full-stack AI product development**.

📧 Email: shukla.jeetu2550@gmail.com  
🌐 Portfolio: https://port-folio-alpha-black.vercel.app  
💼 LinkedIn: https://www.linkedin.com/in/jatin-shukla-401739202  
🐙 GitHub: https://github.com/Jatin29AFK

---

### “Building AI systems that move from prototype to production.”
