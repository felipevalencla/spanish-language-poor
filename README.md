# Jacques Audiard's Comment on Spanish as a "Language of the Poor"

## Author: Felipe Valencia-Clavijo

### Abstract
French director Jacques Audiard, while promoting his movie *Emilia Perez*, stated: *"Spanish is a language of modest countries, of developing countries, of the poor and migrants."* 

This comment sparked significant controversy, with many pointing out its bias. Critics highlighted that some of the world's poorest nations, such as Haiti and several African countries, are French-speaking. 

Curious about the validity of Audiard's statement, I decided to explore economic data to compare the wealth of French-speaking and Spanish-speaking countries.

__The results of the data visualization analysis showed that on average, francophone countries are actually poorer than Spanish-speaking ones.__

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
- **Analysis tools:** Python (Pandas, NumPy, Matplotlib, Seaborn)

### Contributions
Feel free to contribute by suggesting additional datasets or refining the methodology.

### License
MIT License