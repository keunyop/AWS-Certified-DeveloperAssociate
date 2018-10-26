### 1. Can you configure an RDS Read Replica using CloudFormation templates?
Yes, when you create a new CloudFormation template.

AWS CloudFormation gives developers and systems administrators an easy way to create and manage collections of AWS resources.
You can now set Read Replicas for your databases with RDS when you create a new CloudFormation template. You can start using it with the sample template of CloudFormation.

> RDS: Relational Database Service

### 2. A user has configured ELB. Which of the below mentioned protocols the user can configure for ELB health checks while setting up ELB?
An ELB performs a health check on its instances to ensure that it diverts traffic only to healthy instances.
The ELB can perform a health check on HTTP, HTTPS, TCP and SSL protocols.

> ELB: Elastic Load Balancer

### 3. The AWS console for DynamoDB enables you to do all the following operations, except:
Import Data from other databases or from files.

### 4. You need to develop and run some new applications on AWS and you know that Elastic Beanstalk and CloudFormation can both help as a deployment mechanism for a broad range of AWS resourceaici statements best describes the differences between Elastic Beanstalk and CloudFormation?
CloudFormation is much more powerful than Elastic Beanstalk, because you can actually design and script custom resources.

AWS Elastic Beanstalk provides an environment to easily develop and run applications in the could. It is integrated with developer tools and provides a one-stop experience for you to manage the lifecycle of your applications. AWS CloudFormation is a convenient deployment mechanism for a broad range of AWS resources.

### 5. Which one of the following operations is NOT a DynamoDB operation?
BatchDeleteItem.

In DynamoDB, DeleteItem deletes a single item in a table by primary key, but BatchDeleteItem doesnt exist.

### 6. In Amazon EC2, which of the following is the type of monitoring data for Amazon EBS volumes that is available automatically in 5-minute periods at no charge?
Basic

Basic is the type of monitoring data (for Amazon EBS volumes) which is available automatically in 5 -minute periods at no charge called. 

### 7. ExamKiller (with AWS account ID 111122223333) has created 50 IAM users for its organization’s employees. ExamKiller wants to make the AWS console login URL for all IAM users as: https://examkiller.signin.aws.amazon.com/console/. How can this be configured?
It is not possible to have capital letters as a part of the alias name.

If a user wants the URL of the AWS IAM sign-in page to have the company name instead of the AWS account ID, he can create an alias for his AWS account ID. The alias must be unique across all Amazon Webservices products and contain only digits, lowercase letters, and hyphens.

> IAM: Identity and Access Management

> bucket: Amazone S3 bucket is a public cloud storage resource available in AWS.

### 8. When AutoScaling is launching a new instance based on conditions, which of the below mentioned policies will it follow?
Launch an instance in the AZ with the fewest instances.

AutoScaling attempts to distribute instances evenly between the Availability Zones that are enabled for the user’s AutoScaling group. Auto Scaling does this by attempting to launch new instances in the Availability Zone with the fewest instances.

### 9. How doesAmazon SQS allow multiple readers to access the same message queue without losing messages or processing them many times?
Amazon SQS queue has a configurable visibility timeout.

Every Amazon SQS queue has a configurable visibility timeout. For the designated amount of time after a message is read from a queue, it will not be visible to any other reader. As long as the amount of time that it takes to process the message is less than the visibility timeout, every message will be processed and deleted. In the event that the component processing the message fails or becomes unavailable, the message will again become visible to any component reading the queue once the visibility timeout ends. This allows you to have many components all reading messages from the same queue, with each working to process different messages.

> SQS : Simple Queue Service

### 10. A user has created an application which sends data to a log file. The server hosting the log files can be unavailable due to any reason. The user wants to make it so that whenever the log server is up it should be receiving the messages. Which of the below mentioned AWS services helps achieve this functionality?
AWS Simple Queue Service

Amazon Simple Queue Service (SQS) is a fast, reliable, scalable, and fully managed message queuing service. SQS provides a simple and cost-effective way to decouple the components of an application. The user can use SQS to transmit any volume of data without losing messages or requiring other services to always be available. Using SQS, the application has to just send the data to SQS and SQS transmits it to the log file whenever it is available.
