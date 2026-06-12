# The Educational Gradient in Depression: A European Multilevel Study

Code and final manuscript for my master's thesis, Research Master in Sociology and Demography, Universitat Pompeu Fabra (June 2025). Supervisor: Aya Adra.

The thesis examines the extent to which depressive symptoms are unequally patterned across levels of individual and parental education, and whether these patterns differ by gender. Using data from Round 3 of the European Social Survey (n = 18,251, 12 countries), I construct four indices of depressive symptomatology via principal component analysis and estimate multilevel linear regression models with random intercepts for country. The results show a negative association between years of education and depressive symptoms; paternal education moderates the effect of respondents' own education, and the protective effect of education is stronger for women.

## Contents

- `thesis.pdf` — final manuscript
- `create-indices.R` — construction of the depression, heaviness, negative outlook, and disengagement indices (PCA with promax rotation, pooled and country-specific)
- `analysis.R` — multilevel models (`lme4`), natural cubic splines (`splines`), interaction models, and predicted-value plots

## Data

The analysis uses the European Social Survey, Round 3, which is freely available for research purposes at [europeansocialsurvey.org](https://www.europeansocialsurvey.org/). The data files are not included in this repository; the code expects the ESS Round 3 integrated file.

