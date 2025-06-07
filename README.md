# vivek_stats

**vivek_stats** is a custom-built Python library designed to simplify and automate statistical analysis during the Exploratory Data Analysis (EDA) phase of data science projects.

This lightweight module calculates 15+ essential descriptive statistics with a single function call. Ideal for students, beginners, and data science learners who want to quickly summarize numeric data.

## 📊 Key Features

- Total Count and Sum  
- Minimum, Maximum, and Range  
- Mean, Median, Mode  
- Variance and Standard Deviation  
- Interquartile Range (IQR), Q1, Q3  
- Lower & Upper Whiskers (for boxplot insights)  
- Skewness and Kurtosis

## 🚀 Quick Start

```python
from vivek_stats import cal_stats
import pandas as pd

df = pd.read_csv('your_data.csv')
cal_stats('column_name', df['column_name'])
