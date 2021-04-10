![alt text](https://github.com/jcmc72/My100DaysOfCloud/blob/3b27fe5577fdf0b6c4c59fa9ad987e95d3f7c83a/Journey/003/ec2-spot-logo.jpg)

# DAY 3

## Introduction
Third lab on AWS

## Prerequisite
Connect to the AWS console, with administrator user.

## Use Case
In this lab, will be using Amazon Machine Images to launch Amazon EC2 Spot Instances, and configure "User Data" to add configurations in the instance from the launch.

## Cloud Research
https://aws.amazon.com/ec2/?ec2-whats-new.sort-by=item.additionalFields.postDateTime&ec2-whats-new.sort-order=desc

## Try yourself
### Steps
1. Open Console
2. Go to service EC2
3. Add and configure a basic instance
4. In the tab "Step 3: Configure Instance Details"
    Under the section --> Advanced Details 
    Under the subsection --> "User data", enter the following script, (which creates an HTML page served by Apache):
    ![alt text](https://github.com/jcmc72/My100DaysOfCloud/blob/3b27fe5577fdf0b6c4c59fa9ad987e95d3f7c83a/Journey/003/Lab-003-EC2-Spot-Instance-010-Step3.png)    
5. Connect to the EC2 instance
6. Verify the web server is up
9. Create and publish a test page

## ☁️ Cloud Outcome
Launch and configure a EC2 Spot Instance in the Amazon cloud.
	
1. In the Saving summary, you will save a total of 70% as compared to on-demand instances.
![alt text](https://github.com/jcmc72/My100DaysOfCloud/blob/3b27fe5577fdf0b6c4c59fa9ad987e95d3f7c83a/Journey/003/Lab-003-EC2-Spot-Instance-007-Savings-Summary.png)

2. In the Pricing history, you can modifiy the instance type and data range, to verify the cost upfront.
![alt text](https://github.com/jcmc72/My100DaysOfCloud/blob/3b27fe5577fdf0b6c4c59fa9ad987e95d3f7c83a/Journey/003/Lab-003-EC2-Spot-Instance-006-Pricing-History-03.png)

NOTE:
* The script to creat a web page fail, but the web server is OK with his configuration.
* Manual process to creat a web page, connect to the Instance and do the steps to do this requirement.

## Next Steps
Day 4.

## Social Proof
:-)
