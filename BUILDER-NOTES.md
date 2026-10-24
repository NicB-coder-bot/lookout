# Builder notes: nothing to build yet

## What happened
- The task was "Follow the details under: What should this workflow make?", but the details never arrived (see `research.md`).
- Builder's standing instructions say to build the **Helper chat bubble** for the agentbox panel.
- That Helper **already exists**. It was built, tested at 1366px and 390px on a dev copy (port 3100), and merged in
  `~/projects/agentbox-panel` (commits `9ee6523`, `44b2e53`, `76f8403`; see the "v2.1" sections of that project's `NOTES.md`).
  Later work (v3, PR #11) taught it the new pages too.
- This "lookout" project is empty (just a one-line README). It has no panel, agents, runs or database for a Helper to talk about.

## What I decided
- **I did not build a second Helper here.** A copy in an empty project couldn't see anything, and it would drift away from the real one.
- I changed no code. This note is the only change.

## What Nic can do next
1. Fill in **"What should this workflow make?"** in the panel and run the workflow again, **or**
2. If you wanted changes to the Helper, run the workflow on the **agentbox-panel** project and say what to change
   (for example "the Helper should also…").
3. If "lookout" is meant to be something new, write one or two sentences in its README about what it should watch or do.
