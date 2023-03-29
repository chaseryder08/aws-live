<!-- # # end to end website
# * create RDS aurora
# * free tier
# * public


# 2) create bucket

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

# // -->

sudo apt-get update
# For Sql-client
sudo apt-get install mysql-client

# For python and related frameworks

sudo apt-get install python3
sudo apt-get install python3-flask
sudo apt-get install python3-pymysql
sudo apt-get install python3-boto3

# for running application
sudo python3 Empapp.py
