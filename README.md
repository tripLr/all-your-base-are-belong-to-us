# Train Your Dragon AI
### All Your Base Are Belong To Us

> A portable personal AI operating layer.

This repository is the **public plan** for turning the Train Your Dragon approach into something anyone can use across different AI models.

The goal is simple:

**You own the intelligence layer.**  
The model is just the engine.

---

## Core Idea

Instead of starting from zero with every new AI (ChatGPT, Claude, Grok, etc.), you maintain a living set of:

- Clear rulesets
- Skills
- Principles
- Versioned preferences

These live on GitHub under your control.  
A thin interface then injects the right rules into whatever model you choose to talk to.

---

## Planned Options

### 1. Grok Files (Quick Start)
Create ready-to-upload files specifically formatted for Grok.  
Fastest way to get the system running with minimal friction.

### 2. Web UI — Select Your AI
A simple personal webpage where you:
- Type your question
- Choose which model to use (Grok / Claude / ChatGPT / others)
- The page automatically sends your current ruleset + relevant skills with the question

### 3. Ruleset Toggles (Development & Testing)
Checkboxes that let you turn individual rulesets and skills on or off.  
Useful for:
- Testing what each rule actually does
- Development of new skills
- Running controlled experiments

---

## Design Principles

- **Human ownership** — You keep control of the system
- **Durable external systems** — Skills and rules live in files, not only in chat history
- **Model agnostic** — The same operating layer should work across different AIs
- **Progressive** — Start simple (Grok files), grow into the full web UI
- **Transparent** — Everything is visible and editable

---

## Current Status

This is the public planning and architecture repository.

The personal implementation currently lives in:
- [Train-Your-Dragon-AI](https://github.com/tripLr/Train-Your-Dragon-AI)

---

## Roadmap (High Level)

1. Solidify the core ruleset and skill format
2. Create clean “Grok upload” packages
3. Design the minimal web UI
4. Add model selection
5. Add ruleset on/off toggles
6. Document how others can fork and run their own version

---

## Name

**Train Your Dragon AI** is the project.  
**All Your Base Are Belong To Us** is the attitude.

You take back control of the context, the rules, and the long-term relationship with the AI.

---

*This is a living public plan. It will evolve.*
