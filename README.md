# BTN Narrative Review Tool — v5 (blind)

Blind accuracy check of the gpt-5 (de-biased, actor-generalized v5) coding. Open **index.html** in any browser.

## Review (Pass 1) — BLIND
- A fixed random **300 tweets**, the same for everyone (seed-locked, embedded).
- You **code each tweet from scratch** — dropdowns start empty, the model's answer is **hidden**, so you can't be primed.
- Per actor you check: mentioned + framing / overall_framing / government / people / blame (+ people-split); plus primary_topic.
- After you submit, the tool scores you against the hidden model and shows a running **% correct** (95% CI). Download CSV exports only *your* answers + your score (no model labels).
- Keys: Enter = submit & next · S = skip · ← = back.

## Compare P1↔P2
A separate analysis view showing where Pass 1 (date-aware) and Pass 2 (date-blind) differ — this one DOES display model output, for analysts (not for blind review).
