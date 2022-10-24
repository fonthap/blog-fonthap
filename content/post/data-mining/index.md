---
title: "523312 KNOWLEDGE DISCOVERY AND DATA MINING"
description: SUT course content knowledge discovery and data mining in academic year 1/2021
date: 2021-11-14
image: 
categories:
    - SUT Courses
tags:
    - Data mining
---

# KNOWLEDGE DISCOVERY AND DATA MINING 
## Data vs Information vs Knowledge
### Data
Data are raw facts and figures that on their own have no meaning.These can be any alphanumeric characters i.e. text, numbers, symbols  
Example  
- Yes, Yes, No, Yes, No, Yes, No, Yes  
- 42, 63, 96, 74, 56, 86  
- 111192, 111234  

four basic types:
- Numbers – are stored as numbers, obviously!
- Text characters are stored as a code that represents each – e.g. ASCII
- Images are stored as numbers representing the amounts of red, green and blue for each pixel
- Sounds are stored as numbers representing the loudness at given intervals  

How we split data in Machine Learning?  

**Training Data**: The part of data we use to train our model. This is the
data which your model actually sees(both input and output) and learn
from.

__Validation Data__: The part of data which is used to do a frequent
evaluation of model, fit on training dataset along with improving
involved hyperparameters (initially set parameters before the model
begins learning). This data plays it’s part when the model is actually
training.

**Testing Data**: Once our model is completely trained, testing data
provides the unbiased evaluation. When we feed in the inputs of
Testing data, our model will predict some values(without seeing actual
output). After prediction, we evaluate our model by comparing it with
actual output present in the testing data.  

 Properties of Data  

1. Volume : Scale of Data. With growing world population and
technology at exposure, huge data is being generated each and
every millisecond.  
2. Variety : Different forms of data – healthcare, images, videos,
audio clippings.  
3. Velocity : Rate of data streaming and generation.  
4. Value : Meaningfulness of data in terms of information which
researchers can infer from it.  
5. Veracity : Certainty and correctness in data we are working on.
### Information
Information is data that has been processed to make it meaningful and
useful

Data + Meaning = Information

Example 
the average mark for the class was 53%, or that boys did better than
girls, or that 76% of the students in your school got a grade A or B,
then that is information!
### Knowledge
Data and information deal with facts and figures.Knowing what to do with them requires knowledge

Knowledge = information + rules

Rules tell us the likely effect of something.  
For example: you are more likely to pass your A level
IF you do your coursework and revise for your exam!
## Data Collection
### Data collection methods
Six data collection methods
1. Interviews
2. Questionnaires and surveys
3. Observations
4. Documents and records
5. Focus groups
6. Oral histories
### Qualitative vs quantitative data collectionmethods

- Quantitative – Numbers, tests, counting, measuring  
ex. questionnaires, surveys, and documents and records

- Qualitative – Words, images, observations, conversations,
photographs  
ex. interviews, focus groups, observations, and oral histories
## Data Preprocessing
Data preparation is the process of taking raw data and
getting it ready for ingestion in an analytics platform.
- Deleting Unnecessary Data
- Consolidating/Separating Fields
- Transforming Data
- Making Corrections to Data
- Changing Formats
### Missing Data
Data is not always available.  
E.g., many tuples have no recorded value for several attributes,
such as customer income in sales data

Missing data may be due to  
equipment malfunction, inconsistent with other recorded data
and thus deleted, data not entered due to misunderstanding
,certain data may not be considered important at the time of
entry, not register history or changes of the data  

Missing data may need to be inferred.  

How to Handle Missing Data?
- Ignore the tuple:  
1. usually done when class label is missing (assuming the
tasks in classification—not effective when the percentage
of missing values per attribute varies considerably)  
2. Fill in the missing value manually: tedious + infeasible?  
3. Use a global constant to fill in the missing value: e.g.,
“unknown”, a new class?!
- Use the attribute mean to fill in the missing value
- Use the most probable value to fill in the missing
value:
1. inference-based such as Bayesian formula or decision tree

<!-- ### Noisy Data -->