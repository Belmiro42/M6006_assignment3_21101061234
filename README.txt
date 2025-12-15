***Research Question***
Do UK migration patterns follow wealth inequality and deprivation patterns in local councils?

***Hypothesis:***
Migration from high income areas increase wealth inequality in the area they migrate to.
This changed over time as we aggregated smaller councils to bigger regions.

***Cleaning***
Cleaning done in Cleaning_Income.ipynb and Cleaning_Migration.ipynb notebooks
The cleaning is just removing rows with lots of nan values and standardising what the dataframes look like.
This was a problem because it eliminated councils that were low income which was the target demographic we were looking for as they were largely underdocumented.

***Analysis***
Analysis done in Merging.ipynb notebook 
We have done a few regression calculations.
The first one was exploratory and not causal because it had a lot of colinearity.
We did more regression with less variables that had overlapping figures and these more robust analyses proved lower significance in our findings.

***Conclusion*** 
To conclude, the results provide little evidence that migration from high-income origin areas is a key driver of short-term change in income inequality measured by the Foster Wolfson index. Detailed models suggested that the relationship could differ across age groups; however, these patterns were not statistically robust when tested against simple models. This indicates that the association between migration and inequality is weak. More detailed data or longer time periods would be needed to identify any clearer distributional effects. A major limitation of our work was created by the substantial reduction in sample size that occurred during the data cleaning and merging process, including assimilating various counties into larger areas meaning microtrends were eliminated. As a result, the final dataset used for analysis contained fewer than 50 rows. This reduction likely limited the statistical power of the models, making it harder to determine effects if they existed. Also, the use of year-on-year change in inequality may underestimate longer-term effects of migration, which may be more visible over longer time frames due to factors such as housing markets and labour. With more time or data access, we could have tried to extend the analysis over longer time scales or different types of lagging variables. 
