# Phase 0 · Session 0.2 — How Code Actually Runs
**Duration:** 90 min · **Format:** Mix of unplugged + a simple visual step-tracer

## Session goal
Batool can trace a short instruction list step-by-step exactly as a computer would — one
instruction at a time, in strict order — and understands that mistakes ("bugs") are a normal,
expected part of this process, not a sign of failure.

## Recap (5 min)
2-minute glossary recap of Session 0.1 terms before introducing anything new (per course
language/glossary policy).

## PRIMM breakdown

### Predict (10 min)
Show her a short numbered list of instructions (e.g., a 5-step "get dressed" list) with the
steps **out of a sensible order** (e.g., "put on shoes" before "put on socks"). Ask: "What do
you think will happen if someone follows this exactly, in this order, no skipping, no
reordering?" Let her predict the funny/broken result before running it.

### Run (15 min)
Actually act it out (or have her act it out) literally, step by step, in the given order,
changing nothing. Confirm the predicted breakage happens. Key line to land here: *"The
computer didn't get it wrong — it did exactly what the list said. The list was wrong."*

### Investigate (20 min)
New vocabulary:
- **Sequence** — instructions run one at a time, strictly in the order written; the computer
  never jumps ahead or reorders on its own.
- **Step-by-step execution** — same as "run/execute" from 0.1, now emphasizing the *order*
  matters as much as the instruction itself.
- **Bug** — a mistake in the instructions (not in the computer) that causes a wrong or broken
  result.
- **Debugging** — the process of finding and fixing that mistake — a normal, expected skill,
  not a sign of being "bad at this."

Use a simple visual: number the steps vertically, draw an arrow moving down one at a time,
pausing to say out loud what "the computer" is doing/holding at each step. This is a soft,
unplugged precursor to reading code execution/tracing later in Python.

### Modify (25 min)
Give her 2–3 more small step lists with the *order* broken (not the wording — order is the
target skill here). She reorders them into a sequence that actually works, then re-traces it
step-by-step out loud to confirm.

### Make (15 min)
She writes a new 5–7 step sequence for something of her choosing, deliberately checks it by
tracing it herself step-by-step as "the computer would," and finds/fixes at least one issue on
her own if she can — framed as practicing debugging, not as a test.

### Wrap-up (5 min)
Ask: "If a program doesn't work, whose fault is it usually — yours or the computer's? Why?"
Goal: she says "the instructions" without hesitation.

## What "done" looks like
- Can trace a short list of steps strictly in order, out loud, without skipping/reordering.
- Uses "sequence," "bug," "debugging" correctly and without embarrassment about the last one.
- Independently catches at least one ordering mistake in a step list.

---

# Practice Sheet — How Code Actually Runs

## 🟢 Warm-Up
1. True or false: a computer can skip a step if it looks unnecessary. Explain your answer.
2. What is a "bug"? Whose fault is it usually?

## 🟡 Practice
Here is a sequence with the steps out of order. Renumber them into a sequence that actually
works, then trace it step-by-step out loud to check yourself.

- ___ Put toothpaste on the toothbrush
- ___ Rinse your mouth
- ___ Pick up the toothbrush
- ___ Brush your teeth
- ___ Put the toothbrush down

## 🔴 Challenge
Write your own 6-step sequence for a morning routine. Then deliberately swap two steps to
create a bug. Trace the buggy version step-by-step and describe exactly what goes wrong —
then fix it.

## 💭 Reflection
- Was there a bug you didn't notice until you traced it step-by-step?
- How did it feel to call something "a bug" instead of "a mistake I made"? Different?
