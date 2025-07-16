# CHUNK 2: Case Study Analysis

## Case 1: Amazon’s Biased Hiring Tool

### Source of Bias
Amazon’s AI-powered hiring tool was designed to automate the screening of job applicants by learning from historical hiring data. However, the system developed a bias against female candidates, particularly for technical roles. The primary source of this bias was the training data: Amazon’s historical hiring records reflected a male-dominated tech workforce, leading the model to associate male-related terms and experiences with higher suitability. Additionally, the algorithm penalized resumes containing words like “women’s” (as in “women’s chess club captain”) and favored those with language or experience more common among men. This bias was further exacerbated by flawed feature selection, where the model picked up on proxies for gender, such as certain schools or extracurricular activities, reinforcing existing disparities.

### Three Concrete Solutions
1. **Bias-Aware Data Curation:** Proactively audit and balance the training dataset to ensure equal representation of genders and other protected groups. Remove or anonymize features that serve as proxies for gender, such as names, pronouns, or gendered organizations, to prevent the model from learning discriminatory patterns.
2. **Algorithmic Fairness Constraints:** Integrate fairness constraints or regularization techniques during model training to penalize disparate impact. For example, use techniques like reweighing or adversarial debiasing to ensure that the model’s predictions are not correlated with gender or other sensitive attributes.
3. **Human-in-the-Loop Oversight:** Implement a hybrid approach where AI recommendations are reviewed by diverse human recruiters, especially for edge cases or high-stakes decisions. Regularly retrain and audit the model with updated data and feedback to catch and correct emerging biases.

### Three Fairness Metrics for Evaluation
1. **Selection Rate Parity (Demographic Parity):** Measures whether candidates from different groups (e.g., men and women) are selected at similar rates. A large disparity indicates potential bias.
2. **Equal Opportunity Difference:** Assesses whether qualified candidates from all groups have equal chances of being selected. This metric focuses on true positive rates across groups.
3. **Disparate Impact Ratio:** Compares the selection rate of the protected group to that of the majority group. A ratio below 0.8 (the “four-fifths rule”) signals possible discrimination.

### Frameworks Cited
- EU Trustworthy AI Guidelines (Fairness, Human Agency, and Oversight)
- AI Fairness 360 (IBM)

---

## Case 2: Facial Recognition in Policing

### Ethical Risks
Facial recognition technology (FRT) in policing introduces significant ethical risks, particularly regarding racial misidentification, wrongful arrests, and privacy erosion. Studies have shown that FRT systems often have higher error rates for people of color and women, leading to disproportionate misidentification and potential wrongful detainment. These risks are compounded by the lack of transparency in how FRT algorithms are trained and evaluated, making it difficult for affected individuals to challenge erroneous outcomes. The deployment of FRT in public spaces also raises profound privacy concerns, as it enables mass surveillance without consent, potentially chilling free expression and assembly. Furthermore, the use of FRT by law enforcement can exacerbate existing societal biases, undermining public trust and social cohesion.

### Three Deployment Policies to Reduce Harm
1. **Independent Oversight Boards:** Establish independent, multidisciplinary oversight committees to review and approve FRT deployments. These boards should include ethicists, technologists, legal experts, and community representatives to ensure diverse perspectives and accountability.
2. **Mandatory Transparency Reports:** Require law enforcement agencies to publish regular transparency reports detailing FRT usage, including the number of searches conducted, demographic breakdowns of matches, error rates, and instances of misidentification. This fosters public scrutiny and informed debate.
3. **Strict Use Limitations and Consent Protocols:** Limit FRT deployment to clearly defined, high-necessity scenarios (e.g., serious crimes) and require explicit consent or judicial authorization where possible. Implement robust opt-out mechanisms and ensure individuals are informed when FRT is in use.

### Frameworks Cited
- EU Trustworthy AI Guidelines (Transparency, Accountability, Privacy, and Fairness)
- GDPR (Data Protection and Consent)
