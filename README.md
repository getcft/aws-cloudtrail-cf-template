# aws-cloudtrail-cfn-template

## Description:

This solution creates a secure [AWS CloudTrail](https://aws.amazon.com/cloudtrail/) deployment for governance, compliance, operational auditing, and risk auditing of your AWS account.

The AWS CloudFormation template creates [KMS](https://aws.amazon.com/kms/) encryption keys for CloudTrail and [S3](https://aws.amazon.com/s3/), an encrypted S3 bucket, and enables CloudTrail for the account.

## Prerequisites:

* AWS account and environment configured with AWS Credentials
* IAM user with AWSCloudTrailFullAccess, AWSKeyManagementServicePowerUser, AWSCloudFormationReadOnlyAccess, AmazonS3FullAccess

## See how it works:

AWS Management Console

* Login to AWS Management Console
* Launch in CloudFormation cloudtrail.yml (from the repo you cloned)

CloudFormation Fields

* Stack name (Enter a name to associate to your AWS CloudTrail) then **Next**
* Continue choosing **Next** and then **Create**
