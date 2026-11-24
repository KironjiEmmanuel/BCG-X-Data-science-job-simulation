This repository contains my work on the BCG X Data Science Job Simulation (Forage), analysing customer churn for PowerCo, an SME utility provider. It covers exploratory analysis, a pre-specified hypothesis test (does the December vs. January off-peak price change predict churn?), and a churn model built to support targeted retention offers.

Key results: the pricing hypothesis was not supported; margins, consumption and tenure were the stronger signals. A tuned Random Forest (stratified splits for the ~9.7% churn rate, RandomizedSearchCV, benchmarked against a dummy model and an untuned baseline) flags ~70% of churners while contacting ~38% fewer customers than blanket outreach, at ~16% precision.
The Notebooks in the repo are divided into 2:
- My Notebooks-My working and reasoning for Exploratory Data Analysis, Feature Engineering and modelling
- Guide notebooks- Norebooks provided by the team at BCG X as guides along the project
Note on data: each simulation task used its own prepared dataset. EDA and the hypothesis test use my own engineered features, while the modelling stage uses the dataset provided by BCG X.