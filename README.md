# last-human-input
A human accountability system that records the final human decision before automation begins, preserving intent, assumptions and responsibility.

# LAST HUMAN INPUT
**Remembering the final human decision before automation begins.**

---

## Overview
LAST HUMAN INPUT is a human-accountability system designed to record, preserve, and display the final human decision made before a process becomes automated or AI-driven.

As automation expands, responsibility often fades. Systems make decisions, but humans originally chose to deploy those systems. This project ensures that the intent, assumptions and acknowledged risks behind those decisions are never lost.

---

## Problem
Automated systems influence hiring, healthcare, finance, governance and education.  
When failures occur, responsibility becomes unclear.

Most systems record outcomes.  
Few record the human decision that started everything.

---

## Solution
LAST HUMAN INPUT creates a permanent record of:

- who made the decision
- what they intended
- what they assumed
- what risks they acknowledged

It preserves the **origin of automation**.

---

## Key Features
- Decision logging interface
- AI-generated intent summary
- Assumption and risk extraction
- Timeline visualization
- Decision archive
- Anonymous or named submissions
- Permanent record concept

---

## How It Works
1. A human logs a decision before automation is deployed.
2. The system stores the raw decision text.
3. Gemini AI analyzes the decision and generates a neutral summary.
4. The system displays:
   - Original human input
   - AI interpretation
   - Timeline of responsibility

---

## Tech Stack
- HTML
- CSS
- JavaScript
- PHP
- MySQL
- Gemini AI API

---

## Architecture
Client → PHP Backend → MySQL Database → Gemini AI → Stored Summary → Displayed Record

---

## Example Use Cases
- Approving automated hiring screening
- Deploying AI medical triage
- Automating loan approvals
- Implementing surveillance AI
- Using AI grading systems

---

## Why It Matters
Automation is advancing faster than accountability frameworks.

LAST HUMAN INPUT ensures that when systems act, we can still trace:
> who decided, why they decided and what they believed would happen.

---

## Future Vision
This system could evolve into:
- AI governance infrastructure
- Ethical audit trails
- Policy compliance systems
- Public accountability archives

---

## Installation (Local Setup)
1. Clone repository
2. Import database.sql into MySQL
3. Configure database credentials in PHP config file
4. Add Gemini API key
5. Run on local server (XAMPP / WAMP / LAMP)

---

## Database Schema
Table: `decisions`

Fields:
- id
- title
- domain
- automation_description
- goal
- assumptions
- risks
- human_name
- is_anonymous
- ai_summary
- created_at

---

## Hackathon Context
Built for **ORIGIN Hackathon** — a challenge focused on meaningful technology, human impact and thoughtful innovation.

---

## Philosophy
This project is not about automation.  
It is about remembering who chose automation.

---

## License
MIT License
