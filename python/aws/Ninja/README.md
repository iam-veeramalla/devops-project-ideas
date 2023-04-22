# AWS Ninja

## Project Summary 

"AWS Ninja" is a governance project that uses Lambda functions to optimize and manage AWS resources. With AWS Ninja, you can easily govern your AWS resources, automate
compliance checks, and enforce policies. By leveraging Lambda functions, AWS Ninja enables you to ensure the security, compliance, and cost-efficiency of your AWS 
infrastructure. Whether you're a small startup or a large enterprise, AWS Ninja can help you streamline your AWS governance and improve your operations.

## Project Scope

- Fix not properly secured S3 buckets: Lambda functions can be used to monitor S3 bucket access and enforce security policies, such as preventing public access, 
encrypting data at rest, and logging all access activity.

- Fix not optimized EC2 instances: Lambda functions can be used to monitor CPU utilization and other metrics of your EC2 instances, and automatically adjust the
 instance size or capacity based on the workload. This can help optimize performance and reduce costs.

- Fix not automated backups and disaster recovery: Lambda functions can be used to schedule backups and automate disaster recovery processes, such as copying data
 to a backup S3 bucket or launching a new EC2 instance in case of a failure.

- Fix not automated routine tasks: Lambda functions can be used to automate routine tasks, such as database backups, log analysis, and file processing. This can help
 reduce manual effort and improve efficiency.

- Fix IAM permissions and roles properly: Lambda functions can be used to enforce IAM policies and roles, such as granting least privilege access and rotating access keys. 
This can help improve security and compliance.

## High Level Design

![Screenshot 2023-04-22 at 8 07 51 PM](https://user-images.githubusercontent.com/43399466/233791082-464d1417-6bfb-46ff-bb32-697a605a1a28.png)
