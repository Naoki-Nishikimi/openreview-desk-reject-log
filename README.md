# ICLR 2026 OpenReview Desk Rejection – Public Review Log Archive

**Press Summary**

This repository provides a structured, verifiable archive of publicly accessible OpenReview records associated with an ICLR 2026 submission that received a desk rejection.  
It consolidates review texts, author rebuttals, reviewer score and confidence snapshots, and the originally submitted paper, preserving them in a stable and readable format due to access limitations on the original platform.  
The repository does not assert misconduct, intent, or evaluative judgments; instead, it documents observable procedural facts and timelines as they appear in public logs.  
All materials are derived exclusively from publicly available sources, enabling independent readers, journalists, and researchers to directly verify the review process and draw their own conclusions.

---

## Purpose

This repository provides a **structured, verifiable archive** of publicly accessible
OpenReview records related to an ICLR 2026 submission that received a desk rejection.

The purpose of this repository is **not** to accuse, speculate, or assign intent.

Instead, it aims to:
- Preserve publicly visible OpenReview materials in a stable format
- Organize review, rebuttal, and metadata logs for third-party inspection
- Enable independent readers to verify procedural timelines and records directly

All materials are derived exclusively from **public OpenReview pages**.

---

## Scope and Principles

**Included**
- Desk rejection notice
- Reviewer comments and scores
- Author rebuttal text
- Publicly visible reviewer confidence values
- Time-stamped screenshots for verifiability
- The originally submitted paper (unaltered)

**Excluded**
- Private communications
- Identity inference beyond OpenReview pseudonyms
- Claims of misconduct, bias, or intent
- Interpretive or evaluative language

**Operating principles**
- Descriptive, not accusatory
- Primary sources over commentary
- No claims beyond what is directly observable

---
## Distinction Between Desk Rejection Grounds and Reviewer Concerns

The desk rejection of this submission was formally issued on the basis of
**citation and bibliographic accuracy issues**, as stated by the Program Chairs.

Separately, multiple reviewers provided substantive technical and conceptual
evaluations of the paper during the review phase.

To avoid conflation of these two distinct aspects, this repository explicitly
distinguishes between:

- **Desk rejection grounds**  
  → Bibliographic and citation-related issues cited by the Program Chairs

- **Reviewer concerns**  
  → Technical, conceptual, and presentation-related points raised in reviews

The table below summarizes reviewer-visible concerns and observable interactions
*without asserting causality or responsibility*.

---

## Reviewer Summary Table (Public Observations)

| Reviewer ID | Initial Score | Key Stated Concerns (Summary) | Author Rebuttal Coverage | Post-Rebuttal Reviewer Response | Score Change Observed |
|------------|---------------|-------------------------------|--------------------------|----------------------------------|----------------------|
| dYzc | 0 (Strong Reject) | LLM authorship concern; TSR characterization; terminology clarity | Mathematical and conceptual responses provided to all stated points | No substantive response observed | None |
| 4mjb | 0 (Strong Reject) | Reproducibility; experimental clarity | GitHub-based reproduction logs and clarifications provided | No response observed | None |
| 1G3A | 2 (Reject) | Professionalism; novelty; reproducibility | Prior concerns addressed with references and explanations | Brief informal response; no follow-up | None |
| cbU2 | 2 (Reject) | Technical simplicity; theoretical depth | Conceptual framing and novelty clarified | No further response observed | None |

**Notes**
- All entries are derived solely from publicly visible OpenReview records.
- The table reports *observable statements, responses, and score logs only*.
- No claims are made regarding reviewer intent, adequacy, or correctness.
- Supporting reproduction logs referenced in this table are archived at:
  https://github.com/APF-Consortium/APF_Reproducibility_Study_ICLR2026


---

## Repository Structure

```
openreview-desk-reject-log/
├─ README.md
├─ LICENSE
├─ 01_rebuttal/
│  ├─ README.md
│  ├─ iclr2026_rebuttal_with_meta_review.png
│  └─ iclr2026_rebuttal_with_meta_review_url.png
├─ 02_submitted_paper/
│  └─ (original submission files, unmodified)
└─ 03_reviewer_confidence/
   ├─ README.md
   ├─ reviewer_4mjb_confidence_2025-11-21.png
   ├─ reviewer_4mjb_confidence_2025-11-26.png
   └─ reviewer_4mjb_confidence_2026-01-18.png
```

Each directory contains its own README describing context and capture method.

---

## Data Source

Primary source:
- OpenReview (ICLR 2026 submission forum)

The original OpenReview page remains the authoritative source.
This repository exists to **preserve accessibility and readability**.

---

## Capture Method

- Screenshots were captured using **GoFullPage**
- Dates are encoded in filenames
- No visual modifications were applied
- URL-context screenshots are included where relevant to ensure traceability

---

## Notes on Interpretation

- “No response observed” is used only when no public reply exists after a rebuttal
- Score or confidence values are recorded exactly as displayed
- Absence of activity is treated as an observable state, not an inference

Readers are encouraged to:
1. Inspect the archived materials
2. Compare with the original OpenReview page
3. Draw independent conclusions

---

## Disclaimer

This repository is provided for documentation and research purposes only.

- All reviewer identifiers are OpenReview-assigned pseudonyms
- No attempt is made to identify real individuals
- No allegation of misconduct or ethical violation is asserted

This archive records **what is visible**, not **why it occurred**.
