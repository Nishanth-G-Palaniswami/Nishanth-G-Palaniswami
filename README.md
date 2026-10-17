### Start here

Six repos are pinned below. If you have five minutes, these are the decisions worth reading:

- **The agent can't send, by construction.** [`guardrails.py`](https://github.com/Nishanth-G-Palaniswami/second-brain/blob/main/.claude/scripts/security/guardrails.py) in second-brain rejects any Gmail-send call, SDK or REST, before the model can make it. Advisor mode lives in code, not in the prompt.
- **Rules decide, the model writes the memo.** [`triage.mjs`](https://github.com/Nishanth-G-Palaniswami/SovereignDesk/blob/main/engine/triage.mjs) in SovereignDesk: `PRECEDENT_FLOOR` and `PRECEDENT_BIND` were split after a measured false positive; the case is in the comment.
- **Keyword and vector in one query.** [`memory_search.py`](https://github.com/Nishanth-G-Palaniswami/second-brain/blob/main/.claude/scripts/rag/memory_search.py): SQLite FTS5 and sqlite-vec scored together, no separate vector database.
- **Tests gate the marts.** [`census_dbt/tests`](https://github.com/Nishanth-G-Palaniswami/census-trade-warehouse/tree/main/census_dbt/tests): the singular dbt tests a table has to pass before it's published.
- **Never steal focus.** [`overlay.py`](https://github.com/Nishanth-G-Palaniswami/voicebot/blob/main/src/voicebot/overlay.py) in voicebot: the recording indicator stays out of the foreground so the paste lands in your app.

Before got2eat (Backed by Base44) I owned tariff data pipelines at SAIL GTX (Cornell Tech Runway), which is why two of the pins are trade data.

[IEEE ICCCNT 2024 paper](https://ieeexplore.ieee.org/document/10725877) · [Resume](https://nishanthgp.me/resume.pdf)
