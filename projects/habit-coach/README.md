# AI Habit Consistency Coach

**AariyaTech — Community Project**

**Goal:** Build a lightweight, privacy-first assistant that helps people (especially those with ADHD and students) build and maintain consistent habits through simple check-ins, pattern detection, micro-habit suggestions, and gentle reminders.

---

## Why this matters
Habit formation is a daily struggle for many. Small, empathetic nudges and clear, data-driven patterns can materially improve outcomes — for students, caregivers, and anyone trying to change behaviour. This project focuses on practical, testable features that can be built by the community and expanded into a meaningful product later.

---

## MVP (Minimum Viable Product)
The initial deliverable will be small, privacy-first and easy for contributors to run locally:

- A minimal CLI and/or tiny web demo to log habit check-ins
- Local storage (JSON or SQLite) for check-ins
- Basic analytics: total check-ins, simple streak calculation, simple miss-pattern detection
- A demo reminder mechanism (console or scheduled job)
- Clear README and contribution steps so new contributors can pick tasks

---

## Key features (MVP scope)
- Define simple habits (name, frequency)
- Log check-ins (daily)
- View basic analytics (streaks, total check-ins)
- Suggest a micro-habit when recurring misses are detected
- Console-based reminders for demo mode (extendable to email/push later)

---

## Non-goals for MVP
- No personal data sharing or cloud storage by default  
- No production-grade authentication for MVP  
- No advanced ML in the first iteration — keep it rule-based and extendable

---

## How to get started (for contributors)
1. Fork the main repo and create a branch for your change.  
2. Create or update files under `projects/habit-coach/`. Start simple (README, a small script, sample data).  
3. Open a PR tagged with `good first issue` or link it to a relevant issue using `Closes #<num>`.  
4. Be ready to explain your change in the PR description; maintainers will give feedback.

---

## Development & run notes (for future scaffold)
*(These are placeholders — implement when you add the scaffold files)*

- CLI demo: `node projects/habit-coach/main.js` or `python projects/habit-coach/main.py`  
- API server: `npm run server` -> `http://localhost:3000/api/health`  
- Data storage: keep data in `projects/habit-coach/data/` as JSON or SQLite for MVP

---

## Contribution ideas / good first issues
When you’re ready to invite contributors, good first tasks include:
- Add starter CLI script and sample data
- Implement simple streak calculation and display
- Add a basic Express API endpoint to log check-ins
- Add README badges and usage examples
- Add tests for the streak logic (small unit tests)

---

## Privacy & ethics
- Default to local-only storage. No external sharing without explicit opt-in.  
- Be careful with sensitive language — position the tool as a supportive assistant, not therapy.  
- Include a SECURITY.md and a short Data Handling section in this README when code is added.