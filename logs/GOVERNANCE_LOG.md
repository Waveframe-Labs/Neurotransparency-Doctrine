---
filetype: governance_log
version: 1.0.0
created: 2025-12-04
maintainer: Waveframe Labs
authority: Aurora Research Initiative (ARI)
---

# Neurotransparency Doctrine — Governance Log

This log records governance decisions, approvals, and oversight actions for the **Neurotransparency Doctrine** repository.  
It is the canonical governance trace for how the doctrine is maintained under **ARI** standards.

---

## 1. Governance Events

| Date       | Action                                         | Role       | Outcome      | Notes |
|------------|-----------------------------------------------|-----------|--------------|-------|
| 2025-12-01 | Creation of standalone Doctrine repository     | Maintainer | ✅ Approved   | Doctrine split out from AWO archives into its own ARI-governed repo. |
| 2025-12-01 | Doctrine v1.0.0 content freeze for release     | Maintainer | ✅ Approved   | Text aligned with ARI governance; dependencies limited to NTS. |
| 2025-12-01 | Repository structure + metadata review         | Auditor    | ✅ Compliant  | `README.md`, `CITATION.cff`, `.zenodo.json`, and descriptors verified against ARI norms. |
| 2025-12-01 | PDF handling policy confirmed (Forge only)     | Auditor    | ✅ Compliant  | PDFs to be generated deterministically via Waveframe PDF Forge and attached only as release assets. |

---

## 2. Governance Position

- The Doctrine is treated as a **Layer 0 epistemic primitive** under ARI.
- Implementation, enforcement, and runtime concerns are delegated to:
  - Neurotransparency Specification (NTS)
  - Aurora Workflow Orchestration (AWO)
  - CRI-CORE

Any modification to the doctrine’s axioms, core principle, or adoption requirement:

1. must be recorded in this log,  
2. must update the version in `doctrine/Neurotransparency_Doctrine.md`, and  
3. must be reflected in `CITATION.cff` and `.zenodo.json`.

---

**Governance Authority:** Waveframe Labs / Aurora Research Initiative (ARI)  
**Contact:** swright@waveframelabs.org
