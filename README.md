# Cristian Operating Profile Skill

This repository contains a reusable Claude Skill profile designed to help Claude work as a senior strategic, technical, product, GTM, and execution coworker for Cristian across any project, offer, client opportunity, proposal, technical architecture, or delivery plan.

The repository is intentionally project-agnostic. 

## Repository Structure

```text
cristian-operating-profile-skill/
├── README.md
├── CHANGELOG.md
├── LICENSE
├── .gitignore
├── skills/
│   └── Cristian_Operating_Profile_SKILL_v2.md
├── templates/
│   ├── Project_Context_SKILL_TEMPLATE.md
│   ├── Offer_One_Pager_TEMPLATE.md
│   ├── Client_Proposal_TEMPLATE.md
│   ├── PRD_TEMPLATE.md
│   ├── Competitive_Analysis_TEMPLATE.md
│   ├── GTM_Plan_TEMPLATE.md
│   ├── Technical_Architecture_TEMPLATE.md
│   └── Delivery_Plan_TEMPLATE.md
├── source_docs/
├── research/
├── drafts/
├── outputs/
├── final_deliverables/
└── .github/
    └── workflows/
        └── markdown-check.yml
```

## How to Use

### 1. Add the base skill to Claude

Upload or copy:

```text
skills/Cristian_Operating_Profile_SKILL_v2.md
```

Use it as the reusable base profile across projects.

### 2. Create a project-specific skill

Copy:

```text
templates/Project_Context_SKILL_TEMPLATE.md
```

Rename it, for example:

```text
Project_Context_SKILL.md
```

Then complete it with the current project, offer, client, constraints, decisions, and required outputs.

### 3. Keep project files organized

Use these folders:

- `source_docs/`: original files, client docs, notes, screenshots, transcripts, source material.
- `research/`: market research, competitor research, references.
- `drafts/`: working versions.
- `outputs/`: generated artifacts.
- `final_deliverables/`: client-ready or team-ready final files.

## Recommended Claude Setup

Use this repo as a reusable operating layer:

```text
Claude Project
├── Cristian_Operating_Profile_SKILL_v2.md
├── Project_Context_SKILL.md
├── Source_Docs/
├── Research/
├── Drafts/
├── Outputs/
└── Final_Deliverables/
```

## Version

Current version: `v2.0.0`

