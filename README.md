# readme.md

**Name**:  Zun Yang
**USF email address**:  zyang65@dons.usfca.edu



*The [PDF version of this assignment spec](https://usfca.instructure.com/courses/1591632/files/folder/assignments?preview=66324308) is available under Files on Canvas.*

As seen during class, there are many requirements on the data we feed to simple linear regression (SLR). In this lab, your task is to recreate the visual work in class to determine whether a dataset is appropriate for SLR and show how you are able to apply the technique to a previously-unseen dataset.

### Data

There are two datasets for this lab, listed in Table 1. Use (only) the Predictors listed.

| Dataset                                                      | Target  | Predictors                    |
| ------------------------------------------------------------ | ------- | ----------------------------- |
| [Toluca (Links to an external site.)](https://drive.google.com/file/d/1nsKeli0EU_PluE0D7yOL0BnqEajhg3hv/view?usp=sharing) dataset (courtesy of Paul Intrevado) | lotSize | workHours                     |
| [Credit (Links to an external site.)](http://faculty.marshall.usc.edu/gareth-james/ISL/Credit.csv) dataset (from Introduction to Statistical Learning with Applications in R) | Limit   | IncomeRatingCardsAgeEducation |

*Table 1: Datasets, Targets and Predictors*

### Process

Use the starter code [here (Links to an external site.)](https://classroom.github.com/a/TLFoAbRg) and fill in your name and USF email in the readme. 

For each predictor, your implementation must:

- Plot the predictor against the target
- Plot the residual against the target
- Determine the coefficients (slope, intercept) against the target

… and based on the above, you must determine whether the predictor is suitable for SLR. 

### Grading

Grades for this assignment will be determined by the grader as follows:

- 100% = Code functions, is well-documented and clearly shows the relationships of all predictors to targets and to residuals.
- 75% = Code functions but is not well-documented or does not clearly show the relationships of all predictors to targets and to residuals.
- 50% = Code functions but is not well-documented -AND- does not clearly show the relationships of all predictors to targets and to residuals.
- 0% = No submission / code does not function.