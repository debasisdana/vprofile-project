# Prerequisites
#
- JDK 1.8 or later
- Maven 3 or later
- MySQL 5.6 or later

# Technologies 
- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- MySQL
# Database
Here,we used Mysql DB 
MSQL DB Installation Steps for Linux ubuntu 14.04:
- $ sudo apt-get update
- $ sudo apt-get install mysql-server

Then look for the file :
- /src/main/resources/accountsdb
- accountsdb.sql file is a mysql dump file.we have to import this dump to mysql db server
- > mysql -u <user_name> -p accounts < accountsdb.sql

----------------------------------------------------------------------------------------------------

1. Login to AWS
2. Create Key-pairs
3. create security groups
4. Launch instance with user data (bash script)
5. Update IP to name mapping in route 53
6. Build Application from Source Code
7. Upload to S3 Bucket
8. Download artifact to Tomcat EC2 Instance
9. Setup ELB with HTTPS (cert from Amazon certification Manager)
10. Map ELB Endpoint to Website name in godaddy DNS
11. verify
12. Build Autoscaling Group for Tomcat Instace

--------------------------------------------------------------------------------------------------

1. Login to AWS
	 https://475585517635.signin.aws.amazon.com/console
	 AdminDdana/Belarani!123
	 AdminDebasis/Belarani!123
2. Create Key-pairs
	vprofile-key.pem
3. create security groups
	vprofile-ELB-SG --->Security Group for vprofile Load Balancer
	vprofile-app-sg --->Security group for tomcat ec2 instance
	vprofile-backend-sg --->Security group for vprofile backend services

4. Launch instance with user data (bash script)
5. Update IP to name mapping in route 53
6. Build Application from Source Code
7. Upload to S3 Bucket
8. Download artifact to Tomcat EC2 Instance
9. Setup ELB with HTTPS (cert from Amazon certification Manager)
10. Map ELB Endpoint to Website name in godaddy DNS
11. verify
12. Build Autoscaling Group for Tomcat Instace