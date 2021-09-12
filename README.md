## Order-Sales-Analysis-with-Athena

![image](https://user-images.githubusercontent.com/29160965/132944250-6b083ae1-4843-4db0-b907-9b9e98f91ead.png)



In this project I place myself in the position of a Data Engineer with a responsibilities spanning different data professions like Business Intelligence Analyst, Data Analyst, Data Scientist ..
I took a time to develop business questions that management could be needing answers to. The data is customer data collected from a fictious company Nick'sGlo.Inc. As a data specialist, I wanted to harnes the internal data information for performance analysis. The analysis could help me understand what next? ‘what if?’ and ‘what’s out there?’ kind of questions. 
 

### Data ingection process in in Amazon Console 



1.	On the Amazon Management Console, create two S3 buckets one storing the data and the other empty bucket to receive Athena query results.
2.	 Copy the data bucket path in the S3 bucket since it will be required when specifying the data source. 
3.	At Athena go at the settings and specify the output path pointing to the empty result bucket.
4.	Then connect data source using AWS Glue data catalog then set up a crawler to retrieve schema information automatically. 
5.	Label the crawler name and the Data source, choose data store as S3 then specify the path of the data bucket in S3. 
6.	Thereafter, create IAM role and Schedule the crawler to run on demand. 
7.	On databases create new or use the default (this is database visible at Athena side pane) 
8.	Preview the crawler settings and finish the process, then run the crawler to start migrating S3 data to Athena. 
9.	On refreshing AWS Athena you should see the one table with the filename created then start performing queries. The results of the queries will be stored in the result bucket in S3.   
  

