This repository accompanies the NeurIPS paper **“HYSYNTH: Context-Free LLM Approximation for Guiding Program Synthesis.”**  
HYSYNTH learns a probabilistic context-free grammar (PCFG) that approximates the distribution of programs produced by an LLM and uses those weights to guide search.

## Repository layout

- **ARC DSL grammar** — `dsl/v0_3/dsl.lark`  
- **PCFG estimation (ARC)** — `compute_pcfg.py`  
- **ARC synthesis runner** — `run_synthesize.py`

---

## Other Domains

- **TF-Coder PCFG estimation** — [`tf_coder/tfcoder_pcfg_modified.py`](https://github.com/shraddhabarke/hysynth/blob/main/tf_coder/tfcoder_pcfg_modified.py)  
- **Probe PCFG** — [Probe](https://github.com/shraddhabarke/Probe/commit/5b625f02b8fe1191e305390f87d4d5870d80131c)
