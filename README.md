# BTN Narrative Review Tool — v5

Spot-check the gpt-5 (de-biased, actor-generalized v5) coding for accuracy. Open **index.html** in any browser.

## Two modes (top-left toggle)
- **✍ Review (Pass 1)** — review the model's **Pass 1 (date-aware)** coding. A fixed random **300 tweets** — the same 300 for everyone (seed-locked, embedded). For each mentioned actor you check `framing`, `overall_framing`, `government`, `people`, `blame` (+ people-split) and `primary_topic`. Model's `blamed_for` + evidence shown for context. Any dropdown change counts as a disagreement; live agreement % (95% CI). Download CSV exports your calls + the model's side-by-side.
- **⇄ Compare P1↔P2** — read-only view of where **Pass 1 (date-aware)** and **Pass 2 (date-blind)** disagree, per tweet and per field (the date-contrast reliability check).

Keys (Review): Enter = save & next · R = reset to model · S = skip · ← = back.
Data embedded from the v5 pass-1/pass-2 coding.
