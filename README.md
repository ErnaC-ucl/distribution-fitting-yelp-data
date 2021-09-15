# distribution-fitting-yelp-data

There are two research questions this analysis:
- **RQ1**: What probability distribution is well suited to describe the user and business reviews data on a selected metropolitan area? Provide an estimation of parameters for such distribution.
- **RQ2**: Are Yelp users consistent across different states? Discuss differences and similarities between the distribution of star ratings betwee two different states.

Yelp dataset is used to study the statistics of online reviews in the metropolitan area of Arizona. In particular we want to analyse the probability distribution
that is well suited to describe the data and provide an estimate for the parameters of such distribution. Then, we analyse the consistency of ratings and the similarity
of statistical distribution for two different states namely, Arizona and Nevada.

**We conclude that:**
- a composite distribution which consists of a Gaussian Kernel for the body and power law for the tail is  well suited to describe Yelp reviews data. 
- for the distribution of ratings we have observed that while the empirical moments and the plots indicate a high degree of similarity, based on the statistical tests of Kolmogorov Smirnov and Cramer-von Mises (CVM), the null hypothesis that the two distributions are similiar is rejected at the 5% confidence level.

# This repo contains:
- A pdf report which describes in detail the methodology and findings of our analysis;
- A Jupyter notebook for data cleaning and pre-processing
- Matlab script for the main analysis 
