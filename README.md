### Alpha Version:
- Developed an interactive web page to allow users to view nearby recommended restaurants based on their preferences.
- Wrote Java servlet service to fetch restaurant data from Yelp API.
- Utilized [**MySQL**](../blob/master/src/db/MySQLDBConnection.java)/[**MongoDB**](../blob/master/src/db/MongoDBConnection.java) to store user preference and restaurant information.
- Designed and implemented a filtering and sorting algorithm to identify restaurant based on similar users’ preferences.
- Improved precision of recommendations by sorting restaurants by star rating, distance from user, and category. 

### Beta Version: (Migrate the application to the AWS)
- Built an auto-recovery, fully backup, secure, elastic and Dockerized application on AWS and GCP.
- Wrote Java servlet service to fetch restaurant data from Yelp API.
- Performed auto-scaling feature by auto-scaling group and Application Load Balancer for better performance (scalable).
- Set CloudWatch to monitor CPU utilization and provide the details and threshold for the alarm.
- Hosted the relational database in AWS RDS for stateless to store user preference and restaurant information.
- Stored the application files and server log files in the S3 for backup and further analysis (ELK).
