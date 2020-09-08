# Coursera_Capstone
Final Report

# Introduction 

The world as a whole suffers due to car accidents, including the USA. In this report the selected data is from the city of Seattle. According to the National Highway Traffic Safety Administration of the USA and 2017 WSDOT data, a car accident occurs every 4 minutes and a person dies due to a car crash every 20 hours in the state of Washington while Fatal crashes went from 508 in 2016 to 525 in 2017, resulting in the death of 555 people. The project tried to predict severity of accidents in terms of human fatality, traffic delay, property damage, or any other type of accident bad impact. 


## Stakeholders:

The target audience of the project is local Seattle government, police, rescue groups, car drivers, and car insurance companies. The model and its results are going to provide some advice for the target audience to make insightful decisions for reducing the number of accidents and injuries for the city


# Data Understanding

The data was collected by the Seattle Police Department and Accident Traffic Records Department from 2004 to present.Our predictor or target variable will be 'SEVERITYCODE' because it measure the severity of an accident from 0 to 3 within the dataset.The variable can take the following values:

• 3—fatality, 2b—serious injury, 2—injury, 1—prop damage, 0—unknown

The Dataset contains 221.266 records and 40 columns.

The distribution of the records is the following:

Property Damage Only Collision    137485 , Injury Collision                   58698, Unknown                            21636, Serious Injury Collision            3098, Fatality Collision                   349

Finally, because of the existence of null values in some records, the data needs to be preprocessed before any further processing.
