# AI Ethics Assignment

In this repository is a structured, multi-part AI Ethics assignment, covering various fields including theoretical foundations, real-world case analysis, practical dataset auditing, personal reflection, and policy drafting. The materials are organized for clarity and ease of use, supporting both academic study and practical application.

## Repository Structure

- **AI_Ethics_Assignment_Prompts.md**  
  The master prompt file outlining all assignment tasks and requirements.

- **Theoretical_Understanding.md**  
  Answers to academic theory questions and explanations of core AI ethical principles (Chunk 1).

- **Case_Studies_Analysis.md**  
  In-depth analysis of two real-world AI ethics case studies, including sources of bias, solutions, and policy recommendations (Chunk 2).

- **Compas_Dataset_Audit.md**  
  Written summary, ethical implications, and mitigation strategies for the COMPAS dataset audit (Chunk 3).

- **COMPAS_Audit.ipynb**  
  Jupyter notebook with Python code for auditing the COMPAS Recidivism dataset using AI Fairness 360, pandas, and matplotlib. Includes fairness metrics and visualizations (Chunk 3).

- **Ethical_Reflection.md**  
  Personal reflection on ensuring ethical AI principles in past, current, or future projects (Chunk 4).

- **Ethical_AI_Guideline.md**  
  A 1-page, actionable policy guideline for ethical AI use in healthcare, covering consent, bias mitigation, and transparency (Chunk 5, Bonus).

## How to Use the COMPAS Audit Notebook

1. Download the COMPAS dataset from [ProPublica](https://projects.propublica.org/datastore/#compas-recidivism-risk-score-data-and-analysis) and place it in your working directory as `compas-scores-two-years.csv`.
2. Open `COMPAS_Audit.ipynb` in Jupyter Notebook or JupyterLab.
3. Follow the code cells to load, preprocess, and analyze the dataset for racial bias using AI Fairness 360 and standard fairness metrics.
4. Review the summary and ethical discussion in `Compas_Dataset_Audit.md` for interpretation and recommendations.

## Requirements
- Python 3.7+
- pandas
- matplotlib
- scikit-learn
- aif360

Install dependencies with:
```bash
pip install pandas matplotlib scikit-learn aif360
```

## License
This repository is for educational and academic use. Please cite appropriately if using in your own work. 
