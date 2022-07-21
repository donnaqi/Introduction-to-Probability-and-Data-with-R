# Numercial Data

## 1. Scatterplots
Use scatterplots for describing the relationship between two numerical variables making sure to note the direction (positive or negative), form (linear or non-linear) and the strength of the relationship (strong or weak) as well as any unusual observations (outliers) that stand out. 

## 2. Distribution of a numerical variable
When describing the distribution of a numerical variable, mention its shape, center, and spread, as well as any unusual observations. 

### 1) Shape

Skewness:
- Left skewed (Negative skew)
- Symmetric 
- Right skewed (Positive skew)

<img src= "https://sigmamagic.com/blogs/images/skewness.jpg">

Modality:
- Unimodal: 
    - one prominent peak
    - also kown as normal distribution / bell curve
- Bimodal: 
    - two prominent peaks
    - two distinct groups, i.e. heights of individuals at a preschool, first peak might be the kids, the second peak might be the teachers
- Uniform: 
    - no prominent peaks
    - no apparent trend in the data. That high and low values of the variable are equally likely to occur
- Multimodel
    - more than two prominent peaks

## 3. Three commonly used measures of center and spread: 

### Center
Mean: arithmetic average <br>
Median: midpoint of the distribution (50th percentile) <br>
Mode: most frequent observation <br>

Sample statistics are point estimates for the unknown population parameters:

<img src="https://media.cheggcdn.com/media/7ac/7ac1a812-3b41-4873-8413-b6a7b8fab530/CL-26481V_image_006.png">

Skewness vs Center:
- left skewed: mean < median
    - few low valued observations pull the average down
    - less than 50% of the data will be smaller than the mean
- symmetric: mean ~ median
- right skewed: mean > median
    - few high valued observations pulled the average up
    - more than 50% of the data will be smaller than the mean

<img src="https://researchhubs.com/uploads/skewness-vs-measures-of-center.png">

### Spread
- Range: max - min
- Variance
- Standard deviation
- Variability vs Diversity
- Interquartile range IQR = Q3 - Q1


## 4. The shape of a distribution as symmetric
Identify the shape of a distribution as symmetric, right skewed, or left skewed, and unimodal, bimodal, multimodal, or uniform. 

## 5. Histograms, box and intensity map
Use histograms and box plots to visualize the shape, center, and spread of numerical distributions, and intensity maps for visualizing the spatial distribution of the data. 

Box plot: do not display modalitu, histograms do
Skewness of a distribution from a box plot: 
- imagine what the histogram would look like
- The peak of the distribution will be roughly around the median
- The tails will extend out to the tails in the box plot 

<img src="https://researchhubs.com/uploads/skewness-by-boxplot.png">


Intensity Map:
- useful to view the spatial distribution
- i.e. income are low in Africa, and high in North America

<img src="https://researchhubs.com/uploads/intensity-map.png">

## 6. Robust statistic
Define a robust statistic (e.g. median, IQR) as a statistic that is not heavily affected by skewness and extreme outliers, and determine when such statistics are more appropriate measures of center and spread compared to other similar statistics. 

- Center: 
    - robust: median
    - non-robust: mean

- Spread:
    - robust: IQR
    - non-robust: SD, range

## 7. Transformations
Recognize when transformations (e.g. log) can make the distribution of data more symmetric, and hence easier to model. <br>

- log transformation: relationship stays positive and becomes more linear, easier to model
- sqaure root transformation
- inverse transformation

goals of transformation: 
- want to see the data structure a little differently
- want to reduce skew to assist in modeling 
- want to straighten a nonlinear relationship in a scatterplot <br>

# Categorical Data

## 1. Use frequency tables and bar plots to describe the distribution of one categorical variable. 

- Histograms: 
    - numerical variables
    - histogram is a number line, so the orders of the bars cannot be changed

- Bar plot: 
    - categorical variables
    - categories can be listed in any order


<img src="https://images.squarespace-cdn.com/content/v1/55b6a6dce4b089e11621d3ed/1611927253487-DBQTE8U444SZJ9AZAAVO/Differences+between+histograms+and+bar+charts.jpg">


- Pie chart: (don't use)
    - only show relative ordering, but not tell actual percentage
    - when have many categorical variable with similar relative frequencies, hard to determine which is higher

<img src="https://etzq49yfnmd.exactdn.com/wp-content/uploads/2022/03/image09-21.png?strip=all&lossy=1&ssl=1">


## 2. Use contingency tables and segmented bar plots or mosaic plots to assess the relationship between two categorical variables. 

- Contigency table: 
    - find the relationship is dependent or not

<img src="https://www.softschools.com/math/probability_and_statistics/images/contingency_table_1.png">

- Segmented bar plots: 
    - useful for visualizing conditional frequency distributions
    - compare relative frequencies to explore the relationship between variables

<img src="https://chartio.com/assets/9bfb20/tutorials/charts/stacked-bar-charts/073137bf11f1c2226f68c3188128e28d66115622dcdecc9bc208a6d4117f53e8/stacked-bar-example-1.png">

- Relative frequency segmented bar plots:
    - plot percentage frequancy
    - segments in each bar add up to 100%

<img src="https://www.statisticshowto.com/wp-content/uploads/2013/01/stacked-bar-chart.gif">

- Mosaic plots:
    - width of the bars: marginal distrubution of x-axis
    - length of the segments: proportion of y-axis

<img src="https://www.jmp.com/en_us/statistics-knowledge-portal/exploratory-data-analysis/mosaic-plot/_jcr_content/par/styledcontainer_2069/par/image_1626416986.img.png/1597772672874.png">

## 3. Use side-by-side box plots for assessing the relationship between a numerical and a categorical variable. 

comparing the distribution of a numerical variable across the levels of a categorical variable

<img src= "https://d2vlcm61l7u1fs.cloudfront.net/media%2Fb04%2Fb043b3eb-65ba-4b7b-997b-1a4b7fd32697%2FphpXIZUxE.png">