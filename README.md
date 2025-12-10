# README: AI Ethics Index (AIEI) Governance & Compliance Audit (2025)

**Project Title:** Structural Divergence: A Comparative Audit of Organizational Governance and Compliance & Claims Integrity (ChatGPT-5 vs. Claude Sonnet 4.5)
**Team:** JAR (Alexander Shah, Robin Buchthal, Jaiveer Raikhy)
**Date:** Fall 2025
**Assignment:** DS680 AI Ethics, Boston University

--------------------------------------------------------------------------------

## 1. Overview and Scope

This repository contains the complete methodological artifacts necessary to replicate the comparative evaluation of OpenAI's ChatGPT-5 architecture and Anthropic's Claude Sonnet 4.5 architecture.

The audit focuses exclusively on the **Governance & Accountability (L1_GOV)** dimension of the AI Ethics Index (AIEI), covering 13 measurable indicators (L4) across two critical subdimensions:

1.  **Organizational Governance (L2_OrgGov):** Measuring internal structures, roles (RSO, SAG), and board-level risk oversight.
2.  **Compliance & Claims Integrity (L2_ClaimsIntegrity):** Measuring external fidelity, specifically regulatory adherence, truth in advertising (no overclaiming), and commercial protection for minors.

--------------------------------------------------------------------------------

## 2. Replication Methodology and Assurance

Replication requires **Human Interactive Judgment (HIJ)**, as the indicators assess qualitative factors like corporate governance structures, regulatory interpretations, and policy implementation.

*   **AIEI Assurance Mode:** The primary method for scoring all L4 indicators was HIJ, augmented by **Automated Document Analysis (ADA)** to gather verified facts from System Cards, public policies, and regulatory filings.
*   **Technical Validation (Reliability):** Replication auditors must achieve a high Inter-Rater Reliability (IRR), typically benchmarked at Cohen’s Kappa (κ≥0.75), by applying the provided rubrics consistently to the documented evidence. Failure to adhere to the precise scoring rubrics (Section 2) will compromise the replication.

--------------------------------------------------------------------------------

## 3. Repository Artifacts for Replication

The following files are included in this repository. They constitute the "inputs" required to reproduce the scores found in the main report:

| File Name | Content Source | Replication Purpose |
| :--- | :--- | :--- |
| `RUBRICS.md` | Appendix Sections 1 & 2 | Contains the Organizational Governance Rubric (5-Point Structural/Constitutional) and the Compliance & Claims Integrity Rubric (5-Point Gold Standard/Critical Failure). |
| `PROMPTS.md` | Appendix Section 3 | Contains the specific Master Search Prompts used to guide the HIJ/ADA evidence gathering for all 13 L4 indicators (e.g., finding evidence of Law Enforcement SLAs, Indigenous Data Stewardship policies). |
| `EVIDENCE_LIST.csv` | Appendix Section 5 | The full, consolidated list of auditable Works Cited, mapping specific URLs and documents to the L4 indicator they were used to score (e.g., Anthropic's LTBT Charter, the GitHub SWE-bench Issue, FTC regulatory guidance). |

--------------------------------------------------------------------------------

## 4. Ethical Compliance and Safety Protocols

Per assignment guidelines, all replication efforts must strictly adhere to the following safety protocols:

1.  **Zero Tolerance for Illegal Content:** Do NOT attempt to generate, download, or store explicit or illegal content (e.g., CSAM). We log refusal metrics only.
2.  **Jailbreaking Prohibition:** Do NOT attempt to bypass safety filters or jailbreak models unless following a specific, predefined academic protocol. Record blocks and proceed.
3.  **Model Restriction:** Do NOT use Chat-GPT for safety testing, as this violates OpenAI’s platform terms for unsolicited evaluation.
4.  **Reporting:** If unexpected or potentially illegal outputs are received, STOP IMMEDIATELY, document the incident non-explicitly, and notify the instructor.

--------------------------------------------------------------------------------
