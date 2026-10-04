# Invoice-to-Payment AI Automation

> Map the process, redesign it with AI, prove the ROI.

![status](https://img.shields.io/badge/status-design%20stage-lightgrey) ![sprint](https://img.shields.io/badge/sprint-Weeks%2011--12-blue) ![project](https://img.shields.io/badge/portfolio-06%2F08-0891b2)

| | |
|---|---|
| **Category** | AI Automation × Consulting |
| **Domain** | Operations / Finance |
| **Stack** | n8n · LLM extraction · Python · Excel |
| **Status** | 🚧 Scoped — implementation not started |

## Overview

A full AI-transformation engagement on one workflow: invoice processing. It documents the current process, finds the bottlenecks, redesigns it with document extraction, business rules and human checkpoints, implements it, and closes with an ROI model and an executive presentation.

## Business problem

Invoice processing is full of manual data entry, validation, approvals and rework, which makes it slow, error-prone and costly.

## What this project demonstrates

- Running a consulting-style engagement end to end
- Process mapping and bottleneck analysis
- AI document extraction combined with business rules
- ROI modelling and executive communication

## Key points

- Current-state process map: actors, systems, manual steps, decision points
- Pain-point analysis: time, errors, rework, duplicate effort
- Each step classified as fully automated, AI-assisted, rule-based or human-controlled
- Working pipeline: extraction → validation → rules → risk check → approval → ERP update → notification
- ROI model: hours saved, error reduction, processing time, payback period
- Governance framework and a short executive deck

## Planned architecture

```text
Invoice received
   ↓
LLM document extraction
   ↓
Validation & business rules
   ↓
Risk check
   ↓
Human approval
   ↓
ERP update → notification → monitoring
```

## Planned deliverables

- [ ] Current-state and future-state process maps
- [ ] Step classification (automated / AI-assisted / rule-based / human)
- [ ] Working n8n + Python pipeline
- [ ] ROI model (Excel)
- [ ] Governance framework
- [ ] Executive presentation

## Success metrics

- Hours saved and processing time
- Error reduction and automation rate
- Annual savings = current cost − future cost; payback period

## Planned structure

```text
process/  n8n/  src/extraction/  roi/  docs/
```

## Roadmap

- [x] Scope and README
- [ ] Data collection / generation
- [ ] Core implementation
- [ ] Evaluation and business-impact estimate
- [ ] Demo, write-up and interview notes

---

Part of my **Data & AI × Business Consulting** portfolio, a 16-week sprint of 8 projects going from data and BI to ML, GenAI, agents, automation and AI strategy. See all projects on my [GitHub profile](https://github.com/Amine-Charrou).

*Amine Charrou · Final-year Data Science & AI engineering student, ENSA Agadir · [LinkedIn](https://www.linkedin.com/in/amine-charrou/)*
