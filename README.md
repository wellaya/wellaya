# Hi, I'm Priyantha 👋

Building intelligent software with Azure, AI, and modern full-stack technologies. I focus on cloud-native architectures, distributed systems, and AI-powered applications that are scalable, reliable, and built to solve real-world business problems.

## What I work on
- **Cloud architecture**: Azure (App Services, Functions, API Management, Service Bus, AD, Managed Identity), Infrastructure as Code (Bicep)
- **AI/ML systems**: Azure OpenAI integration, RAG (Retrieval-Augmented Generation), document Q&A, local & cloud LLM inference
- **System design**: microservices, event-driven architecture, Clean Architecture, Domain-Driven Design
- **Backend**: .NET / C#, Python, Node.js
- **Frontend**: Angular, React
- **Practices**: CQRS, Onion/Clean Architecture, CI/CD, RBAC & security-first design

## Featured work
- 🎧 **[Multi-Agent Support Assistant](https://github.com/wellaya/multi-agent-support-assistant)** — Agentic support-triage system: a LangGraph state graph (triage → retrieve → draft → decide) sits behind FastAPI, grounding replies in a Qdrant + sentence-transformers RAG pipeline and drafting through a provider-agnostic Claude layer. Includes regex-based input/output guardrails, a SQLite audit log and human-in-the-loop approval queue, and a live-API eval suite kept separate from the free offline test suite/CI.

- 🔄 **[SimpleMapper](https://github.com/wellaya/SimpleMapper)** — Lightweight, dependency-free object-to-object mapper for .NET, built as an open-source library focused on simple, clean, and efficient model mapping.

- 🤖 **[DocuAgent](https://github.com/wellaya/docuagent)** — Agentic RAG assistant on Azure AI Foundry combining Document Intelligence, Azure AI Search (hybrid vector index), and a tool-calling agent (search + computer vision) with Content Safety gating and Application Insights tracing. Infrastructure fully defined in Bicep. *In progress.*
- 🎙️ **[AI Meeting Coach](https://github.com/wellaya/ai-meeting-coach)** — Open-source, local-first desktop app giving real-time AI coaching during meetings, using Whisper for transcription, Ollama for local LLM reasoning, and a RAG pipeline grounded in your own project docs.
- 🚗 **[Enterprise Rental Management Platform](https://github.com/wellaya/Rental-Management-Platform-.NET-Onion-Architecture)** — .NET/Angular rental platform built on Onion Architecture, designed for extensibility beyond its initial vehicle-rental scope (cottages, hotels, boats, equipment) via interface-based abstraction, DI, and SOLID principles — with full unit and integration test coverage.
- 💬 **[ChatCordinator](https://github.com/wellaya/ChatCordinator)** — Proof-of-concept exploring event-driven service coordination: a SignalR-based chat service and a separate coordinator service communicate asynchronously via RabbitMQ/MassTransit, with CQRS (MediatR) used internally in both. Built to explore decoupling real-time client delivery from backend coordination logic.
- 🏢 **[Multi-tenant SaaS Platform](https://github.com/wellaya/saas-platform)** — Full-stack SaaS starter built as a Turborepo monorepo with Next.js and Express, featuring row-level multi-tenant isolation, JWT-based auth verification independent of the frontend session layer, and idempotent Stripe subscription billing backed by Redis. Dockerized for local development with a full CI/CD pipeline via GitHub Actions.
- 🧱 **[Clean Architecture for Azure Functions](https://github.com/wellaya/CleanArchitecture.Functions.Template)** — A Clean Architecture template for Azure Functions (.NET 10, isolated worker), backed by shared NuGet packages ([Platform.Shared](https://github.com/wellaya/Platform.Shared)) for MediatR pipeline behaviours, EF Core auditing, and validation. Supports a shared-database-today, dedicated-database-later model via schema-per-vertical and a connection string resolver — no code changes required to split a vertical onto its own database. Reference implementation: [SampleApi](https://github.com/wellaya/SampleApi).
- 🚨 **[AI Incident Management System](https://github.com/wellaya/ai-incident-mgmt)** — Enterprise AI incident platform on Azure AI Foundry: an async Service Bus/Functions pipeline classifies severity, assigns teams, suggests fixes, summarizes logs, drafts RCAs, and generates customer comms (human-approved via Logic Apps), with a .NET/React app and Azure DevOps work-item sync. Infrastructure fully defined in Bicep. *In progress.*
- 🏢 **[AI-Powered HR Assistant](https://github.com/wellaya/azure-ai-hr-assistant)** — Enterprise-grade, cloud-native HR platform on Azure combining microservices, event-driven design, and DDD with an AI layer (Azure OpenAI HR chatbot, resume screening, document Q&A). Built with Bicep for IaC, secured via Azure AD/RBAC/Managed Identity. *In progress.*

