# A systematic review of materials processing and reliability evidence in FDM printed wearable sensors

This repository is the public, versioned companion to the systematic review by Mohamed Elgendi, Pooja Gurram, Swarubini P. J., Alexander V. Shokurov, and Carlo Menon.

The review searched PubMed, Scopus, IEEE Xplore, Web of Science Core Collection, and Embase on 1 September 2026 for eligible journal articles published from 2016 through the search date.

- 13,761 records were exported from the five databases.
- 6,447 duplicate records were removed, leaving 7,314 unique records.
- 1,079 reports were retrieved and assessed at full text.
- The final corpus contains 76 studies and 80 eligible FDM/FFF sensor configurations.

Eligible studies reported original experimental sensor-response data from a wearable or clearly wearable-relevant device. FDM/FFF had to fabricate the sensing element itself or a structure essential to transduction or mechanical load transfer.

## Reliability Evidence Benchmark

The review applies an eight-component Reliability Evidence Benchmark (REB) as a study-level evidence audit:

| Item | Evidence dimension | Studies meeting the minimum criterion |
|---|---|---:|
| L1 | Fabrication parameters | 33/76 |
| L2 | Material composition | 75/76 |
| L3 | Calibration or reference method | 76/76 |
| L4 | Quantitative response metric | 76/76 |
| L5 | Repeated-measurement stability | 62/76 |
| L6 | Environmental or use-related exposure | 31/76 |
| L7 | Integration or interface integrity | 19/76 |
| L8 | Independent-device variation | 17/76 |

The eight-component profile is the primary REB output. It records whether predefined evidence was explicitly located; it is not a measure of intrinsic device reliability, a predictor of service lifetime, or a pass/fail score.

## Main findings

- Thermoplastic elastomers were used in 55 of the 76 studies.
- Resistive or piezoresistive transduction accounted for 37 of the 80 eligible configurations.
- FDM/FFF directly produced the active sensing element in 30 configurations.
- Cyclic testing was substantially more common than evidence that calibration was retained after environmental exposure, through device integration, and across independently fabricated devices.
- The most frequent methodological and applicability concerns involved specimen selection, control of fabrication variables, and independent-device replication.

## Current reproducibility package

The manuscript defines four supporting data files:

1. [**Supplementary Data 1**](Supplementary_Data_1_Master_Extraction_76_Studies.xlsx) — the 76-study extraction database, with final study-level REB profiles synchronized to the adjudicated consensus.
2. [**Supplementary Data 2**](Supplementary_Data_2_Final_Full_Text_Eligibility_76.xlsx) — report-level full-text decisions and the recorded verification of the 13 extraction-stage exclusions.
3. [**Supplementary Data 3**](Supplementary_Data_3_Executed_Search_Strategies_2026-09-01.docx) — the complete executed database-specific search strategies.
4. [**Supplementary Data 4**](Supplementary_Data_4_Final_Consensus_and_Statistical_Analysis_76.xlsx) — original reviewer ratings, agreement calculations, evidence log, adjudication record, and authoritative final consensus matrices.

Supplementary Tables S1–S14 document the searches, study flow and exclusions, REB rules and results, methodological concerns and wearable applicability assessment, study and configuration registers, extraction-stage exclusions, and supplementary-file checks.

Data 1 preserves extraction-stage coding separately from the final study-level profiles; final profiles and their formula-driven summaries use the adjudicated values in Data 4, including L7 = 19/76. Data 2 includes the source verification records without inventing missing reviewer initials or dates. Original independent reviewer ratings are preserved in Data 4. Historical worksheet identifiers containing `Risk` are retained for traceability; the current manuscript calls this the methodological concerns and wearable applicability assessment.

The author-developed assessment comprises seven methodological-concern domains (D1–D7) and one wearable-applicability domain (D8). It has not been externally validated and is distinct from REB.

Pre-adjudication agreement, calculated from the original reviewer ratings, was 516/606 (85.1%; pooled Cohen's κ = 0.668) for REB and 364/606 (60.1%; pooled unweighted κ = 0.361; linear-weighted κ = 0.466) for the methodological concerns and wearable applicability assessment. Each calculation excluded two of the 608 pairs because they contained an unclear rating. These figures describe the original independent ratings, not consensus agreement.

The registered protocol and documented review status are available through [OSF Registries](https://doi.org/10.17605/OSF.IO/JWYFS).


Publisher-provided full-text articles and supplementary files are not redistributed. No custom software was developed for this review.

## Citation

Elgendi M, Gurram P, P. J. S, Shokurov AV, and Menon C. *A systematic review of materials processing and reliability evidence in FDM printed wearable sensors.* Manuscript.

