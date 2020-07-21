## Wine quality classification

Data Source: Wine (https://www.kaggle.com/uciml/red-wine-quality-cortez-et-al-2009)
Task: to predict "quality" (multiple classificaton)

Metric that was used:
Accuracy = (TRUE_POSITIVE + TRUE_NEGATIVE) / (TRUE_POSITIVE + FALSE_POSITIVE + TRUE_NEGATIVE + FALSE_NEGATIVE

Baseline: SVC - 63.5% accuracy

I tried different models:
- Random Forest: 67.5%
- GradientBoosting: 65%
- LightGBM: 63%
