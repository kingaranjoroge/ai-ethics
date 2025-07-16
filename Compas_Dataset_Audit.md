# CHUNK 3: COMPAS Dataset Audit

## Summary of Findings

The audit of the COMPAS Recidivism dataset using AI Fairness 360 and standard fairness metrics revealed significant racial disparities in risk prediction outcomes. Analysis showed that Black defendants were more likely to be classified as high risk compared to white defendants, even when controlling for actual recidivism rates. The disparate impact ratio was below the commonly accepted threshold of 0.8, indicating potential discrimination. Equal opportunity difference analysis revealed that true positive rates (correctly predicting recidivism) were higher for white defendants, while false positive rates (incorrectly labeling as high risk) were disproportionately higher for Black defendants. These findings align with previous studies and highlight the persistence of algorithmic bias in criminal justice applications.

## Ethical Implications

The presence of racial bias in the COMPAS risk assessment tool raises serious ethical concerns. Such bias can lead to unjust outcomes, including harsher sentencing, denial of parole, and erosion of trust in the justice system for affected communities. The use of biased algorithms in high-stakes domains like criminal justice undermines the principles of fairness, justice, and non-maleficence outlined in the EU AI Ethics Guidelines. It also poses challenges for compliance with legal frameworks such as the GDPR, which mandates transparency, accountability, and the right to contest automated decisions.

## Suggested Mitigation Steps

To address these issues, several mitigation strategies are recommended:
- **Reweighing and Preprocessing:** Apply techniques such as reweighing or disparate impact remover to balance the dataset and reduce bias before model training.
- **Algorithmic Auditing:** Regularly audit models using fairness metrics and update them with new data to detect and correct emerging biases.
- **Human Oversight:** Incorporate human review for high-risk decisions and provide clear explanations for risk scores to affected individuals.
- **Transparency and Documentation:** Maintain detailed documentation of data sources, model design, and evaluation procedures to support accountability and external review.

For detailed code, analysis, and visualizations, please refer to the accompanying Jupyter notebook: `COMPAS_Audit.ipynb`.
