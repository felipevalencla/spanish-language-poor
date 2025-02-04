# Jacques Audiard's Comment on Spanish as a "Language of the Poor"

## Author: Felipe Valencia-Clavijo

### Abstract
French director Jacques Audiard, while promoting his movie Emilia Perez, made the controversial statement: "Spanish is a language of modest countries, of developing countries, of the poor and migrants."

This comment sparked significant debate, with many pointing out its bias, particularly as some of the world's poorest nations, such as Haiti and several African countries, are French-speaking.

To explore the validity of Audiard's claim, I analysed economic data to compare the GDP per capita of French-speaking and Spanish-speaking countries.

Using a paired t-test and Wilcoxon signed-rank test on aggregated yearly GDP per capita data, both tests revealed a significant difference _(p < 0.01)_ between the two language groups, indicating a robust disparity in their economic performance over time.

__The results showed that, on average, French-speaking countries are economically less prosperous than Spanish-speaking ones.__

![GDP per capita over time by language](/plot1_en.png)
![GDP per capita over time by language with confidence intervals](/plot2_en.png)
![GDP per capita over time by language with confidence intervals including all countries](/plot3_en.png)

### Background
The statement led to a wave of criticism online. Discussions pointed out France’s continued influence over African nations. Some users sarcastically noted: *"The poorest country in the Americas with migration issues is Haiti, and it’s not a coincidence that they speak French."*

### Project Goals
This project aims to:
1. Compare the wealth of French-speaking and Spanish-speaking countries using GDP per capita over time.
2. Analyse which language is more associated with poorer nations.
3. Provide a data-driven perspective on Audiard’s claim.

### Data and Methodology
- **Data source:** Gapminder (GDP per capita through time)
- **Analysis method:**
  - Grouped countries by language and calculated the mean GDP per capita per year.
  - Created line charts for comparison.
  - Plotted confidence intervals and individual country data for better insights.
  - To compare GDP per capita between French-speaking and Spanish-speaking countries over time, a paired t-test was performed on aggregated yearly data for each language group. This method was chosen because the data for each year consisted of matched pairs: one observation for French-speaking countries and one for Spanish-speaking countries. The paired t-test is appropriate for such matched data, as it accounts for the time effect (i.e., the temporal variations in GDP) and focuses on comparing the two language groups within each specific year. By aggregating GDP per capita by year, the analysis controls for individual country-level variations, allowing a clearer comparison of language-based differences over time. In addition to the paired t-test, the robustness of the results was checked using the non-parametric Wilcoxon signed-rank test, which is a suitable alternative when the assumption of normality for the paired t-test is not met.
- **Analysis tools:** Python (Pandas, NumPy, Matplotlib, Seaborn)

### Results

The paired t-test yielded a p-value of 0.00002 (p < 0.01), indicating a significant difference between the GDP per capita of French-speaking and Spanish-speaking countries over time. Similarly, the Wilcoxon signed-rank test produced a p-value of 0.00049 (p < 0.01), further confirming a significant difference. Both tests provide robust evidence that the GDPs of the two language groups differ significantly, with a high level of confidence.

### Contributions
Feel free to contribute by suggesting additional datasets or refining the methodology.

### License
MIT License