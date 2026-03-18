# Does Elite Offense or Defense Predict NCAA Tournament Success?
### ECON 570 — Fundamentals of Data Analytics for Economists


---

## Overview
This project analyzes which offensive and defensive factors best predict 
reaching the Final Four among power conference teams from 2015–2025. 
Using logistic regression, we find that adjusted offensive efficiency 
is the single strongest predictor, though elite defense is equally 
necessary for deep tournament runs.

## Data Sources
- **Scraped data:** School-level stats for 10 conferences (2015–2025) 
  scraped from sports-reference.com using BeautifulSoup
- **Kaggle dataset:** College basketball team stats and tournament outcomes 
  (2013–2025), sourced from [kaggle.com](https://www.kaggle.com/datasets/andrewsundberg/college-basketball-dataset)


## How to Run
1. Clone this repository
2. Install dependencies: `pip install pandas numpy matplotlib seaborn scikit-learn beautifulsoup4`
3. Open `final_project.ipynb` and run all cells

## Key Findings
- Adjusted offensive efficiency is the strongest single predictor of Final Four appearances
- Final Four teams shoot ~4% better in effective FG% than teams that don't make it
- Strength of schedule is the second strongest predictor, suggesting power conference 
  teams are genuinely better prepared for tournament play
- Turnover rate is the most damaging negative factor
