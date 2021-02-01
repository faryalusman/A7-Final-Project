# Introduction

The paper [Does price matter in charitable giving](https://econweb.ucsd.edu/~jandreon/PhilanthropyAndFundraising/Volume%202/14%20KarlanList.pdf) attempt to observe donor behavior of a not-for-profit organization by assigning them to several treatment groups based on what kind of mail they receive (which will detail the donation ask). The data provided is a mix of demographic, donor-specific and treatment related variables. 

# Research questions
1. For the variables gender of donor and racial compostion of where the donor comes from, is there a
relationship between these variables to the dependent variable of amount donation in a signficant
way? If so, what is the relationship?
2. What variables in general are the most important when it comes to informing amount donated?
3. For the various treatment conditions (ratio of matching donation, donation amount suggested), is
there an association with amount donated?

# Conclusion
For my question about whether demographic variables such as gender of donor and racial composition of area can inform the amount donated, I found no statistical evidence that gender or racial composition can inform donation amounts. However, using EDA I could observe patterns that showed that female donation was lower than male contribution. In addition to gender and race, other demographic variables also showed no signficance in informing amount donated when it came to regressions, although they did stand out as important in the feature selection steps. 

For my question about whether the treatment conditions can signficantly change the amount donated, using hypothesis testing I found no evidence that changing the matching ratio (e.g. promising to match 3 times the donated amount) from a 1:1 setting to higher ratios impacted donations. The same is true for the changing suggeseted donation amount setting.  However, using EDA I could see that a 1:1 Ratio condition corresponded with higher donations, as did a donation suggestion of 1.25 times the previous amount. Similar to what the authors described in the paper, it may be that the donors were wary of conditions that they had no prior exposure to and may have thought a 3:1 matching unlikely. 

When it comes to finding what variables in general were important, variables specific to the behavior of the donor stood out. These included time since previous donations (month and years), highest previous contribution, etc. 
