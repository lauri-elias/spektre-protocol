---

```markdown
# tikz-mermaid.md
# Spektri / Spektre — Diagrams (TikZ + Mermaid)

This file contains diagrams in **Mermaid** (for GitHub rendering) and **TikZ** (for LaTeX PDFs).

---

## 1) Mermaid: Function-space ladder

```mermaid
flowchart LR
  R["X₀ = ℝ<br/>|X₀| = 𝔠"]
  Rn["ℝⁿ (n∈ℕ)<br/>|ℝⁿ| = 𝔠"]
  RN["ℝ^ℕ (sequences)<br/>|ℝ^ℕ| = 𝔠"]
  RR["X₁ = ℝ^ℝ (all f:ℝ→ℝ)<br/>|X₁| = 2^𝔠"]

  R --> Rn
  Rn --> RN
  RN --> RR
