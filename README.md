# Hi, I'm Atif

**Senior Engineer | AI Systems & Agents | Multi-Tenant SaaS | Backend Architecture**

I have been shipping production backends for two decades, across Laravel, FastAPI, Next.js, and a handful of stranger stacks (Phoenix LiveView, Rails 8, Elixir, Lua). These days most of my new work sits at the intersection of solid backend architecture and LLM-driven systems: agentic pipelines, MCP servers, RAG over pgvector, multi-tenant SaaS with proper isolation, and the boring plumbing (queues, audit trails, webhook signing, RBAC) that keeps any of it usable in production.

This profile collects the projects I build for myself in the open. Each one stands on its own. A few may move from portfolio into commercial product.

## What I Build

* **AI agents and MCP infrastructure.** LangGraph multi-agent pipelines, custom MCP servers shipped to npm, embeddable RAG chatbots grounded in private content, and the audit + observability layer underneath.
* **Multi-tenant SaaS.** Row-level security, HMAC webhook signing, tenant-scoped audit trails, RBAC, billing flows. The skeleton I keep reusing across Storebridge, Slate, Plexus, and LearnLoop.
* **Legal and governance tech.** CaseFlow runs on Laravel 12 + Filament 3 + Stripe. Quorum is the AI-native sibling: entity graph, AI-drafted resolutions, RAG over corporate documents, realtime collaborative editing.
* **Search and aggregation systems.** Skylane is multi-provider flight search with WebSocket streaming on Laravel + Reverb.
* **Cross-border fintech.** ZarPay covers the UK to Pakistan remittance corridor with a native Android sender app and a Next.js operations panel.
* **Operational platforms.** Rampart is an enforcement-first field service OS: deterministic FastAPI engine for FSM + audit + events, with Gemini-augmented incident command layered on top.

## AI & Agent Systems

* LangGraph orchestrators with hybrid pgvector + tsvector retrieval, Langfuse tracing, and LLM-as-judge evaluation (Meridian).
* Production MCP servers as a TypeScript monorepo, distributed via npm (MCP Toolkit, three servers: GitHub, Linear, Gmail).
* WhatsApp Business AI agent on the Meta Cloud API with structured tool loops and full Postgres audit (Cue).
* Manifest V3 browser extension that summarizes pages and drafts replies through Groq or Claude (Glean).
* Real-time collaborative document editor on Phoenix LiveView with Claude as a co-author and multi-user presence (Scribe).

## Tech Stack

**Backend.** Laravel (PHP 8.3), FastAPI (Python 3.12), Next.js (TypeScript), Phoenix LiveView (Elixir), Rails 8 (Ruby), Go where latency matters.

**AI tooling.** Claude API (Anthropic SDK), OpenAI, LangGraph, Anthropic MCP, Langfuse, pgvector, structured output via Pydantic.

**Data.** Postgres with RLS, pgvector, MySQL, Redis, MinIO, Drizzle, Prisma, Filament for admin.

**Real-time.** Reverb, WebRTC, Phoenix Channels, Server-Sent Events, WebSockets.

**Infra.** Docker Compose for local stacks, Cloudflare Pages and Workers, AWS, Railway, Fly.io.

**Automation.** n8n, custom subagent fleets, webhook routers, scheduled job orchestration.

## Selected Public Work

* [meridian](https://github.com/atifali-pm/meridian): LangGraph multi-agent research and execution pipeline. Hybrid pgvector + tsvector RAG, Langfuse tracing, LLM-as-judge evaluation.
* [mcp-toolkit](https://github.com/atifali-pm/mcp-toolkit): Three production MCP servers (GitHub, Linear, Gmail) for Claude Desktop and Cursor. TypeScript monorepo, zero hosting, distributed via npm.
* [rampart](https://github.com/atifali-pm/rampart): FastAPI enforcement engine for field service operations with deterministic FSM and Gemini-augmented incident command.
* [cue](https://github.com/atifali-pm/cue): WhatsApp Business AI agent on the Meta Cloud API with RAG and Postgres audit.
* [storebridge](https://github.com/atifali-pm/storebridge): Multi-tenant Shopify SaaS. Next.js + Drizzle + Postgres with RLS, HMAC webhooks, tenant isolation, audit logs.
* [quorum](https://github.com/atifali-pm/quorum): AI-native corporate governance with entity graph, AI-drafted resolutions, RAG vault, agentic filing prep, realtime collab.
* [skylane](https://github.com/atifali-pm/skylane): Multi-provider flight search aggregator with WebSocket streaming on Laravel 12 + Vue + Reverb.
* [zarpay](https://github.com/atifali-pm/zarpay): UK to Pakistan remittance with native Android sender app and Next.js operations panel.
* [caseflow](https://github.com/atifali-pm/caseflow): Legal case management on Laravel 12 + Filament 3 + Stripe (Laravel Cashier).
* [atrium](https://github.com/atifali-pm/atrium): Privacy-first AI assistant workspace UI: streaming chat, memory inspection, tool traces, personas, voice. React 18 + Vite.
* [n8n-agent-studio](https://github.com/atifali-pm/n8n-agent-studio): Three production-grade n8n workflows backed by a shared Postgres audit table.
* [portfolio-bot](https://github.com/atifali-pm/portfolio-bot): Embeddable RAG chatbot grounded on my portfolio site. Cloudflare Workers AI + Vectorize.
* [ai-api-starter](https://github.com/atifali-pm/ai-api-starter): Public FastAPI template for AI integrations. Structured output, RAG over pgvector, multi-LLM routing with fallback, Langfuse observability.
* [tracklane](https://github.com/atifali-pm/tracklane): AI-first project management on Rails 8. Self-hostable, MIT-licensed.
* [odooforge](https://github.com/atifali-pm/odooforge): Open-source deployment kit for multi-cloud Odoo with a Claude-powered customer support module.

The full repo list lives over on the [Repositories tab](https://github.com/atifali-pm?tab=repositories).

## Currently Building

Production-grade agentic pipelines (Meridian), enforcement-first ops platforms (Rampart), MCP infrastructure (toolkit and protocol experiments), and the next pass on the multi-tenant primitives I keep reusing across SaaS projects. Yeah, a lot of it overlaps. That is the point.

## Connect

* Portfolio: [atifali.pages.dev](https://atifali.pages.dev)
* LinkedIn: [linkedin.com/in/-atifali-](https://www.linkedin.com/in/-atifali-/)
* Email: aatifali21@gmail.com
* Based in Islamabad, Pakistan
