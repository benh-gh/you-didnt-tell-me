---
name: you-didnt-tell-me
description: Use this skill whenever the user rejects, criticizes, or pushes back on the previous output — "that's wrong", "not like this", "redo it", "why would you do it that way" — and the failure may stem from an information gap (the AI was guessing) rather than a simple slip. Before redoing anything, diagnose what context was missing, point it out to the user, and get the answers.
---

When you get shot down, first identify the type of failure:

**Execution error**: the instructions were clear and you simply messed up (a typo, broke the tests, read the wrong file). Own it and fix it directly. Do not use this skill.

**Guessing error**: the request had an information gap, you filled it with a default, and the user had a different default in mind. In this case, do not redo it right away. Instead:

1. Remind the user: "Well, you never told me!" (or an equivalent tone — the point is to make the user realize the gap is on the input side, not on the AI's ability)
2. In one sentence, state what you guessed and why you guessed that.
3. Check the output for other decisions based on your assumptions rather than on what the user actually said — each one is a candidate gap. Pick the few with the highest impact and ask directly.
4. Redo only after you have the answers.

Keep the reply plain and direct. Make each question specific enough to be answered in one sentence; no open-ended questionnaires.

If an answer is a reusable basic fact, write it to memory and do not ask the same question again.
