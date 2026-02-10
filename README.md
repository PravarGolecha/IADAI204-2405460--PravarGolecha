### IADAI204-2405460--PravarGolecha

# SA: Art of Story Telling 

Link to Dashboard: https://public.tableau.com/views/SAArtofStorytellingbyPravar/SAArtofStorytellingbyPravar?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

## Project Overview
This project analyses Amazon product reviews to understand how customer ratings, sentiments, and engagement influence buyer trust and product perception.  
The dashboard transforms raw review data into actionable insights that help businesses identify satisfaction drivers, common complaints, and opportunities for service improvement.

---

## Purpose & Audience

### Purpose
To support data-driven decision making by revealing how review scores, customer sentiment, and helpfulness votes affect brand credibility and purchase confidence.

### Target Audience
- E-commerce managers  
- Marketing teams  
- Product owners  
- Customer experience strategists  

The dashboard is designed to move beyond raw numbers and highlight patterns that can guide operational and promotional strategies.

---

## Data Summary

### Source
Amazon Reviews dataset containing customer ratings, review text, product identifiers, and helpfulness voting metrics.

### Key Fields Used
- Score (rating)  
- Text / Summary  
- Product Id  
- Helpfulness Numerator  
- Helpfulness Denominator  
- Time  

### Cleaning & Preparation
- Removed or handled missing rating values.  
- Converted rating scores into categorical measures.  
- Created calculated fields such as sentiment classification.  
- Created helpfulness ratio to measure review trustworthiness.  
- Converted timestamps into date formats for trend analysis.  
- Aggregated data to avoid row-level clutter and enable meaningful comparisons.

---

## Methods

Several analytical techniques were applied.

### Sentiment Classification
Reviews were grouped using rating logic:
- **4–5 → Positive**  
- **3 → Neutral**  
- **1–2 → Negative**

This allowed emotional trend evaluation.

### Distribution Analysis
Bar charts and histograms were used to understand how ratings and engagement volumes spread across the dataset.

### Correlation Analysis
Scatter plots examined the relationship between total votes and helpful votes to evaluate credibility behaviour.

### Word Frequency
Word clouds were created to identify recurring themes in customer feedback and highlight satisfaction or pain points.

---

## Key Insights
- The majority of reviews are **4 and 5 stars**, indicating generally strong customer satisfaction.  
- Positive sentiment dominates, but negative reviews reveal consistent operational issues.  
- Most reviews receive **very low engagement**, while a small portion attracts extremely high visibility.  
- There is a strong linear relationship between total votes and helpful votes, suggesting that visibility drives perceived usefulness.  
- Highly rated reviews tend to build stronger buyer confidence.  
- Engagement inequality implies only a fraction of opinions significantly influence purchasing decisions.

---

## Dashboard Features
The Tableau dashboards include:
- Interactive filtering by rating and sentiment.  
- Drill-down capability to inspect engagement behaviour.  
- Colour encoding to quickly differentiate performance levels.  
- Multiple perspectives: distribution, correlation, and trend.  
- KPI-style summaries for executive-level understanding.  
- Clean layout to guide users from **overview → cause → impact**.

---

## Limitations
During processing and analysis, several constraints were observed:
- The dataset is very large, requiring aggregation instead of individual-level exploration.  
- Sentiment classification is rating-based and does not use advanced NLP, which may oversimplify emotional nuance.  
- Word frequency analysis may include generic terms that require manual refinement.  
- Helpfulness votes reflect user interaction but may be influenced by review visibility rather than quality.  
- Product category information was limited, reducing segmentation opportunities.

---

## Conclusion
The analysis demonstrates that Amazon products in this dataset maintain high overall satisfaction levels.  
However, customer influence is concentrated in a small set of highly visible reviews.

Understanding recurring complaint themes and strengthening operational reliability can further enhance brand trust, customer loyalty, and long-term sales performance.

---

## Future Improvements
Future enhancements could include:
- Applying machine learning or NLP for more accurate sentiment detection.  
- Incorporating product categories or pricing to deepen segmentation.  
- Tracking review response times from sellers.  
- Analysing reviewer behaviour and credibility.  
- Studying how sentiment shifts after product updates.  
- Building predictive models to forecast rating changes.
