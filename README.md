# AI-Bias-Investigation-Adult-Census-Dataset
This case study explores bias detection and fairness evaluation in machine learning models using the 1994 Adult Census Dataset. The dataset was originally intended to predict whether an individual's income exceeds $50k/year. In this scenario:

 *  Individuals predicted to earn > $50k are flagged for tax audits.

Individuals predicted to earn ≤ $50k are pre-qualified for a social welfare program.

The original development team removed sensitive features like race and sex due to concerns about bias before model training. This study revisits the dataset and the model to:

Assess potential biases in predictions despite feature removal.

Investigate the implications of biased predictions on social and financial decisions.

Demonstrate how fairness metrics and explainable AI tools can help identify hidden biases in black-box models.

The repository includes the dataset, model implementation, and analytical notebooks demonstrating bias investigation and mitigation strategies.
