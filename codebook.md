# Codebook Values

The larger data set for the study, both training and test, included measurements
as described in UCL HAR Dataset/features.txt and features_info.txt

The Getting and Cleaning Data assignments asked for values on mean and sd only.
Those values are included in a section below labeled 'Code Values'.

The human readable values for subject activities were taken from UCL HAR Dataset/activities.txt

The values presented with each codes are averages of means and standard deviations
for various measure of movement, respectively, labeled with mean(), std(), and meanFreq().

#Transformations of fields

The fields presented in this dataset are means of means or standard deviations taken from the original dataset. The "subject_train.txt" and "subject_test.txt" files identified the
study participants, and these have been consolidated in the new dataset with the first column labeled "Subject."

"Task" is a remapping of the task activity codes given in "activity_labels.txt." 

All other fields retain their original titles and represent the averages of all observations for each subject, for each activity. 



##Code List
These can be connected to any of the original code entries and explanations in 
UCI HAR Dataset/ features_info.txt.

```

1	Subject
2	Task
3	tBodyAcc-mean()-X
4	tBodyAcc-mean()-Y
5	tBodyAcc-mean()-Z
6	tBodyAcc-std()-X
7	tBodyAcc-std()-Y
8	tBodyAcc-std()-Z
9	tGravityAcc-mean()-X
10	tGravityAcc-mean()-Y
11	tGravityAcc-mean()-Z
12	tGravityAcc-std()-X
13	tGravityAcc-std()-Y
14	tGravityAcc-std()-Z
15	tBodyAccJerk-mean()-X
16	tBodyAccJerk-mean()-Y
17	tBodyAccJerk-mean()-Z
18	tBodyAccJerk-std()-X
19	tBodyAccJerk-std()-Y
20	tBodyAccJerk-std()-Z
21	tBodyGyro-mean()-X
22	tBodyGyro-mean()-Y
23	tBodyGyro-mean()-Z
24	tBodyGyro-std()-X
25	tBodyGyro-std()-Y
26	tBodyGyro-std()-Z
27	tBodyGyroJerk-mean()-X
28	tBodyGyroJerk-mean()-Y
29	tBodyGyroJerk-mean()-Z
30	tBodyGyroJerk-std()-X
31	tBodyGyroJerk-std()-Y
32	tBodyGyroJerk-std()-Z
33	tBodyAccMag-mean()
34	tBodyAccMag-std()
35	tGravityAccMag-mean()
36	tGravityAccMag-std()
37	tBodyAccJerkMag-mean()
38	tBodyAccJerkMag-std()
39	tBodyGyroMag-mean()
40	tBodyGyroMag-std()
41	tBodyGyroJerkMag-mean()
42	tBodyGyroJerkMag-std()
43	fBodyAcc-mean()-X
44	fBodyAcc-mean()-Y
45	fBodyAcc-mean()-Z
46	fBodyAcc-std()-X
47	fBodyAcc-std()-Y
48	fBodyAcc-std()-Z
49	fBodyAcc-meanFreq()-X
50	fBodyAcc-meanFreq()-Y
51	fBodyAcc-meanFreq()-Z
52	fBodyAccJerk-mean()-X
53	fBodyAccJerk-mean()-Y
54	fBodyAccJerk-mean()-Z
55	fBodyAccJerk-std()-X
56	fBodyAccJerk-std()-Y
57	fBodyAccJerk-std()-Z
58	fBodyAccJerk-meanFreq()-X
59	fBodyAccJerk-meanFreq()-Y
60	fBodyAccJerk-meanFreq()-Z
61	fBodyGyro-mean()-X
62	fBodyGyro-mean()-Y
63	fBodyGyro-mean()-Z
64	fBodyGyro-std()-X
65	fBodyGyro-std()-Y
66	fBodyGyro-std()-Z
67	fBodyGyro-meanFreq()-X
68	fBodyGyro-meanFreq()-Y
69	fBodyGyro-meanFreq()-Z
70	fBodyAccMag-mean()
71	fBodyAccMag-std()
72	fBodyAccMag-meanFreq()
73	fBodyBodyAccJerkMag-mean()
74	fBodyBodyAccJerkMag-std()
75	fBodyBodyAccJerkMag-meanFreq()
76	fBodyBodyGyroMag-mean()
77	fBodyBodyGyroMag-std()
78	fBodyBodyGyroMag-meanFreq()
79	fBodyBodyGyroJerkMag-mean()
80	fBodyBodyGyroJerkMag-std()
```
