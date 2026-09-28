# AI User Retention & Mood Analyzer

AI-User-Retention-Mood-Analyzer is an AI-based project that combines **user retention prediction** with **mood journal analysis**. The system analyzes app feature usage and engagement patterns to predict whether a user is likely to remain active or become at risk of churn.

The project also includes a **mood journal reader** that analyzes journal entries, identifies sentiment, detects noticeable negative sentiment shifts over time, and applies safety guardrails to avoid diagnosis, harmful recommendations, or unsupported assumptions.

### Key Features

* Predicts user retention using app usage and engagement data.
* Uses a Random Forest machine learning model for retention prediction.
* Analyzes journal entries for positive, neutral, and negative sentiment.
* Compares previous and current journal sentiment to identify negative shifts.
* Includes basic safety guardrails for potentially concerning journal content.
* Provides interactive interfaces for both retention prediction and mood analysis.
* Designed to protect sensitive API credentials using environment/secret storage.

### Technologies Used

* Python
* Pandas
* Scikit-learn
* Random Forest
* TextBlob
* OpenAI API / LLM integration
* Google Colab
* IPyWidgets

### Project Workflow

**App Usage Data → Feature Extraction → ML Model → Retention Prediction**

**Journal Entries → Sentiment Analysis → Mood Trend Comparison → Safety Guardrails → Analysis**

### Disclaimer

This project is intended for educational and research purposes. The mood analysis feature is not a medical or psychological diagnostic system and should not be used as a substitute for professional support.

