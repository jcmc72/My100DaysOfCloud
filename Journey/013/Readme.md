![alt text](https://github.com/jcmc72/My100DaysOfCloud/blob/47237c3dafea6d46af67850c52a4e0ca984de6e0/Journey/013/Aws-S3-Acces-With-Roles.png)

# DAY 13

## Introduction
Thirteenth lab on AWS

## Prerequisite
Connect to the AWS console, with administrator user

## Use Case
You through the steps to create an AWS S3 bucket and demonstrates how to access the bucket using AWS CLI commands from EC2 instance and IAM roles

## Cloud Research
https://aws.amazon.com/premiumsupport/knowledge-center/ec2-instance-access-s3-bucket/

## Try yourself
### Steps
1. Create an IAM role with S3 full access
2. Create an EC2 instance and attach the S3 role created in the first step
3. Create an S3 bucket and upload some files to the bucket
4. Access the bucket using AWS CLI via our EC2 instance
5. List the objects in the S3 bucket using the AWS CLI from the EC2 instance

## ☁️ Cloud Outcome
* You have successfully created an IAM role to access S3 by granting S3 full access
* You have created an EC2 instance with an IAM role attached
* You have uploaded a file to an S3 bucket via CLI from the EC2 instance
* You have uploaded a file to an S3 bucket from the AWS console

File in S2 bucket
![alt text](https://github.com/jcmc72/My100DaysOfCloud/blob/47237c3dafea6d46af67850c52a4e0ca984de6e0/Journey/013/Lab-013-S3-Access-With-Roles-01.png)

Created rol
![alt text](https://github.com/jcmc72/My100DaysOfCloud/blob/47237c3dafea6d46af67850c52a4e0ca984de6e0/Journey/013/Lab-013-S3-Access-With-Roles-02.png)

Assign role to EC2 instance
![alt text]()

Access S3 via AWS CLI from EC2 instance, create and move new objects
![alt text](https://github.com/jcmc72/My100DaysOfCloud/blob/47237c3dafea6d46af67850c52a4e0ca984de6e0/Journey/013/Lab-013-S3-Access-With-Roles-03.PNG)

## Next Steps
Day 14

## Social Proof
:-)

## 016-Accessing S3 with AWS IAM Roles.pdf
