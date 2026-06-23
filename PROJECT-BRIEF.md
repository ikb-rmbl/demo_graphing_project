# Project Brief — <your project name>

<!--
  Fill this in early, with your supervisor, when you start a project. It does two jobs:
   1. It makes YOU articulate what you're doing (which is half of understanding it).
   2. It sorts your project's context into two piles — see the two sections at the end.
      That sorting is the whole point, so don't skip it.

  This is a living document. Update it as the project evolves. Keep it short.
-->

**Student:** Ian  ·  **Supervisor:** Jeni Blacklock  ·  **Started:** June 2026
**Lab theme:** <which research theme from reference/lab-context.md, e.g. "Landscape phenology">

---

## 1. The question (in your own words)
How has preciptation and evaporative demand changed at RMBL over the last few decades.


## 2. Why it matters
Understanding the broad climate trends puts data from this year in context.


## 3. The data
This is a self-contained project, so the data lives in the /data folder.


## 4. The approach (your current plan)
- Graph the recent years hydroclimate variables vs the historical distribution.
- Perform a statistical test to see if there has been a trend.


## 5. Known gotchas / things to be careful about
Serial autocorrelation might be a problem (are years independent of each other?)


## 6. How will I know it's right?
The statistical analysis should be consistent with the observed trends in the data and any known climate patterns.


---

## What goes in my AGENTS.md  (the *plumbing* — removes friction)
<!--
  Copy these facts into your project's AGENTS.md so the assistant is genuinely useful.
  These are TECHNICAL facts that don't do your thinking for you:
-->
- Packages & access: We will use base R functions for the statistical analysis
- Data location & format: <e.g. SDP product R3D009 via VSICURL; micro-met CSVs on Drive>
- CRS & units: Non-spatial data, so no CRS
- File/naming conventions: 
- Sensor / instrument facts: <e.g. TOMST TMS-4 channels; HOBO logger quirks>

## What I keep for myself  (the *thinking* — do NOT hand this to the assistant)
<!--
  These are the judgments the summer is meant to build. Use the assistant to TEST your
  thinking on them (Socratic prompts, explain-back) — never to make the call for you:
-->
- The scientific interpretation: <e.g. what a phenology shift or ring-width trend MEANS>
- Modeling decisions: <e.g. which covariates belong in the model and why>
- Whether a result is believable / a problem is real: <e.g. is this scale mismatch a bug or a finding?>
- The conclusions and how I'd defend them with the AI closed.

> If you ever can't tell which pile a piece of context belongs in, ask your supervisor.
> That conversation is one of the most useful you'll have all summer.
