# ENIGMA_CTQ
This repository contains all detailed supplementary result tables for the study:
“Childhood Maltreatment and Deviations from Normative Brain Structure: Results from 3,711 Individuals from the ENIGMA MDD and ENIGMA PTSD.”
Researchers can find the full results of the extended analyses, and all large-format tables needed to reproduce or further explore the findings.

Table_S4_CTQ_normative_deviations.csv:
- Numeric results of all normative‐deviation associations with CTQ scores.
- Columns include: brain region labels, regression coefficients, p and q values.

Table_S5_Fishers_comparisons.csv
- Results from Fisher’s r-to-z transformation tests comparing:
- Age cohorts (young adults vs. older adults)
- Sex differences (male vs. female)
- Reports r values, z scores, and two-tailed p values for each comparison across all morphometric measures (subcortical volume, cortical thickness, surface area).

Table_S6_CTQ_normative_deviations_dx_cov.csv
- Full output of normative-deviation × CTQ associations controlling for diagnostic status (patient vs. control).
- Mirrors Table S4 columns, with an added “Diagnosis” column and adjusted regression statistics.

Table_S7_LOO_results.xlsx
- Leave-one-out cross-validation (LOO) results demonstrating site‐wise stability:
- Each sheet corresponds to a specific brain measure (e.g., subcortical volumes, cortical thickness, surface area).
- Rows list the omitted site, original p value, re-computed p, and the range across all leave-one-out iterations.
- Allows inspection of whether excluding any single site changes significance thresholds.
