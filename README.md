# Structured Prompt Injection Efficacy (SSPI)

This repository hosts the **official releases** of the whitepaper:

**Structured Prompt Injection Efficacy:  
Optimizing Language Model Performance Without Weight Modification**

Author: **Marco N.**  
Affiliation: **HighMark IT - YecoAI**  
Category: **Artificial Intelligence**

---

## 📄 Whitepaper

The full whitepaper is distributed via **GitHub Releases** at the moment.

👉 **Download**  

---

## Abstract

This whitepaper introduces **Simple Structured Prompt Injection (SSPI)**, a formal
prompt architecture designed to achieve deterministic and enterprise-grade behavior
from large language models **without modifying model weights**.

SSPI decomposes prompts into four functional blocks:

- **Absolute Role Declaration (ARD)**
- **Negative Operational Constraints (NOC)**
- **Logical Structure Injection (LSI)**
- **Sequential Activation Trigger (SAT)**

Experimental results across multiple state-of-the-art LLMs show that structured
prompting can achieve performance comparable to fine-tuned models while reducing
cost, deployment complexity, and output variance.

---

## Why This Work Exists

Fine-tuning is often treated as the default solution for specialization.
This work demonstrates that, for a large class of enterprise and applied AI workloads,
**prompt structure alone can unlock latent model capabilities** with:

- comparable accuracy
- higher determinism
- lower total cost of ownership
- faster iteration and deployment

---

## Scope and Positioning

This is **applied industrial research**.

- No new model architectures are proposed
- No training or weight modification is performed
- All results are obtained using base models via structured prompting only

The focus is on **prompt architecture as a control surface** for LLM inference behavior.

---

## License

This work is licensed under **Creative Commons Attribution 4.0 International (CC BY 4.0)**.

You are free to share and adapt this work for any purpose, provided appropriate
attribution is given.

---

## Citation

If you reference or build upon this work, please cite:

```

HighMark IT - Marco N. (2026).
Structured Prompt Injection Efficacy:
Optimizing Language Model Performance Without Weight Modification.
YecoAI

```

---

## Contact

For discussion, feedback, or collaboration:

- Website: https://highmark.it
- GitHub: https://github.com/HighMark-31
