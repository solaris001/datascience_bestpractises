# Reproducibility


## Table of contents
* [Introduction](#introduction)
* [Structure of the Repository](#structure-of-the-repository)
* [Technologies](#technologies)
* [Setup](#setup)
 

## Introduction 

That the results of a scientific work is super central for scientific analysis, and also of certain interest of business concerns, because we use data sciences results as base for following decisions and theories. Therefore we must trust out data sciences results that they are true. If we do not want to blindly trust the results of our data science pratice, we can test them by trying to reproduce the results. 

This codesheet is divided into two topics: (1) _reproducible model training_ of the [southern german credit dataset](https://archive.ics.uci.edu/ml/datasets/South+German+Credit), and (2) _reproducing results_ of [Verma & Rubin (2018)](https://dl.acm.org/doi/10.1145/3194770.3194776) using the [german credit dataset](https://archive.ics.uci.edu/ml/datasets/statlog+(german+credit+data)). 

The preprocessing of the dataset has been done in Assignment 2. Firstly it was done for the German Credit Dataset. Form there some problems with the dataset occured. IF you want more information on that you may check the notebook in the [datafolder](https://github.com/solaris001/datascience_bestpractises/blob/main/Data/Introductory_Datascience_Practise.ipynb). Therefore the preprocessing has been done in the same way for the South German Credit Dataset, which you can also find in the folder [Data](https://github.com/solaris001/datascience_bestpractises/tree/main/Data).

For (2) it was tried to reproduce the results of the paper, following a quote of the paper on the steps that the authors have been doing in their analysis: "For our discussion, we trained an off-the-shelf logistic regression classifier in Python. We applied the ten-fold cross-validation technique, using 90% of the data for training and the remaining 10% of the data for testing and illustrating each of the definitions. We used numerical and binary attributes directly as features in the classification and converted each categorical attribute to a set of binary features, arriving at 48 features in total." (Verma & Rubin, 2018)


Spoiler alarm! 


For this codesheet it was not possible to reproduce the results of the authors, and a short discussion of this is found as documentation of the code. The work of Verma & Rubin is professionally done and there may be many reasons why the results couldn't be reproduced. Furthermore, one has to keep in mind that the approach of the paper of Verma & Rubin was not on reproducibility, but on addressing fairness-related issues. 


Matter of fact, the reader is very welcome to use this code in order to reproduce the results or to optimize the data analysis by a differen modeling. If you do so and want to reach out to the author of this codesheet you can do that via the following canals: 
E-Mail: _laurasophia.vonhirschhausen@gmail.com_
LinkedIN: _https://www.linkedin.com/in/laura-von-hirschhausen/_


Please don't hesitate to reach out also if you find conceptual mistakes or odd interpretation! Everyone is happy to learn from others. 


Have a good time with the code and a steep learning curve!


## Structure of the Repository

Readme.md

[Reproducibility.ipynb] (https://github.com/solaris001/datascience_bestpractises/blob/main/Reproducibility/A3_Reproducibility.ipynb)

the data we work with: [df_germanData_readable.csv](https://github.com/solaris001/datascience_bestpractises/blob/main/Reproducibility/df_germanData_readable.csv), [gc_data.csv](https://github.com/solaris001/datascience_bestpractises/blob/main/Reproducibility/gc_data.csv), [sgc_data_readable.csv](https://github.com/solaris001/datascience_bestpractises/blob/main/Reproducibility/sgc_data_readable.csv) and [south_german_credit_data_preprocessed.csv](https://github.com/solaris001/datascience_bestpractises/blob/main/Reproducibility/south_german_credit_data_preprocessed.csv).

[codetable.txt](https://github.com/solaris001/datascience_bestpractises/blob/main/Reproducibility/codetable.txt)


## Libraries

Pandas 

Numpy

Matplot

Seaborn

SKlearn