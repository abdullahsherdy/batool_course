# CLAUDE.md — Batool's Private Coding Course

Source of truth for this project. Read this before generating any session material, practice sheet, or update for Batool's course. Supersedes the client-facing `batool-learning-journey.md` roadmap where the two disagree — that file gets revised to match this one before it's next shared externally.

## Subscription model

- Billed monthly. Client (Batool's mom) has approved and paid for **Month 1**.
- Each month = 4 weekly sessions (90 min each). Continuation is a renewal decision each month, not assumed.
- Content is generated one month at a time, matching what's actually paid for — don't build materials past the current paid month.
- **Month 1 scope (this billing cycle):** Session 0 (diagnostic) + Phase 0, Sessions 1–3. See below.

## Student profile

- Name: Batool, age 13
- Prior experience: Scratch — shallow, not deep. Comfortable with the *idea* of block programming, not with underlying logic.
- English proficiency: low. Bilingual sessions required — see Language Policy below.
- Stated goal (from parent/client): general love of coding + a genuine, strong foundation as a potential future career path. This is a depth-over-pace course.
- Format: private 1-on-1 mentorship, 1 session/week, 90 minutes.

## Curriculum structure (v2 — post-evaluation)

Revised from v1 to add buffer time, a diagnostic session, and a lighter OOP touch, per the senior-engineer/instructor review below. Week numbers are planning estimates, not deadlines — principle #1 below overrides them whenever they conflict.

- **Session 0 (wk 1):** Diagnostic & calibration — not a phase, a single session to confirm her actual starting point before locking pacing.
- **Phase 0 (wk 2–4):** Computational thinking, Scratch bridge — 3 sessions
- **Phase 1 (wk 5–14):** Python fundamentals — 10 sessions (was 9; added a dedicated debugging/error-reading session)
- **Phase 2 (wk 15–19):** Intro OOP — 5 sessions (was 4; treated as a *preview*, not full depth — real OOP depth deferred to Track 2)
- **Phase 3 (wk 20–23):** Data handling & mini-projects — 4 sessions
- **Phase 4 (wk 24–26):** Web fun sprint (HTML/CSS) — 3 sessions
- **Phase 5 (wk 27–30):** Capstone project — 4 sessions (was 3; extra session goes to scoping, to keep the project achievable)

Track 1 now runs ~30 weeks (was 26) — the extra weeks are deliberate buffer, not scope creep. Track 2 (JavaScript / deeper backend topics) gets planned after Phase 5 based on Batool's demonstrated interest — do not pre-plan it now.

## What changed after evaluation, and why

1. **Added Session 0 (diagnostic).** The original plan locked 26 weeks before a single session ran. Session 0 is light, unplugged, low-pressure — it confirms or adjusts everything below before it's treated as fixed.
2. **Added buffer, not just topics.** V1 assigned one Python concept per week with zero slack, which directly contradicted "no advancement over unresolved gaps." V1 phases now carry realistic room for a second pass without breaking the schedule.
3. **OOP is now a preview, not a full block.** 4 sessions to fully teach a new programming paradigm was too tight for a first-time 13-year-old learner. It's now 5 sessions and scoped as an introduction — real depth happens in Track 2, after more fundamentals practice.
4. **Explicit debugging/error-reading session added to Phase 1.** Reading Python tracebacks is taught directly, since typing/spelling errors are a known, named friction point for her profile — better to teach it as a skill than let her rediscover it session by session.
5. **Glossary now has a cadence, not just an intent.** See Language Policy — it's a per-session deliverable now, not a vague ongoing habit.
6. **Capstone extended and scope-constrained.** 3 sessions for plan→build→polish→demo risked an unfinished, deflating ending. Now 4 sessions, and the scoping session's job is explicitly to constrain the project to what's achievable in the time left — not just to brainstorm freely.

## Pedagogical principles (non-negotiable)

1. **No advancement over unresolved gaps.** Week numbers are planning estimates, not deadlines. If a concept isn't solid, the next session re-covers it rather than moving on.
2. **PRIMM lesson structure.** Every new concept: Predict → Run → Investigate → Modify → Make. Never hand her a blank editor for a brand-new concept — she should always meet new syntax inside working code first.
3. **Ownership builds gradually.** Code starts as "not mine" (given, run only) → "partly mine" (modified) → "mine" (built from scratch in the Make phase). Don't skip stages even when she's engaged and wants to jump ahead.
4. **Bridge the Scratch→text gap explicitly.** Watch for the three known failure points: command memorization, typing/spelling errors, and paradigm confusion (block-thinking vs. line-by-line thinking). Name these explicitly when she hits friction — it's expected, not a sign she's behind.
5. **Depth over pace, always.** If a phase needs an extra week, take it. The roadmap is a guide, not a contract.

## Language policy

- Arabic carries explanation, encouragement, discussion.
- English is reserved for code, keywords, error messages, and technical terms — always explained in Arabic on first appearance.
- **Glossary is now a per-session deliverable:** log 5–10 new bilingual terms per session in `glossary.md` (create at Session 0). Start each session with a 2-minute recap of the previous session's terms before introducing new ones.
- Reassess English/Arabic ratio every ~6 weeks. Don't force English faster than her comfort allows.

## Per-session deliverables

Each session should produce, at minimum:
- A short session plan (topic, PRIMM stage breakdown, timing per the 90-minute template in `batool-learning-journey.md`)
- A practice sheet or activity sheet for Batool, following the tiered structure: Warm-Up → Practice → Challenge → Reflection
- The glossary update (5–10 terms, bilingual)
- Any code examples used, saved for reuse/reference in later cumulative review

## Milestones & parent reporting

- Each phase ends in a small milestone project (not a test).
- Send a short parent update after each phase milestone: what Batool built, what's next. Keep it warm, non-technical, and specific to her (not generic progress-report language).
- Since billing is monthly, the Month 1 update doubles as the renewal-decision touchpoint — make the value of the first 4 sessions clear and concrete, not just "on track."

## Open items — confirm before Session 0

- [ ] Device/setup (own laptop vs. session-only access)
- [ ] Coding environment for Python (beginner-friendly online editor vs. local install)
- [ ] Any school curriculum to align with
- [ ] Parent reporting channel and frequency

## Now building: Month 1 content

Next actions, in order:
1. Session 0 — diagnostic & calibration pack (unplugged activities + light Scratch revisit, plus a short instructor-facing calibration note to confirm/adjust the roadmap above)
2. Session 1 (Phase 0) — sequencing & precise instructions
3. Session 2 (Phase 0) — revisiting Scratch with programming vocabulary
4. Session 3 (Phase 0) — Scratch-to-Python bridge

Each gets: session plan, practice sheet, glossary starter, code examples — per "Per-session deliverables" above.

## Change log

- v1 — initial plan drafted, pending confirmation on open items above
- v2 — revised after senior-engineer/instructor evaluation: added Session 0 diagnostic, buffer time across phases, extended and re-scoped OOP and capstone, added debugging session, made glossary a per-session deliverable. Added subscription/Month 1 scope section following client approval and first month's payment.
