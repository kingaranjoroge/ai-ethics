# CHUNK 1: Theoretical Understanding

## Q1: Define algorithmic bias and provide two real-world examples of how it manifests in AI systems.

Algorithmic bias refers to systematic and repeatable errors in a computer system that create unfair outcomes, such as privileging one group over others. This bias often arises from biased training data, flawed model assumptions, or the way algorithms are designed and deployed. For example, if an AI system is trained on historical data that reflects existing societal prejudices, it may perpetuate or even amplify those biases. One real-world example is the COMPAS recidivism algorithm used in the US criminal justice system, which was found to disproportionately label Black defendants as high risk compared to white defendants, even when controlling for actual reoffending rates. Another example is facial recognition technology, which has been shown to have higher error rates for women and people of color due to underrepresentation in training datasets. These biases can lead to discriminatory outcomes, highlighting the need for careful dataset curation and ongoing monitoring of AI systems.

---

## Q2: Explain the difference between transparency and explainability in AI. Why are both critical for responsible design?

Transparency in AI refers to the openness about how an AI system is developed, trained, and operates, including access to information about data sources, algorithms, and decision-making processes. Explainability, on the other hand, is the degree to which the internal mechanics of an AI system can be understood and interpreted by humans, especially regarding how specific decisions are made. While transparency provides stakeholders with insight into the system’s construction and intent, explainability ensures that users and regulators can comprehend and challenge individual outcomes. Both are critical for responsible AI design because they foster trust, enable accountability, and support compliance with legal frameworks such as the EU’s General Data Protection Regulation (GDPR). Without transparency, it is difficult to audit or scrutinize AI systems; without explainability, affected individuals cannot understand or contest decisions that impact them.

---

## Q3: How does the General Data Protection Regulation (GDPR) influence AI development in the EU? Focus on data rights and model accountability.

The General Data Protection Regulation (GDPR) significantly shapes AI development in the EU by establishing strict requirements for data protection, user consent, and accountability. Under GDPR, individuals have enhanced data rights, including the right to access, rectify, and erase their personal data, as well as the right to data portability. Importantly, Article 22 grants individuals the right not to be subject to solely automated decisions that have legal or significant effects, unless certain safeguards are in place. This compels AI developers to implement mechanisms for human oversight and to provide meaningful information about the logic, significance, and consequences of automated processing. GDPR also enforces accountability by requiring organizations to conduct Data Protection Impact Assessments (DPIAs) for high-risk AI applications and to document data processing activities. As a result, AI systems in the EU must be designed with privacy by design and by default, ensuring that data rights and model accountability are integral to their operation.

---

## Ethical Principles Matching

**Justice:**  
Justice in AI ethics refers to the fair and equitable treatment of all individuals and groups affected by AI systems. It demands that AI technologies do not perpetuate or exacerbate existing social inequalities, and that benefits and burdens are distributed fairly. Justice requires careful consideration of how data is collected, how models are trained, and how outcomes are evaluated to prevent discrimination and ensure inclusivity.

**Non-maleficence:**  
Non-maleficence is the principle of “do no harm.” In the context of AI, it means that systems should be designed and deployed in ways that avoid causing harm to individuals or society. This includes preventing physical, psychological, or social harm, as well as safeguarding against unintended negative consequences such as privacy breaches, security vulnerabilities, or the reinforcement of harmful stereotypes.

**Autonomy:**  
Autonomy emphasizes the importance of respecting individuals’ rights to make informed decisions about their own lives, including how their data is used by AI systems. AI should empower users, not manipulate or coerce them, and should provide mechanisms for meaningful consent, control, and the ability to opt out of automated processes.

**Sustainability:**  
Sustainability in AI ethics involves ensuring that the development and deployment of AI systems are environmentally, economically, and socially sustainable over the long term. This principle calls for minimizing resource consumption, reducing environmental impact, and considering the broader societal implications of AI, such as its effects on employment, social cohesion, and future generations.
