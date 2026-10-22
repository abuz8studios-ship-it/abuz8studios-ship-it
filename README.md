# ABUZ8 — Sovereign AI built in the open.

One-person lab (Dayton, Ohio). Arabic-first brains, local inference, agent systems.
GitHub holds the **code**, [Hugging Face](https://huggingface.co/abuz8studios) holds the **weights and data** — every project below links both ways.

ABUZ8 is a one-person research lab building a geometrical Arabic reasoning brain — Arabic roots and morphological patterns treated as geometry — that reasons with Quranic principles of verification (isnad): every claim carries its chain of evidence.

## Brains — weights & data on Hugging Face

| Brain / dataset | Hugging Face | Code here | Status |
|---|---|---|---|
| SUPERBRAIN-1 (9B Arabic roots + math, Fanar-1-9B) | [model](https://huggingface.co/abuz8studios/SUPERBRAIN-1) · [lab runs](https://huggingface.co/abuz8studios/SUPERBRAIN-1-lab) | private — opens on release | Active research — v4 soup_90_10 champion (2026-10-17); ArabicMMLU 47.48% verified 2026-10-20; scores + verdict files on the card |
| Qadir-v1-v2 (LoRA adapters, tool use) | [model](https://huggingface.co/abuz8studios/Qadir-v1-v2) | — | Research adapters + evals published |
| FAIE (local MoE inference research) | [code/papers](https://huggingface.co/abuz8studios/FAIE) · [proofs](https://huggingface.co/abuz8studios/FAIE-proofs) | private — opens on release | Research — weights not redistributed pending license |
| MUTHALLATH-1-m0 | [experiment log](https://huggingface.co/abuz8studios/MUTHALLATH-1-m0) | private — opens on release | Honest negative-result log |
| Arabic Ṣarf Packet B (held-out test, 258 unseen roots) | [dataset](https://huggingface.co/datasets/abuz8studios/arabic-sarf-packet-b) | private — opens on release | Published eval data |
| Arabic Science Packet A10 | [dataset](https://huggingface.co/datasets/abuz8studios/arabic-science-packet-a10) | — | Published with build/check tools |
| Arabic Code Packet A11 | [dataset](https://huggingface.co/datasets/abuz8studios/arabic-code-packet-a11) | — | Published with build/score tools |

## Systems — code here

- [silent-ok-audit-kit](https://github.com/abuz8studios-ship-it/silent-ok-audit-kit) — find agent work that reports OK while shipping nothing (ending-state classifier; MIT, tests included)
- [proofloop](https://github.com/abuz8studios-ship-it/proofloop) — no "done" without disk/live proof; local trust ladder L0–L4, deterministic verify (69 tests; optional Gemini/Cloud Run not live)
- [abuz8-field-notes](https://github.com/abuz8studios-ship-it/abuz8-field-notes) — working recipes for local AI agent setups (Hermes, OpenClaw)

## Elsewhere

- Site: [abuz8ai.com](https://abuz8ai.com) — free tools, guides, AI news/benchmarks/models
- X: [@AbuZ8Studios](https://x.com/AbuZ8Studios)
- Contact: support@abuz8ai.com

*Status labels are literal: "active research" and "WIP" mean still moving; scores are always on the model card or in the repo, never in the pitch.*
