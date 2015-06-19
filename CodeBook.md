The script run_analysis.R create the output as per reuiremnts of the course project

We will complete the following steps in following sequence

1. We will first merge the training and test data to create one data set, it will help to work on combined data
   1.1 Load X_train.txt ,  Y_train.txt and subject_train.txt
   1.2 Load X_test.txt ,  Y_test.txt and subject_test.txt
   1.2 combined data for X,Y and Subject
2.  we will load features file so can get all columns with mean and sd in their name
3. Get the data from comibed data set for desired columns
4. Load activity data
5. Put correct activities name
6. Get whole dataset
7. Get mean and avergae data
8. Ceate dataset

Variables
  Following variables will load data from downloaded file
    1. my_train_x
    2. my_train_y
    3. my_test_x
    4. my_test_y
    5. my_subject_train
    6. my_subject_test
    7. features, getting orrect name
  We merge the data and create the combined data set for each as following
    1. combined_x_data 
    2. combined_y_data 
    3. combined_subject_data
  Grep the mean and average data in following dataset
    mean_and_std_features
  We have combined data for x, y and subject
    my_whole_data
  Get avearge data by applying ddply() function into dataset
    my_average  
  Create desired data in my_average 

    