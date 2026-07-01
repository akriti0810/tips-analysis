# Tips - Analysis
An exploratory analysis of a restaurant tipping dataset, investigating what factors — such as party size and day of the week — influence how much customers tip.

## What I did
- Imported and explored the dataset
- Investigated whether gender is associated with bill amount
- Controlled for party size by calculating bill-per-person, to test if it explained the gap
- Created a tip_pct metric and visualized it by day using a boxplot
- Investigated outliers to check if they represented a real pattern or a data artifact

## Findings
- The apparent gender gap in tipping was partly explained by party size — men's parties tended to be slightly larger. After adjusting for party size (bill per person), the gap shrank significantly but didn't disappear entirely.
- Two extreme outliers in tip percentage weren't cases of unusually generous tipping — they were normal-sized tips ($4–5) that looked extreme only because the bills themselves were very small.

## How to run
- Open tips_analysis.ipynb in this repo (or click it directly on GitHub — it renders in-browser).
- Open in Google Colab, or download and upload to Colab.
- Run each cell in order to reproduce the analysis.
