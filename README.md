# Nirnay — Rural Entrepreneur Decision Guide

**Women Who Master Hackathon 2026** | Aspire For Her × Logitech  
Problem Statement 3: *Rural Entrepreneurship — From Local Opportunity to the Next Evidence-Based Decision*

Submitted by: Sanskriti Shukla | Registration: WWM26-MUM-G-T044-M04 | Location: Mumbai

---

## What is Nirnay?

Rural women entrepreneurs often have a real skill and a real product — but no reliable way to know if an idea is actually profitable before investing their savings. **Nirnay** is a team of 11 specialist GenAI advisors that takes one entrepreneur's business idea and turns it into a single clear, evidence-based decision: **Proceed, Pilot, Modify, Collaborate, Test Further, or Pause.**

Built for **Radha**, a home-based pickle maker in rural Maharashtra weighing whether to expand beyond her village.

## 🔗 Live App
[Try Nirnay on PartyRock](https://partyrock.aws/u/Kuromi05/SgVDia2mn/Nirnay%253A-Rural-Women-Entrepreneur-Decision-Guide)

## 📊 Full Presentation
See presentation for the complete pitch deck, covering the problem, solution design, GenAI workflow, testing results, responsible AI considerations, and impact/feasibility analysis.

---

## How It Works

1. She shares her business details and selects her language
2. **Business Analyst** sharpens her idea into a clear, specific opportunity
3. **Market Researcher** suggests a low-cost way to test real demand
4. She enters her costs — **Chief Accountant** calculates margin and break-even, line by line
5. **Sales Strategist** and **Risk Officer** compare channels and flag risks
6. **Second Opinion** challenges her weakest, most untested assumption
7. **Marketing Coach** drafts a WhatsApp-ready pitch; **Marketing Poster** generates a visual
8. **Decision Card** ties everything together into one final, transparent recommendation with a 30-day action plan

## What's Distinctive

- Not one chatbot — 11 specialist agents functioning like a real advisory panel
- Every number is calculated transparently, never asserted as fact
- Actively challenges the entrepreneur's assumptions instead of just agreeing
- Multilingual, including regional languages — not just English
- Clearly separates facts, assumptions, calculations, and missing evidence, as required by the problem statement

## Built With

- **Platform:** [PartyRock](https://partyrock.aws) (Amazon Bedrock) — a no-code GenAI app builder
- **Model:** Anthropic Claude 4.6 Sonnet
- **Image generation:** Stability AI Stable Image Core v1.1

> PartyRock apps are built and hosted entirely on Amazon's platform and aren't exportable as a traditional codebase. This repository contains our presentation, documentation, and testing evidence in place of source code — the working prototype itself is linked above.

## For Beginners: What is PartyRock?

PartyRock is Amazon's no-code tool for building GenAI-powered apps out of connected "widgets" — each one an AI agent, input form, or output display that can reference other widgets' outputs. No coding is required; the entire app is built through prompts and a visual, drag-and-drop interface. Learn more at [partyrock.aws](https://partyrock.aws).

## Testing Summary

| Test | Scenario | Result |
|---|---|---|
| Standard case | Radha's pickle business, full cost data | ✅ Pass |
| Language & accessibility | Same business, Marathi selected | ✅ Pass |
| Difficult case | Incomplete data, price below cost | 🟡 Iterated — refined prompts to explicitly flag missing data instead of inventing it |

Full testing details, screenshots, and scenario breakdowns are in the presentation.

## Responsible AI

Nirnay is designed to recommend, not decide — the entrepreneur makes the final call. Key safeguards include: minimal data collection, channel recommendations weighted by the entrepreneur's actual access and constraints (not one-size-fits-all), strict separation of facts vs. assumptions vs. verified information, transparent line-by-line financial calculations, and a dedicated Second Opinion step that challenges the weakest assumption before any final recommendation. Full details in the presentation.
