# End to end website - EC2 instance
#
1) create RDS aurora
> free tier / public


2) create S3 bucket

# 3) ec2 - ubuntu

# 4) ssh 

# 5) apt-get update 
# 6) apt-get install mysql-client - (allow connect to rds)

# 7) connect to RDS from ec2 
# connect to endpoint - employee.cfjddbvftwzq.us-east-1.rds.amazonaws.com

# - show databases;
# - create database employee;
# empid varchar(20),
# fname varchar(20),
# ****

# 8) Add Mysql inbound rule for security group

9_ when enter information will be stored in RDS database.

10) upload code to Github repository

11) clone code to ec2 instance
12) install necessary dependencies - 

<code> sudo apt-get update
# For Sql-client
sudo apt-get install mysql-client

# For python and related frameworks

sudo apt-get install python3
sudo apt-get install python3-flask
sudo apt-get install python3-pymysql
sudo apt-get install python3-boto3

# for running application
sudo python3 Empapp.py

</code>

13) Create AWS role allowing Administrator access to allow S3 access to EC2 instance / attach role to EC2 

