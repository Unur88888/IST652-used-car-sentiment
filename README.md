# IST652-used-car-sentiment

# IST652 – Used Car Listings & Consumer Sentiment Analysis

This project analyzes EPA fuel economy data and NHTSA recall complaint text for Toyota and Acura vehicles (2012–2015). The goal was to determine whether consumer sentiment correlates with objective vehicle specifications such as MPG, engine size, and cylinder count.

## Files in this Repository
- `Final_Project_Used_Cars_Colab.ipynb` — full analysis notebook
- `agg_brand_model_year.csv` — aggregated dataset used for correlation analysis
- `base_joined.csv` — merged EPA + NHTSA dataset

## Tools & Technologies
Python, pandas, NLTK (VADER), requests, matplotlib, rapidfuzz

## Key Findings
- MPG metrics were highly internally consistent (correlation > 0.97)
- Sentiment showed weak correlation with MPG (compound vs combined MPG ≈ 0.0451)
- Complaint volume had a moderate negative correlation with MPG (≈ -0.50)

## Author
Unur Gantulga  
MS in Applied Data Science, Syracuse University
