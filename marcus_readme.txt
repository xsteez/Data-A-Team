# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 5 Crash Data

### Contents:
- [Problem Statement](#Problem-Statement)
- [Summary](#Summary)
- [Methodology](#Methodology)
- [Findings and Observations](#Findings-and-Observations)
- [Best Models](#Best-Models)
- [Conclusions](#Conclusions) and [Next Steps](#Next-Steps)




###Problem Statement
Upon original analysis I was trying to determine if in a crash there was a higher likely hood of their being more than one fatality. I will also attempt to predict severity time permitting to see if there are any ways to help prevent injuries. 


###Summary
For every state case are they more likely to be a multiple person fatality? How does that affe
If so, what are some suggestions to help reduce and prevent these accidents with multiple fatals?
Which models did you use?




I collected data from the Traffic Safety Administration from 2020, and as I mentioned before I took a look at both severity and fatals. For fatals I was trying to determine with what accuracy I could predict if- when an accident occured- I could predict the likeliness that it was going to involve mutiple fatals. 



###Methodology
In order to complete the process I cleaned the data that I beleived to be necessary to improve my model. I wanted to first analyze the largest correlations and see how those features had an effect on fatalities. I did this by using a variety of different data vizualization techniques. The eda process involved me dropping rows that harmed the overall data set. 



###Findings and Observations
What I saw was that our predictors were pretty apparent, for example persons correlated heavily with fatalities and accident severity. One surprising find was that light_conditions and work_zones had little to no effect but on the other hand drunk driving did.


###Best Models
The best models were the random forrest and logistic regression. I believe that for classification problems these two are very accurate and great predictors for this particular problem as I binarized this data.


###Conclusions and Next Steps

Be over prepared for situations involving multiple cars and many people.
Continue to educate people on the dangers involved in driving while distracted.






























