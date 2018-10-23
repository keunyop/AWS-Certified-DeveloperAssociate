---


---

<p>AWS-Cate<br>
AWS-Certified-DeveloperAssociate Study?<br>
Yes, when you create a new CloudFormation template.<br>
AWS CloudFormation gives developers and systems administrators an easy way to create and manage collections of AWS resources.<br>
You can now set Read Replicas for your databases with RDS when you create a new CloudFormation template. You can start using it with the sample template of CloudFormation.</p>
<blockquote>
<p>RDS:  Relational Database Service</p>
</blockquote>
<h3 id="a-user-has-configured-elb.-which-of-the-below-mentioned-protocols-the-user-can-configure-for-elb-health-checks-while-setting-up-elb">2. A user has configured ELB. Which of the below mentioned protocols the user can configure for ELB health checks while setting up ELB?</h3>
<p>An ELB performs a health check on its instances to ensure that it diverts traffic only to healthy instance</p>
<p>s.<br>
The ELB can perform a health check on HTTP, HTTPS, TCP and SSL protocols.</p>
<blockquote>
<p>ELB: Elastic Load Balancer</p>
</blockquote>
<h3 id="the-aws-console-for-dynamodb-enables-you-to-do-all-the-following-operations-except">3. The AWS console for DynamoDB enables you to do all the following operations, except:</h3>
<p>Import Data from other databases or from files.</p>
<h3 id="you-need-to-develop-and-run-some-new-applications-on-aws-and-you-know-that-elastic-beanstalk-and-cloudformation-can-both-help-as-a-deployment-mechanism-for-a-broad-range-of-aws-resourceaici-statements-best-describes-the-differences-between-elastic-beanstalk-and-cloudformation">4. You need to develop and run some new applications on AWS and you know that Elastic Beanstalk and CloudFormation can both help as a deployment mechanism for a broad range of AWS resourceaici statements best describes the differences between Elastic Beanstalk and CloudFormation?</h3>
<p>CloudFormation is much more powerful than Elastic Beanstalk, because you can actually design and script custom resources.<br>
AWS Elastic Beanstalk provides an environment to easily develop and run applications in the could. It is integrated with developer tools and provides a one-stop experience for you to manage the lifecycle of your applications. AWS CloudFormation is a convenient deployment mechanism for a broad range of AWS resources.</p>
<h3 id="which-one-of-the-following-operations-is-not-a-dynamodb-operation">5. Which one of the following operations is NOT a DynamoDB operation?</h3>
<p>BatchDeleteItem.<br>
In DynamoDB, DeleteItem deletes a single item in a table by primary key, but BatchDeleteItem doesnt exist.<br>
nmazon2which f hefollowingisthetypeofmonitoringdataformazon volumeshisavailableautomaticallyin5-minuteperiodsatno charge<br>
B<br>
Bai is te e o itorin aa o maon  olumes whic is availale autoticay nminute eios at no arge calledbcke: atc lock Storeoue</p>
<h3 id="examkiller-with-aws-account-id-111122223333-has-created-50-iam-users-for-its-organizations-employees.-examkiller-wants-to-make-the-aws-console-login-url-for-all-iam-users-as-httpsexamkiller.signin.aws.amazon.comconsole.-how-can-this-be-configured">7. ExamKiller (with AWS account ID 111122223333) has created 50 IAM users for its organization’s employees. ExamKiller wants to make the AWS console login URL for all IAM users as: <a href="https://examkiller.signin.aws.amazon.com/console/">https://examkiller.signin.aws.amazon.com/console/</a>. How can this be configured?</h3>
<p>It is not possible to have capital letters as a part of the alias name.</p>
<p>If a user wants the URL of the AWS IAM sign-in page to have the company name instead of the AWS account ID, he can create an alias for his AWS account ID. The alias must be unique across all Amazon Webservices products and contain only digits, lowercase letters, and hyphens.</p>
<blockquote>
<p>IAM: Identity and Access Management<br>
bucket: Amazone S3 bucket is a public cloud storage resource available in AWS.</p>
</blockquote>
<h3 id="when-autoscaling-is-launching-a-new-instance-based-on-conditions-which-of-the-below-mentioned-policies-will-it-follow">8. When AutoScaling is launching a new instance based on conditions, which of the below mentioned policies will it follow?</h3>
<p>Launch an instance in the AZ with the fewest instances.</p>
<p>AutoScaling attempts to distribute instances evenly between the Availability Zones that are enabled for the user’s AutoScaling group. Auto Scaling does this by attempting to launch new instances in the Availability Zone with the fewest instances.</p>

### 9. How does Amazon SQS allow multiple readers to access the same message queue without losing messages or processing them many times?
Amazon SQS queue has a configurable visibility timeout.

Every Amazon SQS queue has a configurable visibility timeout. For the designated amount of time after a message is read from a queue, it will not be visible to any other reader. As long as the amount of time that it takes to process the message is less than the visibility timeout, every message will be processed and deleted. 
> SQS : Simple Queue Service
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTY4Njc1ODM5LC0xMDEwMTM3MjA3XX0=
-->