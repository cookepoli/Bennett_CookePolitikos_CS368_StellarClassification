# SETI / Stellar Signal Classification Project

This project applies data-mining and machine-learning techniques to a stellar classification dataset derived from Sloan Digital Sky Survey-style astronomy data. It is linked from the portfolio card “Machine Learning Modeling, Evaluation, and Feature Engineering.”

## Project signal

This project demonstrates algorithmic feature engineering and comparative model evaluation. The strongest signal is not just that models were trained, but that preprocessing choices were tested as part of the modeling problem.

It supports the portfolio signal that I can choose representations, compare models, and evaluate whether outputs are meaningful for a noisy, domain-shaped dataset.

## What the project does

The project studies classification of astronomical objects such as stars, galaxies, and quasars. It includes preprocessing, feature subset selection, anomaly/outlier analysis, discretization experiments, and model comparison across decision trees, support vector classifiers, and random forests.

A major conclusion from the report is that a more involved preprocessing/discretization approach improved classification results across models. The final comparison showed strong performance for all models on the improved dataset, with random forest producing the best observed results in the study.

Reported final comparison highlights from the project report:

- Improved dataset results outperformed the simpler preprocessing path across decision tree, SVC, and random forest models.
- The random forest model reached approximately 96.9% accuracy and 0.994 AUC in the final comparison.
- The work emphasizes the importance of effective preprocessing and feature representation before model selection.

## Repository navigation

Primary folders:

- `Dataset/` — source and derived datasets used during preprocessing and experiments.
- `Scripts and notebooks/` — notebooks and scripts for preprocessing, discretization, model training, cross-validation, and results analysis.
- `IMGs/` — generated figures and tables.
- `References/` — papers and web references used to frame the data-mining methods.
- `SharedNotes/` — notes from project development.

Important files/notebooks:

- `Scripts and notebooks/feature_discretization.ipynb` — feature-discretization workflow.
- `Scripts and notebooks/MLanalysis.ipynb` — model-analysis workflow.
- `Scripts and notebooks/decisiontree_cross_val.ipynb` — decision-tree model validation.
- `Scripts and notebooks/svc_cross_val.ipynb` — SVC validation.
- `Scripts and notebooks/randomforst_cross_val.ipynb` — random-forest validation.
- `Scripts and notebooks/results.ipynb` — final results analysis.
- `Scripts and notebooks/RandomForestScores.csv` — stored random-forest scores.

## How to review

Recommended review path:

1. Start with the written report to understand the full data-mining question.
2. Review the preprocessing and discretization notebooks.
3. Inspect the cross-validation notebooks for model-specific evaluation.
4. Review `results.ipynb` for the final comparison across preprocessing approach and model type.
