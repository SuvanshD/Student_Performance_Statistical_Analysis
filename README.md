# Student Performance Statistical Analysis

## Overview
Statistical analysis employs various methods to summarize, analyze, and interpret data. It involves applying statistical techniques and tools to understand patterns, relationships, and trends in data, ultimately drawing meaningful conclusions. This project will utilize statistical methods, such as measures of central tendency, measures of dispersion, and hypothesis testing, to derive insights from the student performance dataset.

## What are We Building?
In this project, we will analyze the **Student Performance Dataset**, which contains details about the performance of 1,000 students. The dataset includes information such as gender, parents' education, race/ethnicity, and scores in math, reading, and writing. You can download the dataset from [here](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams?resource=download). We aim to perform statistical analysis to identify underlying patterns and derive insights from this data.

## Pre-Requisites
To follow along with this project, you should have a basic understanding of:
- Python
- Descriptive Statistics
- Inferential Statistics
- Hypothesis Testing

## How Are We Going to Build This?
1. **Load the Dataset**: We will load the dataset and explore it using measures of central tendency (mean) and measures of dispersion (standard deviation).
2. **Perform Hypothesis Testing**: We will define multiple hypotheses and validate them using various techniques.

## Requirements
We will use the following libraries, tools, and modules in this project:
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Scipy

## Dataset Feature Descriptions
The dataset consists of the following features:
- **gender**: The gender of the student.
- **race/ethnicity**: The race or ethnicity of the students.
- **parental level of education**: The education status of the parents.
- **lunch**: The category of the student’s lunch.
- **test preparation course**: Whether the student completed any preparation course or not.
- **scores**: Scores in math, reading, and writing.

## Doing the Statistical Analysis
### Import Libraries and Loading Dataset
We will start by importing all necessary libraries for statistical analysis and loading the dataset. 

### Measure of Central Tendency and Dispersion
We will analyze numerical features using measures of central tendency (mean) and dispersion (standard deviation).

### Hypothesis Testing
Hypothesis testing is a statistical method used to test whether a hypothesis about a population or sample is true or false. We will test four different kinds of hypotheses using various techniques:
1. **Hypothesis 1**: There is no significant difference between a student's performance in reading, writing, or math.
2. **Hypothesis 2**: There is no relation between the gender of a student and their corresponding academic performance.
3. **Hypothesis 3**: An educational consultancy claims that students receive a mean score of 70 or more on average.
4. **Hypothesis 4**: There is no significant difference in the mean math scores of students who have taken test preparation and those who have not.

## Summary
Our findings from the statistical analysis of the student performance dataset include:
- No major differences in the mean and standard deviation of scores in math, reading, and writing.
- Students perform unequally across different subjects, indicating the need for focused support in weaker areas.
- Gender does not significantly influence overall academic performance.
- The claim by the educational consultancy regarding a mean score of 70 is false.
- Students who completed prior test preparation perform better.

## Conclusion
In this project, we loaded and analyzed the student performance dataset, exploring the central tendency and dispersion of various features. We conducted hypothesis testing on four different hypotheses using techniques such as the one-way ANOVA test, chi-square test of independence, one-sample t-test, and independent t-test.

