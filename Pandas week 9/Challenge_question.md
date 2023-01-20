## Question
----
##### Create the data

raw_data_1 = { 'subject_id': ['1', '2', '3', '4', '5'], 'first_name': ['Alex', 'Amy', 'Allen', 'Alice', 'Ayoung'], 'last_name': ['Anderson', 'Ackerman', 'Ali', 'Aoni', 'Atiches']}

raw_data_2 = { 'subject_id': ['4', '5', '6', '7', '8'], 'first_name': ['Billy', 'Brian', 'Bran', 'Bryce', 'Betty'], 'last_name': ['Bonder', 'Black', 'Balwner', 'Brice', 'Btisan']}

raw_data_3 = { 'subject_id': ['1', '2', '3', '4', '5', '7', '8', '9', '10', '11'], 'test_id': [51, 15, 15, 61, 16, 14, 15, 1, 61, 16]}

**Challenge Questions**

1.    Assign each to a variable called data1, data2, data3.
2.    Join data1 and data2 along rows and assign all_data.
3.    Join the two dataframes along columns and assign to all_data_col.
4.    Print data3.
5.    Merge all_data and data3 along the subject_id value.
6.    Merge only the data that has the same 'subject_id' on both data1 and data2.
7.    Merge all values in data1 and data2, with matching records from both sides where available.
