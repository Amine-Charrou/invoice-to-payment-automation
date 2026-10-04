# Invoice-to-Payment Automation: A Consulting Case

> Map the process, redesign it with AI, prove the ROI.

![status](https://img.shields.io/badge/status-planned-lightgrey) ![phase](https://img.shields.io/badge/sprint-Weeks%2011--12-blue)

**Category:** AI Automation × Consulting · **Domain:** Operations / Finance · **Stack:** n8n · LLM extraction · Python · Excel

Project 06/08 of my *Data & AI × Business Consulting* portfolio. 🚧 **Design stage, no implementation yet.**

## Overview

A full AI-transformation engagement on one workflow: invoice processing. It documents the current process, finds the bottlenecks, redesigns it with document extraction, business rules and human checkpoints, implements it, and closes with an ROI model and an executive presentation.

## Business problem

Invoice processing is full of manual data entry, validation, approvals and rework, which makes it slow, error-prone and costly.

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

## Status

- [x] Scope and README
- [ ] Data
- [ ] Implementation
- [ ] Evaluation & business impact
- [ ] Demo and write-up

---

*Author: Amine Charrou · Final-year Data Science & AI engineering student, ENSA Agadir*
