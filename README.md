# community-health-project-in-kenya
# Public Health Analysis: Malaria & Cholera Trends in Kenya (2010-2025)

## Project Overview
This project analyzes the historical trends of Malaria and Cholera in Kenya. By integrating two separate datasets, I performed exploratory data analysis (EDA) and built a predictive model to forecast disease incidence.

## Key Features
- **Data Integration:** Merged temporal datasets using an outer-join strategy.
- **Feature Engineering:** Calculated Case Fatality Rates (CFR) for Cholera outbreaks.
- **Statistical Analysis:** Generated a correlation heatmap to identify relationships between disease metrics.
- **Machine Learning:** Developed a Linear Regression model to forecast Malaria rates with an R-squared score of [Insert your R2 score here].

## Visualizations
![Correlation Heatmap](outputs/correlation_heatmap.png)
![Malaria Forecast](outputs/malaria_forecast.png)

## How to Run
1. Clone the repo: `git clone https://github.com/yourusername/Kenya-Health-Analysis.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the analysis: `python src/main.py`
