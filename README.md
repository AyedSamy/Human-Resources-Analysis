# Human Resources Study
![Kaggle](https://img.shields.io/badge/Dataset-Kaggle-blue.svg) ![Python 3.7](https://img.shields.io/badge/Python-3.7-blueviolet.svg) ![Seaborn](https://img.shields.io/badge/Library-Seaborn-success.svg) ![Scikit-learn](https://img.shields.io/badge/Library-Scikit_Learn-orange.svg)

This study is around an IT Company to perform Data visualization techniques, Exploratory Data Analysis & Machine Learning models to predict Employee Termination.

## Overview

This data set took from Kaggle revolves around a fictitious company and contains a lot of informations on the human resources : **names**, **DOBs**, **age**, **gender**, **marital status**, **date of hire**, **reasons for termination**, **department**, whether they are **active or terminated**, **position title**, **pay rate**, **manager name**, **performance score**, **absences**, **most recent performance review date**, and **employee engagement score**.

In a **first part**, many points of interest can be explored through all these variables. Because grasping relevant information is the key to set up a good management, it is important for companies to study this kind of dataset and sometimes when it's needed, make new decisions.
Thus, to help our company to evolve, a lot of questions can be addressed thanks to data analysis :
- Is the **performance score** unequal between different **areas** of the company ?
- Is there any relationship between **who** a person works for and their **performance score** ?
- What is the overall **diversity profile** of the organization ?
- What are our best **recruiting sources** if we want to ensure a **diverse organization** ?
- Are there **areas** of the company where **pay** is not equitable ?
- Can we get an intuition on who are the **terminated employees** ?
- Which **profiles** tend to cumulate **absences** or to have a poor **satisfaction** working in the company ?

In a **second part**, we'll try to address the following question :
- Can we predict who is going to **terminate** and who isn't ? What level of **accuracy** can we achieve on this ?

It will be done creating several Supervised Machine Learning models, built following all the **preprocessing** steps, setting up a full **pipeline**. We will also try to increase the **accuracy** of our models using **Hyperparameter tuning**, which will allow us to select the best one with **K-Fold Cross Validation** and the best **evaluation metric**.

## Source

[Human Resources data set - Kaggle](https://www.kaggle.com/rhuebner/human-resources-data-set)