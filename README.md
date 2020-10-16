# Investigating player attributes

Main goal of the project was to prove that the attributes of soccer players like potential, vision, positioning, reactions and stamina have significant impact on forming players' overall rating. 

The ultimate Soccer database was used for the purpose of research: https://www.kaggle.com/hugomathien/soccer

Multiple linear regression was used in order to identify how variables contribute to the players' overall rating. 

# Results

Resulting model has high R-squared value — 0.765, meaning that it explains 76.5% of the variance in dependent variable (overall rating). All independent variables are statistically significant in predicting (or estimating) the players' overall rating; not surprisingly, as potential increases by 1, overall rating will increase by 5.1321. With this same logic, the more is player's vision, positioning, reactions or stamina, the higher is its overall rating.

# Limitations of the project:

Dataset brings together the attributes of tens of thousands of soccer players but we are not sure if the data provided is complete, correct and up to date. Additionally, dropping the rows with missing values (zero values in our case) also affected the overall analysis. And finally, the condition number in the results of multiple regression is large, this might indicate that there are strong multicollinearity or other numerical problems.
