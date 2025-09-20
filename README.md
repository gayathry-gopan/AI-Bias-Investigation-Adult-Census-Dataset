# AI-Bias-Investigation-Adult-Census-Dataset
This case study explores bias detection and fairness evaluation in machine learning models using the public Adult Census Dataset from UCI (direct link
). The dataset predicts whether an individual's income exceeds $50k/year. In this scenario:

   * Individuals predicted to earn > $50k are flagged for tax audits.

   * Individuals predicted to earn ≤ $50k are pre-qualified for a social welfare program.

The original development team removed sensitive features like race and sex due to bias concerns. This study revisits the dataset and model to:

   1. Assess potential biases in predictions despite feature removal.

   2. Investigate the impact of biased predictions on social and financial decisions.

   3. Demonstrate how fairness metrics and explainable AI tools can help identify hidden biases in black-box models.

The repository includes the dataset, model implementation, and analytical notebooks demonstrating bias investigation and mitigation strategies.
