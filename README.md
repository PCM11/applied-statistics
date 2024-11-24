# My applied-statistics Repository

** by Phumi Tshidi (phumitshidi@gmail.com)**

## About the repository

This repository contains my assessment submission for 24-25: 8651 - APPLIED STATISTICS module.
It consists of four tasks and one project.

## Tasks

- **1. Permutations and Combinations** - Lady Tasting Tea experiment with twelve cups of tea. Six have the milk in first and the other six having tea in first. A person claims they have the special power of being able to tell whether the tea or the milk went into a cup first upon tasting it.
Calculate, using Python, the probability that they select the correct six cups.

- **2. numpy's Normal Distribution** - Generate a sample of one hundred thousand values using the function with mean 10.0 and standard deviation 3.0. Use the scipy.stats.shapiro() function to test whether your sample came from a normal distribution. Explain the results and output.


- **3. t-Test Calculation** - Use python to calculate the t-statistic based on the dataset containing resting heart rates for patients before and after embarking on a two-week exercise program. Compare it to the value given by scipy.stats

- **4. ANOVA** - In this test we will estimate the probability of committing a type II error in specific circumstances. Create a variable called no_type_ii and set it to 0. Now use a loop to perform the following test 10,000 times.
Use numpy.random.normal to generate three samples with 100 values each. Give each a standard deviation of 0.1. Give the first sample a mean of 4.9, the second a mean of 5.0, and the third a mean of 5.1.
Perform one-way anova on the three samples and add 1 to no_type_ii whenever a type IIerror occurs.

## Project

A project.ipynb notebook that analyzes the PlantGrowth R dataset. A short description of it is on Vicent Arel-Bundock's Rdatasets page. The dataset contains two main variables, a treatment group and the weight of plants within those groups.

Perform t-tests and ANOVA on this dataset while describing the dataset and explaining your work.

## Installations

I used [openincolab.com](https://openincolab.com/) to generate the following clickable link. It opens the `tasks.ipynb` notebook 
in [Google Colab](https://colab.research.google.com/github/PCM11/applied-statistics/blob/main/tasks.ipynb).

To further explore this dataset you need to download python, which can be installed through [anaconda](https://www.anaconda.com
download), and notebook editor, which can be found in [Visual Studio Code](https://code.visualstudio.com/)

## Analysis

 I imported Python libraries to analyse the data.

- Pandas - for data manipulation and analysis. It allo
us to investigate CSV files, amongst other features.

- Matplotlib - for data visualisation and graphical 
plotting

- Seaborn - built on top of matplotlib with similar 
functionalities

- Numpy - to perform  wide variety of mathematical 
operations on arrays

- Math - for mathematical functions from the standard library.

- Itertools -for permutations and combinations.

- Random -for random selections.

- Scipy - for statistics

- Statsmodel - for statistical models