# Severity & Case Classification — Pharmacovigilance Analysis

## Task Description
Classify adverse drug reactions based on seriousness and expectedness. Evaluate multiple cases and determine their clinical impact using pharmacovigilance guidelines.

## Pharmacovigilance Guidelines Used

**Seriousness** — An adverse event is classified as **Serious** if it results in:
- Death
- A life-threatening condition
- Hospitalization (or prolongation of existing hospitalization)
- Persistent or significant disability
- A congenital anomaly
- Another medically important condition

Otherwise, it is classified as **Non-serious**.

**Expectedness** — An adverse event is classified as:
- **Expected** — consistent with the drug's approved product information (label / SmPC) or known pharmacological characteristics of the drug
- **Unexpected** — not consistent with the drug's label or known characteristics

## Case Analysis

| Case | Drug | Adverse Reaction | Seriousness | Expectedness | Rationale |
|------|------|-------------------|--------------|----------------|-----------|
| 01 | Amoxicillin | Skin rash, itching | **Non-serious** | **Expected** | Mild cutaneous hypersensitivity reactions (rash, pruritus) are common, well-documented adverse effects listed on the amoxicillin label. No hospitalization, disability, or life-threatening feature present. |
| 02 | Ibuprofen | Gastrointestinal bleeding requiring hospitalization | **Serious** | **Expected** | Meets the seriousness criterion via hospitalization. GI bleeding is a well-recognized, labeled risk of NSAIDs, including ibuprofen, particularly with prolonged or high-dose use. |
| 03 | Metformin | Lactic acidosis | **Serious** | **Expected** | Lactic acidosis is a rare but life-threatening/medically important condition, satisfying the seriousness criterion. It is a well-known, labeled (boxed-warning-level) risk associated with metformin, especially in renal impairment. |

## Summary

| Category | Cases |
|----------|-------|
| Serious | 02 (Ibuprofen), 03 (Metformin) |
| Non-serious | 01 (Amoxicillin) |
| Expected | 01, 02, 03 |
| Unexpected | None |

All three reactions in this dataset are **expected** per current product labeling; two of the three (Ibuprofen, Metformin) meet **seriousness** criteria due to hospitalization or life-threatening potential, while the Amoxicillin case remains non-serious.




