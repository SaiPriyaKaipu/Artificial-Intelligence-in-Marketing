# Service Quality Analysis for Holiday Inn Hotels (Ontario)

## Overview
This project leverages Natural Language Processing (NLP) and sentiment analysis techniques to evaluate customer reviews of Holiday Inn hotels across Ontario. By collecting and analyzing review data, the goal is to identify service areas that need improvement and provide actionable insights to enhance guest satisfaction and loyalty.

## Objectives
- Collect and analyze Google reviews for selected hotel locations.
- Perform sentiment analysis to measure customer satisfaction levels.
- Classify reviews by service areas (e.g., housekeeping, front desk, dining).
- Provide data-driven recommendations for operational improvements.

## Tools & Technologies
- **Python** (Jupyter Notebook)
- **Google Maps Platform API** – For review data scraping.
- **Google Cloud Natural Language API** – For sentiment scoring.
- **Pandas, Matplotlib, Seaborn** – For data manipulation and visualization.
- **Power BI** – For dashboard creation and reporting.

## Project Workflow
1. **Review Collection**: Scraped customer reviews from 20 Holiday Inn locations in Ontario.
2. **Sentiment Analysis**: Extracted sentiment scores and magnitudes using Google NLP API.
3. **Review Classification**: Mapped reviews to service categories using text-matching logic.
4. **Data Visualization**: Generated insights via histograms, bar charts, and Power BI dashboards.
5. **Evaluation & Reporting**: Presented actionable insights and recommendations based on the analysis.

## Evaluation Summary

### Sentiment Model
- **Average Sentiment Score**: Calculated for overall service impression.
- **Sentiment Magnitude**: Highlighted the intensity of expressed opinions.

### Classification Accuracy
- Reviews were successfully classified into predefined service areas.
- Manual validation confirmed reliable categorization.

### Visual Outputs
- Histograms for sentiment distribution by service area.
- Bar charts for comparing average ratings across locations.
- Power BI report to support stakeholder-ready insights.

## Key Insights
- **Front Desk & Housekeeping** had the highest frequency of negative reviews.
- **Same-day services and check-in experience** were common customer pain points.
- Some locations consistently outperformed others in guest sentiment.
- **Technology-related reviews** generally showed more positive tone and engagement.

## Recommendations
- Prioritize training and performance tracking in front desk and housekeeping teams.
- Establish SOPs for same-day service workflows to reduce dissatisfaction.
- Use sentiment classification to create a real-time feedback loop for service teams.
- Conduct periodic review audits using automated NLP-based dashboards.

## Outcome
The project helped in identifying service gaps and generated practical suggestions to improve hotel performance and guest satisfaction. It showcases the use of AI, sentiment analysis, and visualization in solving real-world business problems.
