# turbo-claude

> A live-synced index of community CLAUDE.md rules, MCP servers, Claude Code skills, and agents — sourced from [clauderules.net](https://clauderules.net). Updated automatically via GitHub Actions. Add yours by submitting at [clauderules.net/submit](https://clauderules.net/submit).

[![Listed on clauderules.net](https://clauderules.net/api/badge)](https://clauderules.net)
![Rules](https://img.shields.io/badge/rules-15-orange)
![MCP Servers](https://img.shields.io/badge/mcp%20servers-9-blue)
![Skills](https://img.shields.io/badge/skills-10-green)
![Last synced](https://img.shields.io/badge/last%20synced-2026--04--19-lightgrey)

---

## Claude Rules (15)

CLAUDE.md rules tell Claude Code how to behave in your project — coding conventions, commands to run, patterns to avoid. Browse the full directory at [clauderules.net/rules](https://clauderules.net/rules).

| Rule | Description |
|---|---|
| [Next.js Expert](https://clauderules.net/rules/nextjs-expert) | Expert-level Next.js development with App Router, Server Components, and modern patterns. |
| [Python FastAPI Expert](https://clauderules.net/rules/python-fastapi) | Building high-performance REST APIs with FastAPI, Pydantic, and async Python. |
| [React TypeScript Best Practices](https://clauderules.net/rules/react-typescript) | Modern React development with TypeScript, hooks, and component patterns. |
| [Node.js Express API](https://clauderules.net/rules/nodejs-express) | Building scalable Node.js REST APIs with Express, middleware, and proper async patterns. |
| [Go Backend Development](https://clauderules.net/rules/golang-backend) | Building robust, idiomatic Go services with clean architecture and proper error handling. |
| [TypeScript Clean Code](https://clauderules.net/rules/typescript-clean) | Writing clean, idiomatic TypeScript with proper types, patterns, and architecture. |
| [Rust Systems Programming](https://clauderules.net/rules/rust-systems) | Safe, fast Rust code leveraging the ownership system, traits, and zero-cost abstractions. |
| [Ruby on Rails Expert](https://clauderules.net/rules/ruby-rails) | Convention-over-configuration Rails development with clean models, service objects, and tests. |
| [Vue.js Composition API](https://clauderules.net/rules/vuejs-composition) | Modern Vue 3 development with Composition API, Pinia, and TypeScript. |
| [Django Web Framework](https://clauderules.net/rules/django-python) | Full-stack Django development with DRF, proper models, and security best practices. |
| [Angular Enterprise](https://clauderules.net/rules/angular-enterprise) | Enterprise Angular development with RxJS, NgRx, standalone components, and best practices. |
| [SvelteKit Frontend](https://clauderules.net/rules/svelte-frontend) | Modern SvelteKit development with server-side rendering, stores, and TypeScript. |
| [Tailwind CSS Expert](https://clauderules.net/rules/tailwind-css) | Expert Tailwind CSS styling with component patterns, dark mode, and design systems. |
| [Swift iOS Development](https://clauderules.net/rules/swift-ios) | Modern iOS development with SwiftUI, Combine, and Swift concurrency. |
| [Flutter Mobile Development](https://clauderules.net/rules/flutter-mobile) | Cross-platform mobile apps with Flutter, Riverpod state management, and clean architecture. |

---

## MCP Servers (9)

Model Context Protocol servers extend what Claude can access — databases, GitHub, web search, filesystems, and more. Browse the full directory at [clauderules.net/mcp](https://clauderules.net/mcp).

| Server | Description |
|---|---|
| [Everything (Reference)](https://clauderules.net/mcp/everything) | Official MCP reference server that exercises all protocol capabilities: resources, prompts, tools, and sampling. Useful for testing MCP client implementations. |
| [Memory](https://clauderules.net/mcp/memory) | Persistent memory storage for Claude. Save and retrieve information across conversations using a knowledge graph. |
| [Slack](https://clauderules.net/mcp/slack) | Read messages, post to channels, and interact with Slack workspaces from Claude. |
| [SQLite](https://clauderules.net/mcp/sqlite) | Interact with SQLite databases. Create tables, run queries, and manage local database files. |
| [Puppeteer](https://clauderules.net/mcp/puppeteer) | Browser automation and web scraping with Puppeteer. Navigate pages, click elements, and extract data. |
| [Brave Search](https://clauderules.net/mcp/brave-search) | Web and local search using the Brave Search API. Get real-time web results and news. |
| [PostgreSQL](https://clauderules.net/mcp/postgres) | Execute SQL queries, explore schema, and interact with PostgreSQL databases safely. |
| [GitHub](https://clauderules.net/mcp/github) | Interact with GitHub repositories, issues, pull requests, and workflows directly from Claude. |
| [Filesystem](https://clauderules.net/mcp/filesystem) | Secure file system operations with configurable access controls. Read, write, create, and delete files within allowed directories. |
| [Agent Shadow Brain](https://github.com/theihtisham/agent-shadow-brain) | Self-evolving AI coding intelligence with infinite memory (TurboQuant), genetic algorithm self-evolution, predictive bug detection, PageRank knowledge graphs, swarm intelligence, and adversarial defense. |
| [Omni Skills Forge](https://github.com/theihtisham/omni-skills-forge) | 50,000+ curated AI agent skills for Claude Code, Cursor, Copilot, Windsurf, Cline. Visual dashboard, one-click install, skill doctor, auto-update.

---

## Claude Code Skills (10)

Slash commands for Claude Code that automate common workflows. Install with `claude mcp add` or drop into `.claude/commands/`. Browse at [clauderules.net/skills](https://clauderules.net/skills).

| Skill | Command | Description |
|---|---|---|
| [Code Review](https://clauderules.net/skills/code-review) | `/review` | Performs a thorough code review of the current changes or specified files. |
| [Generate Tests](https://clauderules.net/skills/generate-tests) | `/test` | Generates comprehensive unit tests for the specified function or file. |
| [Fix Bug](https://clauderules.net/skills/fix-bug) | `/fix` | Analyzes a bug or error and provides a targeted fix with explanation. |
| [Generate Commit Message](https://clauderules.net/skills/commit-message) | `/commit` | Generates a conventional commit message based on your staged changes. |
| [Standup Summary](https://clauderules.net/skills/standup-summary) | `/standup` | Generates a daily standup summary from recent git commits. |
| [PR Description](https://clauderules.net/skills/pr-description) | `/pr` | Writes a clear pull request description from your commits and changes. |
| [Refactor Code](https://clauderules.net/skills/refactor) | `/refactor` | Refactors code for better readability, performance, or maintainability. |
| [Write Documentation](https://clauderules.net/skills/write-docs) | `/docs` | Generates clear documentation for functions, components, or modules. |
| [Explain Code](https://clauderules.net/skills/explain-code) | `/explain` | Provides a clear explanation of what a piece of code does and why. |
| [Security Audit](https://clauderules.net/skills/security-audit) | `/security` | Audits code for security vulnerabilities based on OWASP Top 10. |

---

## Claude Agents (10)

Reusable agent configurations and sub-agent patterns for Claude Code. Browse at [clauderules.net/agents](https://clauderules.net/agents).

| Agent | Description |
|---|---|
| [Anthropic Cookbook — Agent Recipes](https://clauderules.net/agents/anthropic-cookbook) | Official collection of agent patterns and recipes from Anthropic. Includes tool use, multi-agent orchestration, memory management, and real-world agent implementations. |
| [Financial Data Analyst Agent](https://clauderules.net/agents/financial-data-analyst) | A multi-tool agent that analyzes financial data, queries databases, generates charts, and produces structured investment research reports using Claude. |
| [Customer Support Agent Starter](https://clauderules.net/agents/customer-support-agent) | Anthropic's quickstart for building a production-ready customer support agent with Claude. Includes conversation management, tool use for order lookups, and escalation logic. |
| [Model Context Protocol SDK](https://clauderules.net/agents/model-context-protocol) | Official MCP SDK for building Claude tool integrations. Enables agents to connect Claude to any external system — databases, APIs, filesystems, and custom tools. |
| [Multi-Agent Orchestration Patterns](https://clauderules.net/agents/multi-agent-orchestration) | Anthropic's reference patterns for orchestrating multiple Claude agents. Covers parallel agents, sequential pipelines, hierarchical agents, and error recovery strategies. |
| [Claude Code GitHub Action](https://clauderules.net/agents/claude-code-action) | Official Anthropic GitHub Action that runs Claude Code as a CI agent. Automatically reviews PRs, fixes bugs, and implements features directly in your GitHub workflow. |
| [Computer Use Demo Agent](https://clauderules.net/agents/computer-use-demo) | Anthropic's reference implementation of a computer-use agent. Claude controls a virtual desktop — browsing the web, running commands, and interacting with GUI applications. |
| [Claude Agent SDK — Python](https://clauderules.net/agents/claude-agent-sdk-python) | The official Python SDK for building Claude-powered agents. Provides a clean API for multi-turn conversations, tool definitions, streaming, and structured outputs. |
| [Claude Agent SDK — TypeScript](https://clauderules.net/agents/claude-agent-sdk-typescript) | The official TypeScript/Node.js SDK for Claude. Build agents with type-safe tool definitions, streaming responses, and comprehensive error handling. |
| [AWS Bedrock Claude Agents](https://clauderules.net/agents/bedrock-claude-agents) | Deploy Claude agents on AWS using Amazon Bedrock. Includes examples for knowledge base integration, action groups, and enterprise-scale agent deployments. |

---

*Auto-synced from [clauderules.net](https://clauderules.net) · [Submit a rule](https://clauderules.net/submit/rule) · [Submit an MCP server](https://clauderules.net/submit/mcp) · [Submit a skill](https://clauderules.net/submit/skill)*
