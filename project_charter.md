# Project Charter

## Project Title
**Data-Driven Media Optimization for E3 Media Crafters Pvt Ltd**

## Project Sponsor
E3 Media Crafters Pvt Ltd

## Project Manager
Ajit Tripathi

## Project Start Date
15- May- 2025

## Project End Date
8 weeks from start date

## Background
E3 Media Crafters Pvt Ltd seeks to optimize its media campaigns by leveraging data analytics and machine learning. This project aims to analyze customer feedback, forecast campaign performance, and classify visual content using the Yelp Open Dataset. These insights will enable E3 to design more engaging and effective marketing campaigns.

## Objectives
- **Sentiment Analysis (NLP):** Analyze customer reviews to extract sentiment and understand audience reactions.
- **Time Series Analysis (TSA):** Predict campaign performance trends using temporal review data.
- **Computer Vision (CV):** Classify business-related photos to enhance campaign visuals.
- **Visualization & Deployment:** Create interactive dashboards and a user-friendly app to empower marketing decisions.

## Scope
- Utilize the Yelp Open Dataset focused on restaurants in Las Vegas (2018-2023).
- Data preprocessing, cleaning, and feature engineering for NLP, TSA, and CV tasks.
- Develop and train models using deep learning techniques (BERT, LSTM, CNN).
- Deploy models into dashboards (Power BI) and an interactive app (Streamlit).
- Deliver documentation including data dictionary, EDA reports, model evaluations, and final presentations.

## Deliverables
- Cleaned and processed datasets for sentiment, time series, and image classification.
- Trained and evaluated NLP, TSA, and CV models.
- Power BI dashboards summarizing key insights.
- Interactive Streamlit app for campaign analysis.
- Project documentation: data dictionary, reports, evaluation metrics, and final presentation.

## Timeline (6 weeks)
| Week | Major Activities                      |
|-------|------------------------------------|
| 1     | Business understanding, project charter, dataset exploration |
| 2     | Data preprocessing for NLP, TSA, CV |
| 3     | Model development: NLP and TSA      |
| 4     | Model development: CV, initial evaluations |
| 5     | Model tuning, integration, dashboard creation |
| 6     | Final deployment, documentation, and presentation |

## Resources
- Python (Pandas, TensorFlow, Keras, OpenCV)
- Power BI Desktop
- Streamlit framework
- Yelp Open Dataset (subset)
- Computing resources with GPU support (if available)

## Risks and Mitigations
| Risk                                   | Mitigation Strategy                      |
|---------------------------------------|------------------------------------------|
| Data quality issues or missing data   | Perform thorough EDA and preprocessing   |
| Model training time or computational limits | Use subset of data, optimize code, and leverage cloud/GPU if possible |
| Class imbalance in sentiment labels   | Apply resampling techniques or class weighting |
| Integration and deployment challenges | Plan incremental testing and version control |

## Success Criteria
- Models achieve target accuracy (e.g., >80% sentiment classification accuracy).
- Time series forecasts show reliable performance metrics (e.g., low RMSE).
- Image classifier correctly identifies business attributes with acceptable precision.
- Interactive dashboard and app demonstrate usability and actionable insights.
- Project completed within 6-week timeframe.
