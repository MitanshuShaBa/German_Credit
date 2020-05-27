# German_Credit

#### Data Source

This is the exploratory data analysis of the [German Credit Database](https://www.kaggle.com/uciml/german-credit).

This dataset is a subset of the full dataset by Prof. Hofmann. Original dataset: [UCI](https://archive.ics.uci.edu/ml/datasets/Statlog+%28German+Credit+Data%29)

#### Data Description

In this dataset, each entry represents a person who takes a credit by a bank. There are 1000 such entries and 9 features.

#### Project Goal

To do Exploratory Data Analysis of this dataset and find interesting insights.

#### Conclusion

* As credit amount went up duration for the credit also went up

![credit_heatmap](/images/credit_heatmap.png)

* People didn't prefer to take big credits for large amount of time

![credit_dur_regplot](/images/credit_dur_regplot.png)

* We can see that highly skilled workers took greater credit amount than others even though they applied for less no. of applications

![Job_num_application](/images/Job_num_application.png)
![Job_amount](/images/Job_amount.png)

* The biggest applications for credit were for car. People who didn't have house where applying to get cars.

![Purpose_count](/images/Purpose_count.png)

![free_purpose](/images/free_purpose.png)

