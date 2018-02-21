# Syllabus: Applied Statistics for High-Throughput Biology

## Instructor

Levi Waldron, PhD  
Assistant Professor of Biostatistics  
City University of New York School Graduate of Public Health and Health Policy  
New York, NY, U.S.A.  

Email: lwaldron.research@gmail.com  
Hangouts: lwaldron.research  
Skype: levi.waldron  

## Times and Places

Classes will take place on March 6, 8, and 13:

|date   | time   |  place |
|-------|--------|--------|
| 6 Marc 2018 | 08:30 - 11:30  | Gamma [Borgo Roma - Ca' Vignal 2] | 
|  8 Marc 2018 |  08:30 - 11:30 |  G [Borgo Roma - Ca' Vignal 2] | 
|  13 Marc 2018 |  08:30 - 11:30 |  Gamma [Borgo Roma - Ca' Vignal 2] | 

## Preparation

Please come to the first class with the following installed:

* Bioconductor www.bioconductor.org/install
* R Studio: https://www.rstudio.com/products/rstudio/download3/
* A command-line or desktop git client. GitHub's desktop client is one of the simplest (https://desktop.github.com/). My own favorite is SourceTree.

Please create an account at www.github.com, and use it to introduce yourself at https://github.com/waldronlab/AppStatTrento/issues. 


## Summary

This course will provide biologists and bioinformaticians with practical statistical and data analysis skills to perform rigorous analysis of high-throughput biological data.  The course assumes some familiarity with genomics and with R programming, but does not assume prior statistical training.  It covers the statistical concepts necessary to design experiments and analyze high-dimensional data generated by genomic technologies, including: exploratory data analysis, linear modeling, analysis of categorical variables, principal components analysis, and batch effects.  

## Textbook

* [Biomedical Data Science](http://genomicsclass.github.io/book/) by Irizarry and Love ([ePub version](https://leanpub.com/dataanalysisforthelifesciences/))
* [Source repository](https://github.com/genomicsclass/labs)

## Related Resources

* Github resources at http://waldronlab.github.io/github/
* Resources for learning R at http://waldronlab.github.io/learnr/
* Other resources at http://waldronlab.github.io/

## Evaluation

Two components are required for class completion: 1) completion of lab exercises each day, and 2) completion of a written report of the final project.  See details below.

### Labs

Each day will include a hands-on lab session, that students should attempt and hand in something before the following class by committing to this Github repository. You are encouraged to work together on lab exercises, but should hand in your own individual work.

### Projects

A project will be handed out before the final class, that will involve analysing a genomics dataset.  Each student will analyse their own dataset and prepare an individual report using R Markdown for reproducible analysis and reporting.
Reports will be assessed for quality of analysis and clarity of presentation.

## Session detail by day

All course materials will be available from https://github.com/waldronlab/AppStatBio/.

1. introduction
    + random variables
    + distributions
    + hypothesis testing for one or two samples (t-test, Wilcoxon test, etc)
    + hypothesis testing for categorical variables (Fisher's Test, Chi-square test)
    + data manipulation using dplyr
2. linear modeling
    + linear and generalized linear modeling
    + model matrix and model formulae
    + multiple testing
3. unsupervised analysis
    + graphics for exploratory data analysis
    + distance in high dimensions
    + principal componenets analysis and multidimensional scaling
    + unsupervised clustering
    + batch effects
