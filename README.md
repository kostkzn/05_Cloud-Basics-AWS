# AWS Cloud Basics Topic

## 1. Read the terms of Using the [AWS Free Tier](https://docs.aws.amazon.com/en_us/awsaccountbilling/latest/aboutv2/billing-free-tier.html) and the ability to control their own costs.

Useful topics from the link:
1. [Tracking your AWS Free Tier usage](https://docs.aws.amazon.com/en_us/awsaccountbilling/latest/aboutv2/tracking-free-tier-usage.html)
2. [Avoiding unexpected charges after the AWS Free Tier](https://docs.aws.amazon.com/en_us/awsaccountbilling/latest/aboutv2/billing-free-tier.html#avoid-charges-after-free-tier)
3. How to identify account’s active resources:

![Billing control](pics/01.jpg)

## 2. [Register with AWS](https://portal.aws.amazon.com/billing/signup?redirect_url=https%3A%2F%2Faws.amazon.com%2Fregistration-confirmation#/start) (first priority) or alternatively, you can request access to courses in [AWS Academy](https://aws.amazon.com/training/awsacademy/member-list/) if you are currently a student of certain University.

![AWS account registered](pics/02.jpg)

## 3. Find the [hands-on tutorials](https://aws.amazon.com/ru/getting-started/hands-on/?awsf.getting-started-category=category%23compute&awsf.getting-started-content-type=content-type%23hands-on&?e=gs2020&p=gsrc&awsf.getting-started-level=*all) and [AWS Well-Architected Labs](https://www.wellarchitectedlabs.com/) for your AWS needs. Explore list of step-by-step tutorials for deferent category. Use, repeat as many as you can and have fun))

![Hands-on tutorials](pics/03.jpg)

![AWS Well-Architected Labs](pics/03-1.jpg)

## 4. Register and pass courses on [AWS Educate](https://www.awseducate.com/). Filter by checking Topic Cloud Computing and Foundational Level. Feel free to pass more.

![AWS Educate registered](pics/04.jpg)

## 5. Register and pass free courses on [AWS Skillbuilder](https://explore.skillbuilder.aws/learn). AWS Cloud Practitioner Essentials: Core Services, AWS Cloud Practitioner Essentials: Cloud Concepts. Try AWS Cloud Quest: Cloud Practitioner.

![AWS Skillbuilder registered](pics/05.jpg)

## 6. Pass free courses on [Amazon qwiklabs](https://amazon.qwiklabs.com/)

![qwiklabs registered](pics/06.jpg)

## 7. Review [Getting Started with Amazon EC2](https://aws.amazon.com/ec2/getting-started/?nc1=h_ls). Log Into Your AWS Account, Launch, Configure, Connect and Terminate Your Instance. Do not use Amazon Lightsail. It is recommended to use the t2 or t3.micro instance and the CentOS operating system.

![Instance created](pics/07.jpg)

![Instance connected](pics/07-1.jpg)

## 8. Create a snapshot of your instance to keep as a backup.

![Step 1](pics/08.jpg)

![Step 2](pics/08-1.jpg)

![Snapshot result](pics/08-2.jpg)

## 9. Create and attach a `Disk_D` (EBS) to your instance to add more storage space. Create and save some file on `Disk_D`

![Attaching EBS volume to instance](pics/09.jpg)

![Coping files to EBS volume](pics/09-1.jpg)

## 10. Launch the second instance from backup.

![Creating AMI from snapshot](pics/10.jpg)

![Deployed instance from custom AMI](pics/10-1.jpg)

## 11. Detach `Disk_D` from the 1st instance and attach `Disk_D` to the new instance.

![Attaching EBS volume to new instance](pics/11.jpg)

![Mounting EBS volume](pics/11-1.jpg)

## 12. Review the 10-minute [example](https://aws.amazon.com/getting-started/hands-on/get-a-domain/?nc1=h_ls). Explore the possibilities of creating your own domain and domain name for your site. Note, that Route 53 not free service. Alternatively you can free register the domain name *.PP.UA and use it

![Registered *.PP.UA](pics/12.jpg)

## 13. Launch and configure a WordPress instance with Amazon Lightsail [link](https://aws.amazon.com/getting-started/hands-on/launch-a-wordpress-website/?trk=gs_card)

![Lightsail dashboard](pics/13.jpg)

![WordPress Hello World](pics/13-1.jpg)

## 14. Review the 10-minute [Store and Retrieve a File](https://aws.amazon.com/getting-started/hands-on/backup-files-to-amazon-s3/). Repeat, creating your own repository

![s3 Uploaded](pics/14.jpg)

## 15. Review the 10-minute [example](https://aws.amazon.com/getting-started/hands-on/backup-to-s3-cli/?nc1=h_ls) Batch upload files to the cloud to Amazon S3 using the AWS CLI. Create a user AWS IAM, configure CLI AWS and upload any files to S3

![s3 cli workflow](pics/15.jpg)

## 16. Review the 10-minute [example](https://aws.amazon.com/getting-started/hands-on/deploy-docker-containers/?nc1=h_ls) Deploy Docker Containers on Amazon Elastic Container Service (Amazon ECS). Repeat, create a cluster, and run the online demo application or better other application with custom settings

![Active cluster](pics/16.jpg)

![Active app](pics/16-1.jpg)

## 17. [Run a Serverless "Hello, World!"](https://aws.amazon.com/getting-started/hands-on/run-serverless-code/?nc1=h_ls) with AWS Lambda

![Execution results](pics/17.jpg)

## 18. Create a static website on Amazon S3, publicly available ([link1](https://docs.aws.amazon.com/AmazonS3/latest/dev/HostingWebsiteOnS3Setup.html) or [link2](https://docs.aws.amazon.com/AmazonS3/latest/dev/website-hosting-custom-domain-walkthrough.html) - using a custom domain registered with Route 53). Post on the page your own photo, the name of the educational program (EPAM Cloud&DevOps Fundamentals Autumn 2022), the list of AWS services with which the student worked within the educational program or earlier and the full list with links of completed labs (based on [tutorials](https://aws.amazon.com/getting-started/hands-on/?awsf.getting-started-content-type=content-type%23hands-on&?e=gs2020&p=gsrc) or [qwiklabs](https://amazon.qwiklabs.com/). Provide the link to the website in your report and СV

Link to [kostkzn.pp.ua](http://kostkzn.pp.ua)

![Static website](pics/18.jpg)
