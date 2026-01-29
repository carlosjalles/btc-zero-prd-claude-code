# Claude Code Agent Ecosystem

> Production-ready AI agents and knowledge bases for automated invoice processing pipelines.

## Overview

This repository contains a comprehensive **Claude Code agent ecosystem** designed for building intelligent, serverless data pipelines. The system features 40+ specialized AI agents, 8 curated knowledge base domains, and a structured development workflow (SDD) for rapid, reliable development.

**Target Project:** UberEats Invoice Processing Pipeline — an automated AI-powered extraction system achieving 90%+ accuracy on invoice data with autonomous monitoring.

## Quick Start

```bash
# Clone and navigate
git clone https://github.com/btc-zero/btc-zero-prd-claude-code.git
cd btc-zero-prd-claude-code

# Launch Claude Code
claude

# Explore the codebase
/explore
```

## Architecture

```text
.claude/
├── agents/              # 40+ specialized AI agents
│   ├── ai-ml/           # LLM, GenAI, prompt engineering
│   ├── aws/             # Lambda, CI/CD, deployment
│   ├── code-quality/    # Review, test, document, clean
│   ├── data-engineering/# Spark, Lakeflow, Medallion
│   ├── domain/          # Invoice pipeline specialists
│   ├── exploration/     # Codebase analysis
│   └── workflow/        # Brainstorm → Build → Ship
├── kb/                  # Knowledge base domains
│   ├── pydantic/        # Schema validation
│   ├── gcp/             # Serverless infrastructure
│   ├── gemini/          # Document extraction
│   ├── langfuse/        # LLMOps observability
│   ├── terraform/       # Infrastructure as Code
│   ├── terragrunt/      # Multi-environment config
│   ├── crewai/          # Autonomous agents
│   └── openrouter/      # LLM gateway fallback
└── sdd/                 # Structured Development Design
```

## Key Components

| Component             | Purpose                                              |
|-----------------------|------------------------------------------------------|
| **Agents**            | Task-specific AI specialists with validation systems |
| **Knowledge Base**    | MCP-validated patterns and concepts                  |
| **SDD Workflow**      | AgentSpec 4.1 for reproducible development           |
| **Invoice Generator** | Synthetic data for testing (`gen/`)                  |

## Agent Categories

| Category         | Count | Examples                                       |
|------------------|-------|------------------------------------------------|
| AI/ML            | 4     | `llm-specialist`, `genai-architect`            |
| AWS              | 4     | `lambda-builder`, `aws-deployer`               |
| Code Quality     | 6     | `code-reviewer`, `test-generator`              |
| Data Engineering | 8     | `spark-specialist`, `lakeflow-architect`       |
| Domain           | 5     | `extraction-specialist`, `pipeline-architect`  |
| Workflow         | 6     | `brainstorm-agent`, `ship-agent`               |

## Tech Stack

- **AI/LLM:** Gemini 2.0 Flash, OpenRouter, Claude Code
- **Cloud:** GCP (Cloud Run, Pub/Sub, GCS, BigQuery)
- **IaC:** Terraform + Terragrunt
- **Validation:** Pydantic
- **Observability:** LangFuse, Cloud Logging
- **Automation:** CrewAI (autonomous monitoring)

## Usage Examples

```bash
# Explore codebase structure
claude "Use codebase-explorer to analyze this repo"

# Create documentation
claude "Use code-documenter to create API docs"

# Build a new feature
claude "/brainstorm add validation layer"
```

## Project Status

| Milestone            | Target   | Status         |
|----------------------|----------|----------------|
| Agent ecosystem      | Jan 2026 | ✅ Complete    |
| Knowledge bases      | Jan 2026 | ✅ Complete    |
| SDD workflow         | Jan 2026 | ✅ Complete    |
| Invoice pipeline MVP | Apr 2026 | 🚧 In Progress |

## Documentation

- [Summary Requirements](notes/summary-requirements.md) — Consolidated project specs
- [Agent Template](.claude/agents/_template.md.example) — Create new agents
- [KB Index](.claude/kb/_index.yaml) — Knowledge base registry

## License

MIT
