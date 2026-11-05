# AdmitMate — AI Admissions Copilot (Portfolio MVP)

A beginner-friendly, front-end prototype for a fictional university admissions journey.

## Run it
1. Download or clone this repository.
2. Open `index.html` in a modern browser. No build tools or API keys are required.

## What works in this MVP
- Student profile form and sample eligibility comparison for three fictional programmes.
- Document checklist with a live completion meter.
- Admissions Q&A demo with predefined answers and a safe fallback.
- Responsive layout for desktop and mobile.

## Important limitations
- All institution, programme, GPA and intake information is fictional.
- The eligibility result is an illustrative rule-based comparison, not an admission decision.
- The assistant is not connected to an LLM yet. It uses predefined answers so the core journey can be tested before adding an AI provider.
- Checklist state is not persisted after refresh in this first version.

## Product decisions
- Start with one fictional university and three programmes to keep the MVP focused.
- Use transparent, rule-based eligibility logic before introducing AI. Eligibility should be grounded in approved programme requirements, not hallucinated by a model.
- Use a safe fallback when the assistant cannot answer and direct users to admissions staff for authoritative decisions.

## Suggested next iterations
1. Add local persistence for checklist progress.
2. Add a programme requirements editor backed by structured data.
3. Add an LLM-powered Q&A layer with retrieval from approved programme documents, citations, refusal/fallback rules and a small evaluation set.
4. Add a counsellor handoff summary.
5. Add event tracking for eligibility checks, checklist completion and assistant fallback rate.
