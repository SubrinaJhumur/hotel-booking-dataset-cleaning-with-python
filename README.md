# hotel-booking-dataset-cleaning-with-python
the link of the dataset: https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand.
At first import pandas for data loading and data cleaning.
wWith pandas library the dataset loading.
After loading the dataset show the first 5 rows of the dataset.
With the code of data.shape we can check the total number of rows and columns present in the dataset.
Now check the persent of data missing.
now check the duplicate values present in the dataset.
After checking the duplicates values now remove the duplicate values from the dataset.
check the unique values in the agent column.
filling the na values of the agent column with -1 values.
drop the missing values present in the 'num_of_child' column.
missing values in the country column is filled with the 'unknown' word.
Now check is there any null values present in the dataset.
converting the 'is_canceled' and 'is_repeated_guest' column into boolean values and 'num_of_child' and 'agent' column into int values.
after converting the data types check the data type.
creating a column for 'lead_time' to a 'lead_time_binned' column.
check the unique values of the hotel column.
rename the 'adults', 'children','babies' columns in the last step.
