# MULTI-TIER SCALABLE AWS ARCHITECT USING DIFFERENT ACCOUNTS ( - 12 TIER ARCHITECT )
## ABSTRACT:
Created a project using 12 different services in three different regions each in three different accounts...

Three different regions used are:

1.N.Virginia ( us-east-1 )

2.Stockholm (eu-north-1)

3.Mumbai (ap-south-1)

This Project is a combination of multiple accounts with multiple services

which form a multi-tier architecture.

## AWS Services used in project are:
1.VPC

2.EC2

3.IAM ROLE

4.DYNAMO DB

5.CLOUD WATCH

6.SNS CONSOLE

7.S3

8.LAMBDA

9.SNAPSHOT

10.CLOUDSHELL

11.DOCKERHUB

12.RDS

## DETAILED INFO:
In first account :- Dynamo DB , CloudWatch, SNS are the services that are used,using those major services monitored the readcapacity of a instance and sent mail to the subscriber using sns...

In second account:- S3 buckets,DockerHub are used, using the S3 buckets data is stored using dockerhub being a third party tool some commands are executed to manipluate instance ,here lambda service is used to create,terminate the instance...

In third account:- RDS,Snapshot are used,database are used and stored by rds (using my sql database),snapshots are created for different instances ,here using cloud shell created ,terminated the instance...

Finally all three accounts are connected by peering connections...

Using above serivces created a 12-tier architect
