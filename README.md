# Bella-Beta-casestudy
You are a junior data analyst working on the marketing analyst team at Bellabeat, a high-tech manufacturer of health-focused
products for women. Bellabeat is a successful small company, but they have the potential to become a larger player in the
global smart device market. Urška Sršen, cofounder and Chief Creative Officer of Bellabeat, believes that analyzing smart
device fitness data could help unlock new growth opportunities for the company. You have been asked to focus on one of
Bellabeat’s products and analyze smart device data to gain insight into how consumers are using their smart devices. The
insights you discover will then help guide marketing strategy for the company. You will present your analysis to the Bellabeat
executive team along with your high-level recommendations for Bellabeat’s marketing strategy.


### Ask
The business task is to analyse the data and figure out the usage of product by customers to guide the formation of marketing strategy for the company.

The datasets of bella beta customers consists of following data-
* Daily activity - This dataset contains information of daily distance travelled in different levels then combined as total distance, calories burnt, and steps.
* Heartrate - This dataset contains data of heartrate recorded at multiple instants per minute daily.
* Calories - This dataset contains data of calories burnt and is available as calories burnt hourly as well as minutely.
* Intensity - This dataset represent data of intensity of activity recorded minutely and then merged to get hourly intensities of activity.
* Sleep - This dataset contains data of sleep recorded minutely with value corresponding to sleep.

### Prepare
This Kaggle data set contains personal fitness tracker from thirty fitbit users. Thirty eligible Fitbit users consented to the submission of
personal tracker data, including minute-level output for physical activity, heart rate, and sleep monitoring. It includes
information about daily activity, steps, and heart rate that can be used to explore users’ habits.

The data consists of Id which is uniquely representing customers. The date column consists of date in mm/dd/yyyy format and time. The calories, steps, heartrate and value of sleep consists of integral values.

### Process
The datasets consist of some non-uniformities which should be rectified through cleaning process. The non-uniformities can be due to mismatched formating, missing values and duplicate data.
The dataset consists of date column which is not formatted properly. So, it should be formatted uniformly to date format. The sleep data consists of data recorded minutely and to make it suitable for analysis 
it must be combined to make it daily data. 
The datasets are available as different file for different time frame. These datasets should be combined for analysis.

### Analyze
After cleaning and formatting data, a new dataset is formed from other datasets through JOINS in SQL. Datapoints from this dataset are analyzed and it can be seen that customers are using the product for tracking 
their physical activity. By observing the relation between different parameters, it is also observed that there is linear relation between calories or steps taken and sleep score. Another obvious linear relation is confirmed 
between calories and steps.



From the insights drawn from the datasets, it is clear that customers are using products for the purpose of tracking physical activity. The relation determined between sleep score and steps or calories signifying 
physical activity can be used for the purpose of formulating marketing strategy focussed on the tracking of physical activity emphasizing its relation with sleep score.



