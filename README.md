# mind-your-language

### Project contributors:

1. [Sean Conley](https://github.ubc.ca/conleyst)
2. [Ruoqi Xu](http://github.ubc.ca/rq1995)
3. [Abishek Murali](https://github.ubc.ca/amurali)


### Introduction

Our project explores how the first programming language that you learnt affects your preference between R and Python.

### Survey
We designed a [survey](https://docs.google.com/forms/d/1dfnSiBsicGfV4rYh5XcmsFbeY_k2n3nvtBobQYNH6X4/edit?usp=sharing) in Google Forms and collected 45 responses. You can find an outline of the survey [here](./doc/survey-outline.md).

### Data
You can find [clean data](./data/clean-survey_data.csv) and [raw data](./data/raw-survey_data.csv) in the `data` folder.

### Analysis
Based on these data, we used logistic regression to control for the confounding variables and predict the probability that a person prefers Python and the probability that a person prefers R. We looked at the coefficient associated with the first programming languages to see if they were non-zero in a statistically significant way.

Here is the [analysis script](./src/perform_analysis.Rmd).

Here is the [final report](./doc/final_report.pdf).
