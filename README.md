# DA/ML Journey

Started: June 24, 2026

Currently learning: Python, Pandas, Data Analysis

## Log
- Day 1: Set up repo, started Titanic EDA with Pandas
- Day 2 (June 25, 2026): Filtering by Sex and Pclass, 
  groupby — women survived at 74% vs men at 18%, 
  1st class at 63% vs 3rd class at 24%.
- Day 3 (June 26, 2026): Found missing values in Age(177), 
  Cabin(687), Embarked(2). Dropped Cabin, filled Age with 
  mean, Embarked with mode. Clean dataset achieved.
- Day 3 extended: Sorting with nlargest/nsmallest, 
  correlation matrix, groupby on multiple columns. 
  Found survivors paid 2x fare and were slightly younger.
- Day 4: Visualisation with Matplotlib — bar charts and 
  histograms. Age is normally distributed, Fare is right 
  skewed. Cherbourg passengers paid highest average fare.
- Day 5: Scatter plots, coloured scatter by survival, 
  pie chart. Completed full Titanic EDA. Added notebook 
  README with key findings. Higher fare = better survival 
  visible visually.
- Day 6: Seaborn — boxplots with outliers and hue, regplot with regression line
  and confidence interval. Tips dataset. Non-smokers show 
  stronger bill-tip relationship than smokers.
- Day 7: Correlation heatmap and pairplot. Titanic — 
  Pclass most correlated with Survived (-0.34). 
  Tips — total_bill and tip strongest pair (0.68).
- Day 8: First SQL queries using pandasql. SELECT, WHERE, 
  GROUP BY, ORDER BY, AVG, COUNT. Verified results matched 
  earlier Pandas groupby calculations.
- DAY 9: Made two data frames passenger and tickets.
  Applied INNER JOIN and LEFT JOIN on them.
- Day 9 Continued: HAVING vs WHERE clause, multi-column 
  GROUP BY. Found passengers with no tickets 
  using LEFT JOIN + IS NULL pattern.
- Day 10: SQL subqueries. Started World Happiness Report 
  project — 153 countries, 12 columns. Top 5: Scandinavian 
  countries. Bottom 5: African/Middle Eastern conflict zones. 
  North America highest avg happiness by region.
- Day 11: Happiness project charts — top 10 countries bar chart,
  correlation heatmap (Economy strongest predictor), Economy vs 
  Happiness regplot (strong relationship), boxplot by region. 
  North America least variation, Western Europe consistently high.
- Day 12: Completed Happiness project. Key finding: Generosity 
  weakest predictor (0.16), Economy strongest (0.81). Central 
  African Republic scores 0 on Economy and Family. Published 
  as standalone repo: world-happiness-eda.
- Day 13: Statistics fundamentals — mean vs median (use median 
  for skewed data), standard deviation, normal distribution 
  (68-95-99.7 rule), quantiles, IQR outlier detection. 
  No outliers found in Happiness Score or Economy columns.
- Day 14: Revision of all concepts learnt, nothing new added. 
- Day 15: Started Zomato EDA (51,717 restaurants, 17 columns).
  Cleaned rate column (removed /5, handled NEW values) and 
  cost column (removed commas). Used pd.to_numeric with 
  errors='coerce' for safe conversion.
- Day 16: Zomato EDA analysis — table booking strongly affects 
  rating (3.6 vs 4.1), online ordering minimal impact. Bars & 
  Pubs most expensive (₹850 avg). Price doesn't guarantee 
  quality — top rated cuisines are multi-cuisine combos 
  (data quality issue noted).
- Day 17: Published Zomato EDA as standalone repo 
  (zomato-bangalore-eda). Fixed git tracking issues. 
  3 public portfolio projects now live on GitHub.