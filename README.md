

Name: Zita Lo

Competition Number: 235642

Date: December 11, 2025

1_ Inspection Data - Prepare data and generate risk score_Zita Lo.ipynb
Prepare an inspection dataset ready including engineer features required to evaluate and improve the current risk-scoring method.
- Input File: inspections_dataset\\inspections_dataset.csv
- Output Files: 
----- Inspections Profiling Report1.html: Preliminary statistical profile of the full dataset..

----- phone_area_code_to_AREA_mapping.csv: Generated mapping between phone area codes and geographic AREA values.

----- correlation_heatmap.png: Correlation heatmap used to assess feature relationships, including evaluation of the GRADE field (50%+ missing).

----- df_establishment_inspections.csv: Cleaned inspection-level dataset with all engineered features. Includes: current risk score calculation.

----- unique_establishment_details.csv: Establishment-level dataset summarizing attributes for each unique location.

----- df_violation_keywords_severity.csv: Same as df_establishment_inspections.csv, with additional keyword-based violation severity features.

----- inspection_summary_by_establishment.csv: Aggregated establishment-level inspection summary.

2_Evaluate Current Risk Scoring Algorithm_Zita Lo.ipynb
Evaluate existing risk scoring algorithm.
- Input File: inspection_summary_by_establishment.csv
- Output Files: Distribution of Current Risk Score.png

3_Propose_Improvements_Zita Lo.ipynb
Propose improvements.
- Input File: inspection_summary_by_establishment.csv
- Output Files: 

----- inspection_summary_propose_score_by_establishment.csv: Same as inspection_summary_by_establishment.csv with additional proposed risk score

----- Current and Proposed Risk Score Distribution.png

----- Correlation Matrix Current vs Proposed Risk Scores.png

----- roc_auc_comparison.png

