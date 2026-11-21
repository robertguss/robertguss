# 👋 Hey I'm Robert

# Projects

## ⚓ Keel Data Stack (Rust Data Engineering)
A 10-tool suite of single-binary, agent-first (DX + AX) Rust tools for modern SQL/PostgreSQL/SQLite data pipelines — start at the **[keel-stack hub & unified installer](https://github.com/robertguss/keel-stack)**:
- ⚓ [runkeel](https://github.com/robertguss/runkeel) - Zero-daemon, parallel Rust DAG pipeline runner orchestrating the Keel Data Stack and shell/SQL workflows with retries, `--from` resume, Mermaid diagrams, and JSON audit logs.
- 🌊 [fetchkeel](https://github.com/robertguss/fetchkeel) - Declarative Rust REST API extractor with RFC 5988 `Link`/cursor/page pagination, `429` rate-limit backoff, and atomic incremental watermarks.
- 🧭 [dapkeel](https://github.com/robertguss/dapkeel) - Blazing-fast Rust CLI for Instructure's Data Access Platform (Canvas Data 2) with OAuth 2.0 per-table JWTs, ODCS contract export, streaming JSONL unpack, and atomic PostgreSQL `COPY` replication.
- 🛡️ [datakeel](https://github.com/robertguss/datakeel) - Rust data contract, schema drift, cross-source FK, quarantine-splitting, and Postgres/Pydantic codegen CLI with native ODCS v3.2.0 YAML and TOML support.
- 🚢 [loadkeel](https://github.com/robertguss/loadkeel) - Rust JSONL/JSON/CSV/Parquet to PostgreSQL `COPY` + atomic `ON CONFLICT` upsert bulk loader with JSON flattening, PK dedupe, and safe column evolution.
- 🔍 [sqlkeel](https://github.com/robertguss/sqlkeel) - Contract-grounded Rust SQL semantic bug analyzer, Postgres migration lock checker, dbt/Jinja preprocessor, and transitive column-level lineage tool.
- 📊 [statkeel](https://github.com/robertguss/statkeel) - Blazing-fast Rust EDA data profiler (`ydata-profiling` replacement with offline SVG HTML reports), cross-source join health checker, live read-only SQL query trust auditor, and snapshot/query drift comparator.
- 🗺️ [mapkeel](https://github.com/robertguss/mapkeel) - Zero-Java, zero-Graphviz Rust SchemaSpy replacement: PostgreSQL/SQLite database cataloger, interactive inline SVG & Mermaid ER diagrams, schema anomaly & snapshot drift checker (`diff`), and automatic implicit cross-schema FK discovery.
- 🚚 [pgkeel](https://github.com/robertguss/pgkeel) - Zero-Lisp Rust `pgloader` replacement: migrate SQLite, MySQL/MariaDB, CSV, JSONL, and Parquet into PostgreSQL with DDL/type/index/FK translation, parallel streaming `COPY`, identity sequence resets, and row-count verification.
- 🪶 [litekeel](https://github.com/robertguss/litekeel) - Blazing-fast, single-binary Rust drop-in for `sqlite-utils`: ingest CSV/TSV/JSON/JSONL/Parquet into SQLite with `--alter`, `--flatten`, true upserts, FTS5 BM25 search + sync triggers, `extract`, atomic `transform`, `analyze`, and `optimize`.

## 🧬 Languages & Databases
- 🧬 [Mo](https://github.com/robertguss/mo) - A from-scratch programming language for the AI era
- 𝌏 [MoDB](https://github.com/robertguss/modb)
- 🦺 [Safe C](https://github.com/robertguss/safe-c) - Make C a practical, near-provably safe language for AI agents to write

## 🤖 AI, Agents & Skills
- 🎏 [Elara](https://github.com/robertguss/Elara) - Elara is a BEAM-native coding agent for a local working directory. It can inspect and edit files, run shell commands, keep persistent conversations, load local tools, and move tool execution to a separate worker. It emphasizes durable, causally explainable work rather than feature-for-feature parity with existing agents.
- 🧠 [Agent Skills](https://github.com/robertguss/agent-skills) - Portable agent skills in the open Agent Skills format. Each skill is a folder under skills/ that runs unchanged in Claude Code, Codex, Cursor, Gemini CLI, and Antigravity CLI.
- 🥞 [Pstack Portable](https://github.com/robertguss/pstack-portable) - Vendor Cursor's pstack plugin into any project for Amp, Claude Code and Codex, with per-role models in pstack.config.yaml.
- 🧰 [Claude Code Toolkit](https://github.com/robertguss/claude-code-toolkit) - A collection of custom skills that extend Claude's capabilities with specialized workflows, methods, and domain knowledge.
- 🤖 [BMAD Automated](https://github.com/robertguss/bmad_automated) - A CLI tool for automating BMAD-METHOD development workflows with Claude Code.
- 📝 [Claude Code Transcripts](https://github.com/robertguss/claude_transcripts) - A CLI tool for converting Claude Code session transcripts to markdown.
- 🥼 [Artifact Driven Research Program](https://github.com/robertguss/artifact-driven-research-program) - Evidence-grounded research → coherent architecture → adversarial review → implementation plan as phases and milestones. Git is the system of record.
- 🐅 [Programming Tiger Style](https://github.com/robertguss/programming_tiger_style) - Standards-first repository for high-rigor coding with humans and AI agents.

## 🛠️ Developer Tools & CLIs
- 👀 [Qgate](https://github.com/robertguss/qgate) - A local, deterministic quality gate for code written by AI agents. It runs as git hooks on every commit and push, so the mechanical checks that usually wait on remote CI finish on your machine in seconds, and AI review can spend its tokens on judgment instead.
- 🐆 [Go Plan](https://github.com/robertguss/go-plan) - A deterministic, offline CLI for creating, approving, executing, revising, and retiring one Git-native implementation plan. The executable is named `gp`.
- 🕵️ [Recon](https://github.com/robertguss/recon) - Code intelligence and knowledge CLI for Go repositories.
- 🍄 [Mycelium](https://github.com/robertguss/mycelium) - Single-binary Go CLI that scaffolds and operates idea repos.
- 🥤 [Go Foundry CLI](https://github.com/robertguss/go-foundry-cli) - Foundry generates minimal, production-grade Go CLI and TUI projects from a strict TOML specification and an embedded catalog — with descriptor-relative filesystem transactions, closed tool environments, and commit-dominant exit semantics.
- 🥾 [exe-bootstrap](https://github.com/robertguss/exe-bootstrap) - Modular idempotent dev environment bootstrap for disposable exe.dev VMs.

## 🚀 Starter Kits & Frameworks
- 🦀 [Rust Web Kit](https://github.com/robertguss/rust-web-kit) - AI-first full-stack starter: Rust (Axum) API + React (Vite) frontend, shipped as a single Docker image.
- ⏿ [Iris](https://github.com/robertguss/Iris) - An opinionated framework for building full stack Rust & React applications.
- 🦊 [Go Full Stack Start](https://github.com/robertguss/go-full-stack-start) - An opinionated CLI generator for production-minded personal apps and internal tools: Go, React, TypeScript, SQLite, typed OpenAPI contracts, passkeys/passwords, and realtime SSE in one deployable binary.
- 📟 [Go Full Stack Template](https://github.com/robertguss/go-full-stack-template) - A GitHub template for small, production-ready full-stack applications in Amp orbs and exe.dev. It produces one portable Go binary containing the React app, API, migrations, and SQLite driver—without a project-generation CLI.
- 🦚 [Go Islands Starter](https://github.com/robertguss/go-islands-starter) - Go + templ + React islands starter kit.
- 🐦‍🔥 [Phoenix/Inertia - Starter Kit](https://github.com/robertguss/phoenix-inertia-starter) - A pinned, always-green Phoenix 1.8 / Ash 3 template. One superset repo births an Inertia + React + TypeScript web project, or a JSON:API project via a single command — optimized so AI agents can start shipping features immediately from working, conventional code.
- 🏕️ [Treehouse](https://github.com/robertguss/treehouse) - Starter kit for family browser 3D games: React Three Fiber, iPad-first, multiplayer on Cloudflare, built by agents.
- 🚀 [Web App Starter Kit](https://github.com/robertguss/web-app-starter-kit) - An opinionated starter kit for shipping your ideas fast with AI.
- ⌨️ [Laravel App Starter Kit](https://github.com/robertguss/laravel-app-starter-kit)
- 🛤️ [Rails App Starter Kit](https://github.com/robertguss/rails-app-starter-kit)

## ✞ Theology
- ✞ [Bron](https://github.com/robertguss/bron) - An open commons giving English readers access to the primary sources of the Reformed and neo-Calvinist tradition in their original languages — Dutch, Latin, French, German — without requiring them to know those languages. Original and translation side by side, every claim traceable to a page, every translation carrying its provenance, every passage citable forever.
- ✟ [Reformed Bible Study](https://github.com/robertguss/reformed-bible-study) - A free, open-source Reformed Bible study app built from openly licensed resources.

## ✨ Apps & Productivity
- 🤑 [MoneyHQ - Local](https://github.com/robertguss/money_hq_local_first) - A local-first personal finance command center. Track spending, manage debt, forecast cash flow — all with your data staying on your machine.
- 💬 [Money Advisor](https://github.com/robertguss/money-advisor) - Personal financial advisor you run in chat. Agent + files + CLI. Sample data only.
- 👄 [Speak](https://github.com/robertguss/speak) - Open-source, bring-your-own-key dictation for Mac, iPhone, and iPad.
- 🤔 [ThinkBench](https://github.com/robertguss/think-bench-elixir) - A shared visual board beside a chat with AI.
- 👓 [SignalScout](https://github.com/robertguss/signal_scout) - A daily digest tool that surfaces high-value engagement opportunities across online communities, starting with Reddit.
