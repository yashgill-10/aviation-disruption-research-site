# Aviation Disruption Prediction — Research Website

Interactive research report for the ES 335 Machine Learning course project at IIT Gandhinagar.

## About

This website presents retrospective exploratory research comparing three approaches for predicting BTS departure delays:

- **Flight/Weather** — SGDClassifier with historical and weather features
- **Airport/Network** — RandomForestClassifier with airport state features  
- **M3 Stack** — Logistic regression meta-learner combining both component models

## Important Disclaimer

All results are **retrospective and exploratory**. This website displays stored evaluation results only and does not generate live predictions. No deployment readiness or operational claims are made.

## Features

- Interactive period selector (October–December vs November–December 2024)
- Horizon selector (T−2h vs T−30m prediction windows)
- Model comparison tabs
- Stored metrics: AP, ROC-AUC, Precision, Recall, F1, Balanced Accuracy, Brier score
- Clear documentation of limitations and provenance gaps

## Data Sources

- U.S. Bureau of Transportation Statistics (BTS) TranStats
- NOAA/NCEI GHCNh historical METAR observations
- FAA aviation and airport operational data

## Project Team

- **Yash Gill** — Flight/Weather workstream
- **Omruthik Nakkalapally** — Airport/Network workstream
- **Joint** — Common evaluation protocol and M3 review

## License

This research is conducted as part of the ES 335 Machine Learning course at IIT Gandhinagar. Results are provided for educational and research purposes.

## Contact

For questions about this research, please contact the project maintainers through the main repository.
