# Introduction 
This project's objective is to solve a binary classification problem. The response variable is 'Clicked' which represents whether an individual clicked an online advertisement.

# Narrative
SearchMe is an Internet giant and search engine company that earns the majority of its revenue through online advertising. Their aim is to maximize the number of clicks their advertisements generate. Management has decided to investigate which users are more likely to click a particular advertisement. They want to analyze which factors affect this the most. This will not only help to increase the engagement but will also help in user profiling.

# Objective
Using machine learning, predict which users are likely to click a particular advertisement and explain how different features affect the prediction.

For each record in the test set (test.csv), predict the value of the Clicked variable (0/1). Submit a CSV file with test entries, plus a header row. the file (submissions.csv) should have exactly 2 columns:
* id
* Clicked (contains 0 or 1)

# Files
* train.csv
* test.csv
* sample_output.csv

# Schema

Column | Description
:---|:---
`id` | Unique consumer id
`Daily Time Spent on Site` | Consumer time spent on site (in minutes)
`Age` | Consumer age (in years)
`Area Income` | Avg. Income of geographical area of consumer (in US $$)
`Daily Internet Usage` | Avg. minutes a day consumer is on the internet
`Ad Topic Line` | Headline of the advertisement
`gender` | Gender of the consumer
`Country` | Country of consumer
`Timestamp` | Timestamp at which consumer clicked on Ad or closed window (YYYY-MM-DD HH:MM:SS)
`Clicked` | Whether a consumer clicked on the advert or not (0: No ,1: Yes)