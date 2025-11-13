# Cancer-Risk-Factors-EDA-ML
A compact and standardized dataset examining how lifestyle, environmental, and genetic factors influence five common cancer types.
Contains 2,000 individual records × 21 features, fully numerical and ready for EDA, dashboarding, and multiclass ML tasks.

Why This Dataset?

Explore risk distributions and correlations across lifestyle factors
Build visual dashboards for population-level cancer risk
Train multiclass models on Cancer_Type with balanced evaluation (macro-F1, accuracy)
Practice class imbalance handling and interpretability

Targets

Primary target:
Cancer_Type ∈ {Lung, Breast, Colon, Prostate, Skin}
→ Ideal for multiclass classification (use macro-F1, accuracy, confusion matrix).

Optional target:

Risk_Level ∈ {Low, Medium, High}
→ Derived from Overall_Risk_Score thresholds:
Low < 0.35 | 0.35–0.65 = Medium | > 0.65 = High
