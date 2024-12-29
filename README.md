# A/B Testing Analysis: Cookie Cats Game

## Project Overview

This project involves analyzing A/B testing results from a mobile game. The test focuses on the placement of a gate (level 30 vs. level 40) to determine its impact on user retention. The goal is to identify which configuration maximizes short-term (1-day) and long-term (7-day) retention rates. This project was conducted to practice A/B testing analysis and retention optimization in gaming. The findings can guide decision-making for in-game feature placement and engagement strategies.


## Analysis Steps

1. **Data Cleaning and Exploration**:

   - Checked for missing values and inconsistencies.
   - Explored basic statistics and group distributions.

2. **Exploratory Data Analysis (EDA)**:

   - Calculated retention rates for each group.
   - Visualized 1-day and 7-day retention rates.

3. **Statistical Testing**:

   - Conducted t-tests to compare retention rates between groups.
   - Performed chi-square tests for categorical data.

4. **Visualization and Insights**:

   - Plotted retention rates and game-round distributions.
   - Highlighted significant differences between groups.

## Key Findings

### 7-Day Retention:

- **Significant Difference**: One version's 7-day retention rate is significantly higher (p-value: 0.0016).
- **Implication**: The gate placement affects long-term user engagement.

### 1-Day Retention:

- **No Significant Difference**: The 1-day retention rate showed no statistically significant difference (p-value: 0.0755).
- **Implication**: Gate placement does not strongly influence short-term engagement.

### Game Rounds:

- The number of game rounds played is similar across both groups, suggesting gate placement does not impact this metric significantly.

## Recommendations

- **Long-Term Engagement**: Focus on the version with higher 7-day retention.
- **Short-Term Retention**: Explore other strategies, such as tutorial enhancements or early rewards, to boost initial engagement.
- **Further Analysis**: Investigate other factors influencing retention, such as player demographics or session duration.

## Visualizations

- **Retention Rates**: Bar plots showing 1-day and 7-day retention rates by version.
- **Game Rounds Distribution**: Boxplots illustrating the distribution of game rounds by version.

## Next Steps

- Share findings with stakeholders to inform decisions on gate placement.
- Use this analysis to optimize future A/B tests by focusing on key metrics like retention and player behavior.

## Technologies 
- Python, Pandas, Matplotlib, Seaborn
