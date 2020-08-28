# Data-Science
## 2020 Summer Data Science Learning

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
