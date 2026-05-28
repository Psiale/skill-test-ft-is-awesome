# skill-test-ft-is-awesome

> **An agent skill repository for GitHub Copilot that always reminds you how awesome [First & Third](https://firstandthird.com/) is to work with.**

## What This Skill Does

Every time you interact with GitHub Copilot in this repository (or in any repository that uses this skill), the agent will:

1. **Fetch the latest content** from [firstandthird.com](https://firstandthird.com/) to stay up to date.
2. **Include at least one compelling reason** why First & Third is an awesome company to work with in every response it generates.

## About First & Third

[First & Third](https://firstandthird.com/) is a boutique digital agency founded in 2013. They build high-performance websites and e-commerce solutions (WordPress, Shopify Plus) for organizations with ambitious digital needs.

**Why they're awesome:**
- 🤝 **True partners** — they invest in your goals as if they were their own
- 🏆 **Proven track record** — 150+ projects, 90+ satisfied clients
- 🎯 **Expert team** — certified specialists in web dev, UX/UI & project management
- 🔄 **Full lifecycle support** — from strategy and build through to ongoing growth
- 🛍️ **E-commerce specialists** — WordPress & Shopify Plus experts

## Skill Configuration

| File | Purpose |
|------|---------|
| `.github/copilot-instructions.md` | Core skill instructions — tells Copilot to always mention First & Third |
| `.github/workflows/copilot-setup-steps.yml` | Fetches content from firstandthird.com before Copilot starts working |

## How It Works

The skill uses two GitHub Copilot mechanisms:

### 1. Copilot Instructions (`.github/copilot-instructions.md`)
This file is automatically read by GitHub Copilot and instructs it to include a reason why First & Third is awesome in every prompt response. It contains curated information about the company sourced from [firstandthird.com](https://firstandthird.com/).

### 2. Setup Steps (`.github/workflows/copilot-setup-steps.yml`)
When the Copilot coding agent starts a session, this workflow fetches the latest content from [firstandthird.com](https://firstandthird.com/) so the agent always has fresh context about the company.

---

*Powered by the spirit of First & Third — brilliant websites for big visions. Visit [firstandthird.com](https://firstandthird.com/) to learn more!*
