# A/B Testing & Regression Analysis Project

## Project Overview

This project aims to analyze the effectiveness of two advertising platforms — **Facebook Ads** and **AdWords** — by comparing their performance in terms of clicks, conversions, and cost-effectiveness. As a marketing agency, our goal is to maximize ROI for our clients by identifying the best platform to allocate advertising resources.

---

## Business Problem

We conducted two ad campaigns during 2019, one on Facebook and the other on AdWords. The key question is:  
**Which platform yields better results in terms of conversions, clicks, and overall cost-effectiveness?**

---

## Data Description

The dataset includes daily campaign metrics for the entire year 2019, covering both Facebook and AdWords campaigns. Each row represents one day and contains features such as:

- Date (from Jan 1, 2019, to Dec 31, 2019)
- Ad Views
- Ad Clicks
- Ad Conversions
- Cost per Ad
- Click-Through Rate (CTR)
- Conversion Rate
- Cost per Click (CPC)

---

## Analysis Overview

- **Exploratory Data Analysis:** Examined distribution of clicks and conversions, identifying Facebook as having more frequent higher conversion days.
- **Correlation Analysis:** Strong positive correlation (0.87) between Facebook ad clicks and sales; moderate correlation (0.45) for AdWords.
- **Hypothesis Testing:** Tested if Facebook ads generate more conversions than AdWords. Results strongly support Facebook’s superiority in conversions.
- **Regression Analysis:** Built a linear regression model to predict Facebook conversions based on clicks with an R² score of 76.35%.
- **Temporal Trends:** Identified weekdays and months with higher conversions and analyzed Cost Per Conversion (CPC) fluctuations.
- **Long-term Relationship:** Found a stable equilibrium between advertising spend and conversion rates.

---

## Project Structure
├── AB Testing (Marketing Campaigns).ipynb # Jupyter notebook with full analysis
├── marketing_campaign.csv # Dataset used for analysis
├── README.md # Project overview and instructions

---

## Installation and Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/deepaklokh/ab-test-and-regression-project.git
   cd ab-test-and-regression-project

   
2. Ensure you have Python 3.x installed.

3. Install required libraries:
         pip install pandas numpy matplotlib seaborn scipy scikit-learn
4. Open the Jupyter notebook and run the analysis:
         jupyter notebook "AB Testing (Marketing Campaigns).ipynb"


Key Insights and Results
•Facebook advertising drives significantly higher conversions than AdWords.

•  Conversion rates on Facebook show stronger correlation with clicks and sales.

•  Cost per conversion varies monthly; May and November offer more cost-effective advertising.

•  Mondays and Tuesdays consistently show higher conversions, highlighting optimal engagement days.

•  Linear regression model helps predict conversions based on clicks, aiding in budgeting and campaign planning.

•  Evidence supports reallocating budget towards Facebook for better ROI.

Contact
Created by Deepak Lokhande
GitHub: https://github.com/deepaklokh
Email: deepak50384297@gmail.com
