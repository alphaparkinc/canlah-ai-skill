# canlah-ai-skill

> **GenPark AI Agent Skill** -- # CANLAH AI Agent Skill Project

This project contains the comprehensive product research and custom agent skill definition for **CANLAH AI**, configured for the **Google Antigravity IDE**.

## Project Structure

```text
├── .agent/
│   └── skills/
│       └── canlah-ai-helper/
│           └── SKILL.md                 # Antigravity IDE Skill Definition
├── canlah_research_report.md            # Detailed Product Research Report
└── README.md                            # This file
```

---

## How to Install and Use

### 1. Workspace Skill (Project Specific)
To enable this skill for a specific project:
1. Copy the `.agent` folder into your project's root directory.
2. The Antigravity IDE agent will automatically index the skill on startup using the metadata in `.agent/skills/canlah-ai-helper/SKILL.md`.

### 2. Global Skill (All Projects)
To enable this skill globally across all Antigravity IDE workspaces:
1. Copy the contents of `.agent/skills/canlah-ai-helper` to `~/.gemini/antigravity/skills/canlah-ai-helper/` (or equivalent global config folder on your OS).

---

## Triggering the Skill

You can trigger the skill by asking the Antigravity agent tasks related to:
*   *"Help me research CANLAH AI's Style Genome™ and its pricing plans."*
*   *"Write marketing copy for my brand using Athena and Calliope personas."*
*   *"Perform a GEO (Generative Engine Optimization) site audit on my store: https://example.com"*
*   *"Outline an e-commerce sales flow using Hephaestus and Hestia agents."*

---

## Research Overview

For a deep dive into **CANLAH AI**'s core product suite (**CanMarket**, **CanArt**, and **CanSell**), the **Style Genome™** 768-dimensional brand memory technology, and its **10 specialist agents** across three centers of gravity, see [canlah_research_report.md](canlah_research_report.md).