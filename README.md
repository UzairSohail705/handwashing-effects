## Context:
Dr. Ignaz Semmelweis was a Hungarian physician born in 1818 and active at the Vienna General Hospital. There was a massive issue of
a disease named *Childbed fever* which affected women that just have given birth. As many as **10% of the women** giving birth die from it. The doctor's hypothesis is that there is something contaminated with the hands of doctors delivering the babies. 

## Project Description:
In this project, we're going to analyze the data that made Semmelweis discover the importance of *handwashing*. We will compare data from 
**two clinics** to show the effect of handwashing. as they had a *significant difference* in the proportion of deaths. Then we would 
compare the data before and after the start of handwashing. To test the statistical significance of results, we will perform
**bootstrap analysis** to determine the values with **95% confidence interval**.

## Results
Upon analysis, I found that handwashing did lower the proportion of deaths. The deaths were lowered between
**6.2% and 10%** with a 95% confidence interval. 

## Tools/Methods:
-**Libraries**: Pandas, Numpy, Matplotlib

  -**Statistical analysis**: Bootstrap analysis (in which we resample the data to test for statistical significance)
  
  -**Commands/Methods**: .loc, .append, .plot, .to_datetime, .mean, .series, .sample

