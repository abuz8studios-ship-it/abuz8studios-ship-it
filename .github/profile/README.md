# Ahmad Odeh — Founder, ABUZ8 LLC

**Local AI systems, agent infrastructure, and dealer software. Dayton, Ohio.**

I build AI that runs on hardware the owner controls: custom inference engines, multi-agent operating systems, and production software — from a private lab built around two RTX 5090 GPUs. Everything below is public and checkable. Scores live on the model cards and in the repos, never in the pitch.

**Work with me:** [abuz8ai.com](https://abuz8ai.com) · abuz8studios@gmail.com
**Elsewhere:** [Hugging Face — weights & data](https://huggingface.co/abuz8studios) · [X — @AbuZ8Studios](https://x.com/AbuZ8Studios) · [LinkedIn — Ahmad Odeh](https://www.linkedin.com/in/ahmad-odeh-318b7a345/)

---

## The lab

- **Pegasus** — dual RTX 5090 (32 GB each), Ryzen 9 9950X, 128 GB DDR5. Local inference, model training, and media generation, on-premises.
- **Operating rule** — no claim ships without evidence behind it: a built artifact, a measured test, or a live check. Status labels on this page are literal; "work in progress" means still moving.

## Flagship systems

| System | What it is | Record |
|---|---|---|
| **FAIE2 / FAIE2-FlashNext** | Custom CUDA inference engine, written from scratch — [faie2](https://github.com/abuz8studios-ship-it/faie2) · [faie2-flashnext](https://github.com/abuz8studios-ship-it/faie2-flashnext) | Serves a 180B MoE model locally; 170+ tok/s measured batch-1 decode on dual RTX 5090 |
| **ABUZ8 OS** | Agent operating environment — [abuz8-os](https://github.com/abuz8studios-ship-it/abuz8-os) | v2.68.0 |
| **QadirOS** | Agent operating system, 170 tools, Windows executables — [qadir-app](https://github.com/abuz8studios-ship-it/qadir-app) | v1.0.0 "Mach 3", shipped |
| **LotVue360** | Vehicle photos → interactive 360° listings for independent dealerships — [car-360-viewer](https://github.com/abuz8studios-ship-it/car-360-viewer) | Dealer plan: $99/mo, first 5 vehicles free |
| **OpenClaw Desktop (OPC-1)** | Local home for AI agents: native MCP, bundled llama.cpp, click-to-run Windows — [openclaw-desktop](https://github.com/abuz8studios-ship-it/openclaw-desktop) | Public product release |
| **Showfront** | Vehicle photos → 360 spin, 3D walkaround, commercial, and listing — [showfront](https://github.com/abuz8studios-ship-it/showfront) | Built for the Meta Global AI Developer Hackathon, Oct–Nov 2026 |

## Brains — weights & data on Hugging Face

| Brain / dataset | Hugging Face | Code here | Status |
|---|---|---|---|
| SUPERBRAIN-1 / AHMAD-1 (9B Arabic roots + math, Fanar-1-9B) | [model](https://huggingface.co/abuz8studios/SUPERBRAIN-1) · [lab runs](https://huggingface.co/abuz8studios/SUPERBRAIN-1-lab) | [superbrain-1](https://github.com/abuz8studios-ship-it/superbrain-1) | Active research — champion soup_90_10 (v4); passed internal eval gate 0.906 vs 0.847 baseline; ArabicMMLU 47.48% (verified 2026-10-20) |
| Qadir-v1-v2 (LoRA adapters, tool use) | [model](https://huggingface.co/abuz8studios/Qadir-v1-v2) | — | Research adapters + evals published |
| FAIE (local MoE inference research) | [code/papers](https://huggingface.co/abuz8studios/FAIE) · [proofs](https://huggingface.co/abuz8studios/FAIE-proofs) | [faie](https://github.com/abuz8studios-ship-it/faie) | Research — weights not redistributed pending license |
| MUTHALLATH-1-m0 | [experiment log](https://huggingface.co/abuz8studios/MUTHALLATH-1-m0) | [superbrain-1](https://github.com/abuz8studios-ship-it/superbrain-1) | Honest negative-result log |
| Arabic Ṣarf Packet B (held-out test, 258 unseen roots) | [dataset](https://huggingface.co/datasets/abuz8studios/arabic-sarf-packet-b) | [superbrain-1](https://github.com/abuz8studios-ship-it/superbrain-1) | Published eval data |
| Arabic Science Packet A10 | [dataset](https://huggingface.co/datasets/abuz8studios/arabic-science-packet-a10) | — | Published with build/check tools |
| Arabic Code Packet A11 | [dataset](https://huggingface.co/datasets/abuz8studios/arabic-code-packet-a11) | — | Published with build/check tools |

*(Hugging Face links verified live on 2026-10-30.)*

## Verification tooling — the discipline, as software

- [proofloop](https://github.com/abuz8studios-ship-it/proofloop) — no "done" without disk/live proof; local trust ladder L0–L4, deterministic verify, 69 tests
- [silent-ok-audit-kit](https://github.com/abuz8studios-ship-it/silent-ok-audit-kit) — finds agent work that reports OK while shipping nothing (ending-state classifier, run ledger, scorecard)
- [isnad-verify](https://github.com/abuz8studios-ship-it/isnad-verify) — chain-of-custody verification for claims and sources: every statement keeps its evidence chain
- [claimed-not-done-checker](https://github.com/abuz8studios-ship-it/claimed-not-done-checker) — paste a claim and its evidence, get one verdict: VERIFIED, CLAIMED-ONLY, or DISPUTED
- [raqib-supervisor](https://github.com/abuz8studios-ship-it/raqib-supervisor) — declarative process supervisor for local AI service fleets on Windows
- [ask-abuz8](https://github.com/abuz8studios-ship-it/ask-abuz8) — voice concierge over MCP that reports fleet status only from verified state

## The full shelf

37 public repositories, MIT-licensed — agent systems ([abuz8-agent-hub](https://github.com/abuz8studios-ship-it/abuz8-agent-hub), [consoleai](https://github.com/abuz8studios-ship-it/consoleai), [studio-os](https://github.com/abuz8studios-ship-it/studio-os)), local-first tools ([pdf-knowledge-extractor](https://github.com/abuz8studios-ship-it/pdf-knowledge-extractor), [splat-viewer](https://github.com/abuz8studios-ship-it/splat-viewer), [live-crm](https://github.com/abuz8studios-ship-it/live-crm)), field notes ([abuz8-field-notes](https://github.com/abuz8studios-ship-it/abuz8-field-notes)), and the site source ([abuz8ai-site](https://github.com/abuz8studios-ship-it/abuz8ai-site)). Full list: [github.com/abuz8studios-ship-it?tab=repositories](https://github.com/abuz8studios-ship-it?tab=repositories)

## Services

ABUZ8 LLC sells what the record above supports:

- **Sovereign AI Setup** — private AI running on your own hardware. $150 readiness assessment · $500 single-workstation install · $1,000 full deployment. Details: [abuz8ai.com](https://abuz8ai.com)
- **Agent systems** — multi-agent builds and audits for teams whose agents report "done" without proof.
- **LotVue360** — photo-to-360° listings for independent dealerships, $99/mo.

ABUZ8 is pre-revenue and building in public. No client names or testimonials are listed because none are claimed before they exist.

*Status labels are literal: "active research" and "work in progress" mean still moving; scores are always on the model card or in the repo, never in the pitch.*
