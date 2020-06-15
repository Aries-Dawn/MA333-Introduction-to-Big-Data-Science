# MA333-Introduction-to-Big-Data-Science
****
This is about the Project of this class.

****

## Task 1 (Mandatory)

​	You need to first get familiar with the data by data statistics and visualization.

1. You are asked to first do the data preprocessing for the ‘PatientInfo.csv’ data.Then visualize the data by examining the distribution of the patients using python package ‘matplotlib’ and ‘seaborn’. For instance, the histograms across the attributes `‘sex’`,` ‘age’`,` ‘city’`, `‘province’`, `‘infection_case’`, etc. You can also plot the histograms of ‘released’ patients and ‘deceased’ patients across the attributes ‘sex’, ‘age’, ‘city’, ‘province’, ‘infection_case’, etc. Based on these plots, can you find any interesting relations and draw any conclusions?
2. Please also visualize the time series data fromthe files ‘Time’, ‘TimeAge’, ‘TimeGender’,and ‘TimeProvince’. Collect the useful information from these plots.Note that the first outbreak in South Korea is on 1/20/2020.

### Task 2 (Mandatory)

​	Prediction of the recovery time of the patients.

​	From the file ‘`PatientInfo.csv`’, it is easy to roughly define the ‘`recovery time`’ as the difference between ‘`released_date`’ and ‘`confirmed_date`’. For the ‘`deceased`’patients, you can either define the recovery time to be infinity (or a very large number) or simply delete it in this task. Then predict the ‘recovery time’ by using any regression techniques you like. Remember to divide the samples into training set and test set. Take into account as more features as you can, e.g., the medical level and education level of the cities where the patients came from and where they were treated. Some of this information can be read from the other files, e.g.,‘`Region.csv`’. Which are the important features? (Remark: this task can also be a classification problem, e.g., simply ‘released’ vs. ‘deceased’.)

## Task 3: Say something about the risk levels of the cities

​	Due to the different infection numbers, education levels, medical loading capacities,number of group infections, numbers of oversea inflows etc., different cities should have different risk levels. Can you give a risk level for each city, e.g., high,middle, or low? Of course you can rank the risk levels in more details. Perhaps clustering can be used for this task. If you are the policy maker, what shall you do?

## Task 4: A hard task is to do trend prediction of the infection numbers.

​	This depends on the social network, the public consensus about the emergency events, and more importantly the self-protection awareness of the people, and the government policy, etc. Try to integrate some of these effects into your model, and make a prediction of the trend of the infection numbers. You can use any model you like. The information from the data files ‘Weather.csv’, ‘SearchTrend.csv’, etc.could be used. Perhaps network model and time series analysis can be good for this task. The dynamical model based on differential equations are also welcome.


