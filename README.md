# Fractional Factorial Design
This project is my AMS 582, Design of Experiments, Computer Project. 

Each model has ten independent variables. The value of each variable, ranging from -1 to 1. The dependent variable Y is given by a function of the independent variables. There is a belief that the model will involve five or fewer independent variables. We need to estimate the function by designing an experiment with the smallest possible amount of data. The goal of the project is 

1. Detect which factors has main effect on $Y$.
2. Detect which factors has interaction effects with whom on $Y$.
3. Determine $Y=f(a,b,c,...,j)$ by finding the estimated model $\hat{Y}$.  

The following statistical tools are used to fulfill the goals. 

---
* ANOVA Test
* Bonferroni Confidence Interval
* QQ-plot
* Multiple Linear Regression
* Adjust $R^2$ - squared
* Daniel Plot
---

I perform a 2^{10-2} fractional factorial design with no replication and statistical analysis on the result to fulfill the goal with R. 

The detailed process of the project is described in `Computer_Project(AMS582).Rmd`. 
## Executing Program
Download R version (>=4.1.0)

Imports: 
* FrF2 (>=2.2-3) 
* multcomp (>=1.4-20)
* DescTools (>=0.99.47)
