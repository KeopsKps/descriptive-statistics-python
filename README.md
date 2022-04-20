# Descriptive Statistics in Python

Descriptive statistics is a way for us to give context to the data we are working with. In this repository I review the concepts included in the descriptive statistics, we can group them in the following sections: central tendency, measures of dispersion, outlier detection and so on.

To demostrate these concepts in code I will be using the dataset from **Amazon Top 50 Bestselling Books 2009 - 2022** which can be found [here](https://www.kaggle.com/datasets/chriskachmar/amazon-top-50-bestselling-books-2009-2022) and consists of the folling columns:

- Book title: string
- Author: string
- User rating: float
- Reviews: integer
- Price: float
- Year: int
- Genre: string

This structure of column name and data type help us to limit the descriptive statistics that can be applied to especific columns.

## Central tendency

The goal is to find the center, the middle point, the "central" tendency of our data. For that purpose we use 3 metrics: the mean, the median and the mode. In this notebook, we learn how to calculate the measures of central tendency in 3 different ways: manually, naive implementation and using Python libraries. 