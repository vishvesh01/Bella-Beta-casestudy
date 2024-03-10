# Bella-Beta-casestudy
You are a junior data analyst working on the marketing analyst team at Bellabeat, a high-tech manufacturer of health-focused
products for women. Bellabeat is a successful small company, but they have the potential to become a larger player in the
global smart device market. Urška Sršen, cofounder and Chief Creative Officer of Bellabeat, believes that analyzing smart
device fitness data could help unlock new growth opportunities for the company. You have been asked to focus on one of
Bellabeat’s products and analyze smart device data to gain insight into how consumers are using their smart devices. The
insights you discover will then help guide marketing strategy for the company. You will present your analysis to the Bellabeat
executive team along with your high-level recommendations for Bellabeat’s marketing strategy.


### Business Task
The business task is to analyse the data and figure out the usage of product by customers to guide the formation of marketing strategy for the company.

### Prepare and Process
The datasets of bella beta customers consists of following data-
* Daily activity - This dataset contains information of daily distance travelled in different levels then combined as total distance, calories burnt, and steps.
* Heartrate - This dataset contains data of heartrate recorded at multiple instants per minute daily.
* Calories - This dataset contains data of calories burnt and is available as calories burnt hourly as well as minutely.
* Intensity - This dataset represent data of intensity of activity recorded minutely and then merged to get hourly intensities of activity.
* Sleep - This dataset contains data of sleep recorded minutely with value corresponding to sleep.

This Kaggle data set contains personal fitness tracker from thirty fitbit users. Thirty eligible Fitbit users consented to the submission of
personal tracker data, including minute-level output for physical activity, heart rate, and sleep monitoring. It includes
information about daily activity, steps, and heart rate that can be used to explore users’ habits.

Original data set: [FitBit Fitness Tracker Data](https://www.kaggle.com/code/youssefabdelghfar/fitbit-fitness-tracker-data)

The data consists of Id which is uniquely representing customers. The date column consists of date in mm/dd/yyyy format and time. The calories, steps, heartrate and value of sleep consists of integral values.

The datasets consist of some non-uniformities which should be rectified through cleaning process. The non-uniformities can be due to mismatched formating, missing values and duplicate data.
The dataset consists of date column which is not formatted properly. So, it should be formatted uniformly to date format. The sleep data consists of data recorded minutely and to make it suitable for analysis 
it must be combined to make it daily data. 
The datasets are available as different file for different time frame. These datasets should be combined for analysis.

Cleaned data: [Processed FitBit Fitness Tracker Data](https://www.kaggle.com/datasets/vishvesh01/bella-beta-data)

### Analysis and Visualization
After cleaning and formatting data, a new dataset is formed from other datasets through JOINS in SQL. Datapoints from this dataset are analyzed and it can be seen that customers are using the product for tracking 
their physical activity. By observing the relation between different parameters, it is also observed that there is linear relation between calories or steps taken and sleep score.

<div class='tableauPlaceholder' id='viz1710076807421' style='position: relative'><noscript><a href='#'><img alt='Dashboard 3 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;To&#47;TotalDistancevsDate&#47;Dashboard3&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='TotalDistancevsDate&#47;Dashboard3' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;To&#47;TotalDistancevsDate&#47;Dashboard3&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>    

<div class='tableauPlaceholder' id='viz1710076849612' style='position: relative'><noscript><a href='#'><img alt='Dashboard 2 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ca&#47;CaloriesvsDate&#47;Dashboard2&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='CaloriesvsDate&#47;Dashboard2' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ca&#47;CaloriesvsDate&#47;Dashboard2&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>   


<div class='tableauPlaceholder' id='viz1710073988957' style='position: relative'><noscript><a href='#'><img alt='Dashboard 1 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Be&#47;BellaBeatAnalysis_17098487273780&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='BellaBeatAnalysis_17098487273780&#47;Dashboard1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Be&#47;BellaBeatAnalysis_17098487273780&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                

### Conclusion
From the insights drawn from the datasets, it is clear that customers are using products for the purpose of tracking physical activity. The relation determined between sleep score and steps or calories signifying 
physical activity can be used for the purpose of formulating marketing strategy focussed on the tracking of physical activity emphasizing its relation with sleep score.



