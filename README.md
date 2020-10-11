# Data-Science
## 2020 Summer Data Science Learning
##### Note: These projects were done in conjunction with data science courses I was taking. They demonstrate my ability to implement what I've learned.

### [EDA: Effect of Time Elapsed on Gene Expressions](https://github.com/ronwho/Data-Science/blob/master/EDA%20Effect%20of%20Time%20Elapsed%20on%20Gene%20Expressions.ipynb)
* I examined a dataset of gene expressions found in this research paper. https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE5859
* This paper looks at the allelic differences among a wide variety of ethnicities across the world.
* I wanted to see if there were any inconsistencies in the gene expressions of North Americans with Northern or Southern European descent based on the time elapsed
* For the final result, I found that after 100 days of sampling, there was an inconsistency with the data. I found out by computing the SVD then plotting PC1 on the y-axis versus the days elapsed
#### Skills used:
1. Pandas for data wrangling
2. Matplotlib for data visiualization
3. Linalg.svd (single value decomposition) for dimension reduction
![](/imgs/eda1.JPG)

### [EDA: Is there Bias in Pollsters in Elections Polls](https://github.com/ronwho/Data-Science/blob/master/EDA%20Is%20there%20Bias%20in%20Pollsters%20in%20Elections%20Polls.ipynb)
* I examined a dataset of the 2012 Mitt Romney and Obama general election from the Huffingtonpost Pollster found here: https://elections.huffingtonpost.com/pollster/2012-general-election-romney-vs-obama
* This dataset looks at various pollsters from many different sources. It includes the number of polls, score of Obama and Romney,etc.
* I wanted to see if there were any bias across a large variety of polsters.
* For the final result, I found that the polls were not biased because the standard deviation real data's standard deviation is smaller than the standard deviation we simulated assuming that the data is not biased
### Skills used:
1. Pandas for data wrangling
2. Matplotlib for data visiualization
3. NumPy (standard error, random binomial distribution)
4. SciPy (qqplot)

![](/imgs/eda2.JPG)

### [EDA: Picking the Most Effective Baseball Players using Sean Lahman's Dataset](https://github.com/ronwho/Data-Science/blob/master/EDA%20Picking%20Baseball%20Players%20Using%20Linear%20Regression.ipynb)
* I examined a Sean Lahman's Baseball database found here: http://www.seanlahman.com/baseball-archive/statistics/
* Using Sean Lahman's Baseball Database preceding from 2002, I would like to pick 10 offensive players that keeps the payroll under 20 million dollars, also predict how many games this team would win in a 162 game season
* For the final result, I successfully found a group of baseball players from each position under the budget of 20 million dollars and it is predicted they will be able to win 98 games in a 162 game season.
### Skills used:
1. Pandas for data wrangling
2. Matplotlib for data visiualization
3. linear_model (Linear Regression)

![](/imgs/eda3.JPG)
