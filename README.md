This is the Python scripts used for application of normative modeling to estimate cross-sectional brain structural deviations and longitudinal within-subject changes.

1. Baseline_NM_application: apply pretrained normative model to new data and visualize subject data and normative centile curves.
2. Baseline_t-test_visualization: identify structural group differences between patients and HCs (based on both raw measures and model-derived Z-scores) and visualize the results.
3. Baseline_SVM: SVM classification of patients and HCs (based on both raw measures and model-derived Z-scores)
4. Longitudinal_NM_application: apply pretrained normative model to longitudinal data and conduct wilcoxon signed-rank tests on longitudinal modeling output (Zdiff-scores)
5. Longitudinal_PCA_correlation: conduct principal component analysis on Zdiff-scores and investigate correlations between ten components and changes in symptoms (PANSS scores)
