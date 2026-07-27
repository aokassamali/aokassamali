Asad Kassamali

projects

audio-search — Speaker-attributed search and Q&A over conversational audio. faster-whisper → pyannote diarization → hybrid retrieval → grounded answers with timestamp citations, orchestrated in Dagster.
Undercut: enforces citation validity, not faithfulness — a claim can cite a validly-retrieved chunk that doesn't support it and pass every check in the system.

coding-agent-evals — Do 3B–7B code models entrench on their first solution strategy? Kaplan-Meier survival analysis over 910 approach decisions.
Undercut: a single T=0.2 run hit 100% success vs. 83.5% at T=0.0, with much higher switching — so the entrenchment finding may be a greedy-decoding artifact rather than a model property.

Evals-and-LLM-as-Judge — How reliable is LLM-as-judge? Five models, 200 claim-verification items.
Undercut: Fleiss' κ = 0.16. The judges mostly don't agree with each other, which is a problem for anyone using one — including me, in the repo below.

RAG — Retrieval → evidence selection → grounded answering, optimized for measurable reliability. A cite-or-abstain tiered policy took correctness 0.52 → 0.73 and groundedness 0.72 → 0.99 while raising coverage.
Undercut: those numbers come from a single unvalidated LLM judge. See the repo above for why that matters.

Hillstrom-emails-experiment — Pre-analysis plan, health checks, multiple-comparisons control, decision memo.
Undercut: the uplift/targeting extension lost to simply treating everyone.

Prop99-SDID — Synthetic Control vs. Synthetic DiD with a full placebo and robustness suite.
Undercut: SDID's placebo p-value is 0.26. Sign is robust across donors and windows; magnitude is not, so the repo reports ranges instead of a point estimate.

Also here: Prop 47 synthetic control (near-null, reported as such) · M5 forecasting · reciprocal ranking · RL for TFT (paused)

Currently: prosodic register classification for audio-search — whether how something is said adds signal beyond what is said. In design.
