## Week 6 - HealthConnect Model Improvement, Error Analysis & Validation (Data Science Track)

Built forward from the Week 5 baseline rather than repeating it.

- Conducted error analysis on the Week 5 Logistic Regression baseline - identified a specific blind spot: under-detection of no-shows among patients with short booking lead times and little prior history
- Resolved the prior_no_show_rate / previous_no_shows multicollinearity flagged in Week 5 - model-specific answer (drop for linear, keep for tree-based)
- Trained and compared Random Forest and Gradient Boosting against the baseline; selected Random Forest for its Recall improvement (0.679 → 0.714)
- Completed a cross-track integration check with Data Analytics - flagged a genuine discrepancy between an earlier exploratory finding and this week's model evidence

📄 Notebook: `health_connect/week6/HealthConnect_Week6_DataScience_ModelImprovement.ipynb`
📄 Summary: `health_connect/week6/HealthConnect_Week6_Project_Summary.docx`
📄 Integration evidence: `health_connect/week6/HealthConnect_Week6_DataScience_Integration_Questionnaire.docx`
