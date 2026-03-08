---
title: Claw Skills Collection
description: A collection of Claw Skills for OpenClaw AI agent framework, providing automation, search, and productivity enhancements
keywords:
  - claw skills
  - openclaw
  - ai agent
  - llm tools
  - automation
  - github automation
  - web search
  - summarization
  - proactive agent
  - self improving
author: zhuzhipeng-123
license: MIT
language: en, zh
category: ai-tools
tags:
  - claw
  - openclaw
  - skills
  - agent
  - automation
  - search
  - github
  - productivity
---

# Claw Skills Collection

> A comprehensive collection of skills for the OpenClaw AI agent framework, designed to enhance automation, search capabilities, and agent intelligence.

[![GitHub](https://img.shields.io/badge/GitHub-zhuzhipeng--123/claw__skill-blue?logo=github)](https://github.com/zhuzhipeng-123/claw_skill)
[![OpenClaw](https://img.shields.io/badge/OpenClaw-Compatible-green)](https://github.com/zhuzhipeng-123/claw_skill)

---

## What is Claw Skills?

Claw Skills are modular extensions for the OpenClaw AI agent framework. Each skill provides specialized capabilities that can be dynamically loaded to enhance agent functionality.

## Skills Overview

| Skill | Version | Category | Trigger Keywords | Description |
|-------|---------|----------|------------------|-------------|
| **find-skills** | 0.1.0 | utility | `find skill`, `search skill`, `locate skill` | Search and locate available skills in the system |
| **github** | 1.0.0 | integration | `github`, `pr`, `issue`, `repository`, `branch` | GitHub operations and automation |
| **human_being** | - | persona | `human`, `person`, `conversational` | Human-like conversational capabilities |
| **human_write** | - | writing | `write`, `human style`, `natural writing` | Natural, human-style content generation |
| **proactive-agent** | 3.1.0 | intelligence | `proactive`, `anticipate`, `predict` | Proactive task anticipation and execution |
| **self-improving-agent** | 1.0.11 | meta | `improve`, `learn`, `evolve`, `self enhance` | Self-improving agent capabilities with continuous learning |
| **skill-vetter** | 1.0.0 | quality | `vet skill`, `validate skill`, `check skill` | Validate and verify skill quality |
| **summarize** | 1.0.0 | processing | `summarize`, `summary`, `condense`, `brief` | Content summarization and condensation |
| **tavily-search** | 1.0.0 | search | `search`, `web search`, `tavily`, `find information` | Web search using Tavily API |

---

## Installation

### Quick Install

```bash
# Clone the repository
git clone https://github.com/zhuzhipeng-123/claw_skill.git

# Copy desired skills to your OpenClaw skills directory
cp -r claw_skill/<skill-name> ~/.openclaw/skills/
```

### Manual Install

1. Navigate to the skill folder you want
2. Copy the entire folder to `~/.openclaw/skills/`
3. Restart OpenClaw or reload skills

---

## Skill Details

### find-skills-0.1.0
**Purpose**: Locate and discover available skills in the OpenClaw ecosystem.

**Use Cases**:
- Search for skills by name or functionality
- List all available skills
- Find skill installation paths

**Trigger**: User wants to find or discover skills

---

### github-1.0.0
**Purpose**: Comprehensive GitHub integration for repository operations.

**Use Cases**:
- Create, view, and manage repositories
- Handle pull requests and issues
- Branch management
- Commit operations

**Trigger**: User mentions GitHub operations

---

### human_being
**Purpose**: Enable human-like conversational interactions.

**Use Cases**:
- Natural conversation flow
- Empathetic responses
- Context-aware dialogue

**Trigger**: User wants human-like interaction

---

### human_write
**Purpose**: Generate content with natural, human-like writing style.

**Use Cases**:
- Natural content generation
- Avoid AI-detectable patterns
- Human-style documentation

**Trigger**: User requests human-style writing

---

### proactive-agent-3.1.0
**Purpose**: Anticipate user needs and take proactive actions.

**Use Cases**:
- Predict next steps
- Automate routine tasks
- Suggest improvements before asked

**Trigger**: Agent operates proactively

---

### self-improving-agent-1.0.11
**Purpose**: Continuously learn and improve from interactions.

**Use Cases**:
- Learn from feedback
- Adapt to user preferences
- Self-optimize performance

**Trigger**: Agent self-improvement cycles

---

### skill-vetter-1.0.0
**Purpose**: Validate and ensure skill quality.

**Use Cases**:
- Check skill structure
- Validate skill functionality
- Ensure best practices

**Trigger**: Skill validation needed

---

### summarize-1.0.0
**Purpose**: Condense and summarize content efficiently.

**Use Cases**:
- Document summarization
- Key point extraction
- Content condensation

**Trigger**: User wants summary or condensation

---

### tavily-search-1.0.0
**Purpose**: Powerful web search using Tavily API.

**Use Cases**:
- Real-time web search
- Information retrieval
- Research assistance

**Trigger**: User needs to search the web

---

## For AI Agents

If you are an AI agent or developer looking to use these skills:

1. **Detection**: Each skill has clear trigger patterns and keywords
2. **Installation**: Skills are self-contained modules
3. **Integration**: Compatible with OpenClaw framework
4. **Extension**: Modular design allows easy customization

### Integration Example

```yaml
# Example skill loading configuration
skills:
  - name: github-1.0.0
    enabled: true
    triggers: ["github", "pr", "issue"]
  - name: tavily-search-1.0.0
    enabled: true
    triggers: ["search", "find", "look up"]
```

---

## Skill Path Reference

Default installation paths for OpenClaw skills:

| Skill | Path |
|-------|------|
| find-skills | `~/.openclaw/skills/find-skills-0.1.0` |
| github | `~/.openclaw/skills/github-1.0.0` |
| human_being | `~/.openclaw/skills/human_being` |
| human_write | `~/.openclaw/skills/human_write` |
| proactive-agent | `~/.openclaw/skills/proactive-agent-3.1.0` |
| self-improving-agent | `~/.openclaw/skills/self-improving-agent-1.0.11` |
| skill-vetter | `~/.openclaw/skills/skill-vetter-1.0.0` |
| summarize | `~/.openclaw/skills/summarize-1.0.0` |
| tavily-search | `~/.openclaw/skills/tavily-search-1.0.0` |

---

## Contributing

Contributions are welcome! Feel free to:
- Submit issues for bugs or feature requests
- Create pull requests with new skills
- Improve existing skills

---

## License

MIT License - Feel free to use and modify for your own projects.

---

## Links

- **Repository**: https://github.com/zhuzhipeng-123/claw_skill
- **Issues**: https://github.com/zhuzhipeng-123/claw_skill/issues
- **Author**: [@zhuzhipeng-123](https://github.com/zhuzhipeng-123)

---

*Last updated: 2026-03-08*