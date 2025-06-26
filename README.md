# Predicting offspring height based on parental heights

Project Instruction:  Identify a data set of interest to you with a quantitative variable you wish to predict and/or model. This outcome variable must not be categorical. Use your own kNN algorithm to predict/model the value of your variable of interest using at least one categorical and one quantitative variable, preferably more.

# My project: 
For this project, I used a dataset collected by Professor Myers, which includes the heights of Middlebury economics students along with their parents' heights over the past ten years. However, this dataset comes with some caveats. The majority of Middlebury economics students are male and many participate in sports, which introduces potential bias into the predictions. Since male and athletic individuals tend to be taller on average, the model may not fully generalize to a broader population. Despite these limitations, the dataset provides a sufficient foundation for me to develop a k-Nearest Neighbors algorithm to estimate the height of my future children. 

## Variables of Interest: 

Quantitative (1): Father's Height Quantitative (2): Mother's Height Categorical (1): Sex of the Offspring Outcome (1): Offspring Height

## Conclusion:
Interpretations from visualization (found on the Rmd/Quarto/HTML):
The male offspring tend to have higher predicted heights compared to female offspring, as indicated by more yellow shades on the right side of the male facet. On the other hand, the darker purple regions in the female facet are indicative of predictions of shorter heights for female offspring. This shows that our algorithm captures the height differences across box sexes.

Overall, when both parents are taller, predicted offspring height is also taller (around 72 inches or more). The opposite trend appears for shorter parents, where predictions lean toward shorter offspring heights. This pattern aligns with the concept of assortative mating, which suggests that people tend to choose partners with similar physical traits, including height.

The color gradient shifts more noticeably along the X-axis than the Y-axis, suggesting that father’s height has a stronger influence on the offspring’s predicted height, especially for male offspring.
