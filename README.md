# A Bayesian Network to model road accident in the metropolitan city of Bologna

## Introduction
Nowadays road accident are one of the leading cause of death, especially between
young people. Each year, 1.35 million people are killed on roadways around the
world. It is estimated that fatal and nonfatal crash injuries will cost the world
economy approximately 1.8 trillion dollars from 2015{2030.
Analysing how the circumnstances of the accident affects the type of the crash
and the total casualties can help to build better safety measures.
In this notebook I will do this analysis using Bayesian Networks with the aim of
providing a model that can give probabilistic results given some input evidence.
This project was inspired by a paper by Xin Zou and Wen Long Yue from the
University of Australia.

## The Dataset
The data to compute the conditional probability table of the model are taken
from ISTAT (Italian National Institute of Statistics) in the form of microdata
that is data on the characteristics of units of a population, such as individuals
collected by a census, survey, or experiment. The data describes only accident
that have caused some kind of injuries to people in the year 2019. The dataset
had a lot of attribute that will not be used (like genders, age, etc...), and some
attributes needed to be cleaned. But the process of datacleaning was not the
object of this project so will not be reported.
