# A7-Final-Project
Final Project A7 Report

## Paper description
[Does Price Matter in Charitable Giving? Evidence From a Large-Scale Natural Field Experiment](https://www.nber.org/papers/w12338) is an article written by authors Dean Karlan and John A. List about a large scale natural field experiment that they performed on the behavior of donors of a not-for-profit organization. These authors assigned donors to different treatment groups and observed their donation behavior (donation amount, and whether they donated). These treatments included matching ratio treatment, in which donors were promised different matching ratios (1:1, 2:1, or 3:1 donation matching) as well as suggested donation size ( a multiple of highest previous donation). 

## Accompanying data description 
The paper data is [hosted on Github](https://github.com/gsbDBI/ExperimentData/blob/master/Charitable/RawData/charitable.csv) as a csv. The data is divided into general demographic variables, donor-specific variables and treatment variables. The data is also in the [data folder](Data/charitable.csv) of this repository. The full data in .dat format with relevant data files is [hosted on Harvard Dataverse](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi%3A10.7910/DVN/27853)

### Donor specific variables:
- freq: Number of previous donations
- year: Number of years since previous donation 
- mrm2: Number of months since previous donation 
- hpa: Highest previous contribution
- couple: Whether the donor is a couple
- female: Whether the donor is a female
- out_amountgive: Amount donated (response variable)
- out_gavedum: Dummy variable based on whether they donated more than 0 USD (response variable)
### General demographic variables:
- red0, blue0: Red state / blue state (political affiliation)
- redcty, bluecty: Red county / blue county (political affiliation)
- pwhite, pblack: Percentage of people in area who are white / black 
- page18_39: Proportion of people in area aged 18 - 39
- ave_hh_sz: Average household size
- median_hhincome: Median household income
- Powner: Proportion of people in area who are homeowners
- psch_atlstba: Proportion of people who finished college
### Treatment variables:
- treatment: Whether assigned to treatment or control group
- treat_ratio2: Binary variable indicating whether matching ratio was 2:1
- treat_ratio3: Binary variable indicating whether matching ratio was 3:1
- treat_askd1: Binary variable indicating whether suggested donation was highest previous contribution
- treat_askd2: Binary variable indicating whether suggested donation was 1.25 times the highest previous contribution
- treat_askd3: Binary variable indicating whether suggested donation was 1.50 times the highest previous contribution

## Research questions 
I want to analyze the provided dataset to investigate the following conditions:
1. For the variables gender of donor and racial compostion of where the donor comes from, is there a
relationship between these variables to the dependent variable of amount donation in a signficant
way? If so, what is the relationship?
2. What variables in general are the most important when it comes to informing amount donated?
3. For the various treatment conditions (ratio of matching donation, donation amount suggested), is
there an association with amount donated?

These questions are answered in the [analysis Jupyter notebook](A7_analysis.ipynb). Images for this notebook are saved in [the images folder](images/). Access 
the [presentation](presentation.pdf) for more information about the analysis. 

## Scientific abstract 
Refer to the [scientific abstract](scientfic_abstract.md), that details the results from this analysis,.

## License
This work is under an [MIT License](LICENSE)
