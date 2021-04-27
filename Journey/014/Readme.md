![alt text](https://github.com/jcmc72/My100DaysOfCloud/blob/477ee8ae9b8122f7fb8c010bda49cd3a178914db/Journey/014/Aws-Amazon-CloudFront.png)

# DAY 14

## Introduction
Fourteen lab on AWS

## Prerequisite
Connect to the AWS console, with administrator user

## Use Case
This lab walks you through to Amazon CloudFront creation and working. In this lab you will create an Amazon CloudFront distribution. It will distribute a publicly accessible image file stored in an Amazon S3 bucket

## Cloud Research


## Try yourself
### Steps
1. Log into AWS Management Console
2. Create a S3 Bucket and upload an image to the sample S3 bucket provided
3. Create Custom Error pages
4. Make the image Publicly accessible
5. Create a new Amazon CloudFront distribution
6. Link the CloudFront distribution to serve the image in S3 bucket
7. Test the distribution
8. Update Distribution with Custom Error Pages and test
9. Create a Geo-Restriction
10. Test Geo-Restriction

## ☁️ Cloud Outcome
* You have successfully created an Amazon CloudFront distribution and published an image through CloudFront
* You learned how to configure Custom Error Pages for CloudFront Distribution
* You learned how to configure restrictions based on Geo-location

S3 with folder and image
![alt text](https://github.com/jcmc72/My100DaysOfCloud/blob/477ee8ae9b8122f7fb8c010bda49cd3a178914db/Journey/014/Lab-014-Amazon-CloudFront-01.png)

S3 with folder /CustomErrors and html files to manage these errors
![alt text](https://github.com/jcmc72/My100DaysOfCloud/blob/477ee8ae9b8122f7fb8c010bda49cd3a178914db/Journey/014/Lab-014-Amazon-CloudFront-02.png)

S3 content haven't public access
![alt text](https://github.com/jcmc72/My100DaysOfCloud/blob/477ee8ae9b8122f7fb8c010bda49cd3a178914db/Journey/014/Lab-014-Amazon-CloudFront-03.PNG)

S3 content have public access
![alt text](https://github.com/jcmc72/My100DaysOfCloud/blob/477ee8ae9b8122f7fb8c010bda49cd3a178914db/Journey/014/Lab-014-Amazon-CloudFront-04.PNG)

S3 content accessed from CloudFront
![alt text](https://github.com/jcmc72/My100DaysOfCloud/blob/477ee8ae9b8122f7fb8c010bda49cd3a178914db/Journey/014/Lab-014-Amazon-CloudFront-05.PNG)

Error page to manage error 404 
![alt text](https://github.com/jcmc72/My100DaysOfCloud/blob/477ee8ae9b8122f7fb8c010bda49cd3a178914db/Journey/014/Lab-014-Amazon-CloudFront-06.PNG)

Error page to manage error 403, blocked content in this country
![alt text](https://github.com/jcmc72/My100DaysOfCloud/blob/477ee8ae9b8122f7fb8c010bda49cd3a178914db/Journey/014/Lab-014-Amazon-CloudFront-07.PNG)

## Next Steps
Day 15

## Social Proof
:-)

## 018-Introduction to Amazon CloudFront.pdf


## S3 URL
## https://bck-lab14-test-cloudfront-27042021.s3.amazonaws.com/culture-1536x961.png

## CloudFront
## d3qjil6dpas77g.cloudfront.net/culture-1536x961.png
