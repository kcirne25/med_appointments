# Medical Appointments analysis - Brazil 2016 

Project created to analyze features and trends of No-show appointments in Brazil in 2016. It is pssible to verify all the data analysis process through the project: question, wrangle, explore, draw conclusions and communicate results through charts.

The project get insights about the questions below:

* Age is related to missing an appointment?
* Gender is related to going or missing an appointment?

## Dataset

The dataset was extracted from Kaggle in the csv format and has more than 110k appointments recorded. The file has data of Patient ID, Appointment ID, Gender of patient, Appointment day, Age, Neighbourhood, Scholarship, SMS_received, Handcap, if a patient attended to the appointment or not (No-show) and data of the current health condition of a patient, expressed through Hipertension, Diabetes and Alcoholism. Most columns conditions are expressed with a binary digit, where "1" has the same meaning as "Yes" and "0" means "No".

## Packages

The project was developed in a Jupyter Notebook using the following python libraries: `Pandas`, `Matplotlib` and `Seaborn` and the magic function `%matplotlib inline`. 

## Structure

The project is divided in 3 parts:

* The first one, presents an initial analysis of the dataset, through the wrangling and exploring processes. After analyzing the dataset, data was cleaned to preserve only relevant features to be used in the project.

* The second part shows a visual analysis by plotting results and getting insights about the questions we want to answer.

* On the last part of the project, some conclusions and an analysis about its limitations are made.

## Conclusions

It is possible to verify through the analysis that gender isn't a relevant factor in no-show appointment. Males and females tend to go to appointments in almost the same proportion in each "gender group".

People that have less than 2 years are more susceptible to have a scheduled appointment and attend to medical appointments more often. The number of attendance to appointments declines through the year. Probably because there are fewer old people in the dataset.

## Limitations

The project could have one particular ingredient that could make it more interesting: statistical analysis.

The gender bar chart doesn't appear to have the same total of people than the previous chart (the blue one), because in the second case the charts were overlaid. Also, this kind of plot changes the color of one plotted feature, which could result in a confusion of the analysis.

The line graph to analyze the trend of attendance shows incorrect labels. It needs to be corrected.

For future work, I also aim to make an analysis through ML models.

Enjoy!
