# JetSweep AWS Cost and Usage Report Configuration  

## About
The AWS Cost and Usage Reports contain a comprehensive report of your costs and usages in your AWS Account. JetSweep
has configured an AWS CloudFormation template that will configure an AWS Cost and Usage Report in the format that 
JetSweep requires for data review.  The AWS Cost and Usage Reports require an AWS S3 Bucket as a destination to store
the AWS Cost and Usage Reports.  This CloudFormation template will configure a new S3 Bucket and configure the AWS
Cost and Usage Report with the S3 Bucket as the report destination.   

## Deployment
Sign into the AWS Management Console and click the button below to launch the `jetsweep-aws-cur.json` AWS 
CloudFormation Template.  To open a new Tab, right click on `Launch Stack` and select "Open in new Tab.  
[![Stack](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/new?stackName=JetSweepCUR&templateURL=https://jetsweep.s3.amazonaws.com/jetsweep-aws-cur.template)

1.  Click Next on the AWS CloudFormation Create Stack page.  
![Alt text](https://github.com/bmacdonald-jetsweep/JetSweepCur/blob/main/images/cf-create-stack.png)  
2.  Enter a name for the S3 Bucket that will be the destination of the AWS Cost and Usage Report.  `Note: Choose a unique S3 Bucket Name that is not in use or the deployment will fail`.  Enter a name for the AWS Cost and Usage Report and then click Next.  
![Alt text](https://github.com/bmacdonald-jetsweep/JetSweepCur/blob/main/images/cf-stack-details.png)  
3.  On the Configure stack options page you can use the default settings and then click Next.  
![Alt text](https://github.com/bmacdonald-jetsweep/JetSweepCur/blob/main/images/cf-stack-options.png)  
4.  Click on Finish on the Review page to launch the template.  
![Alt text](https://github.com/bmacdonald-jetsweep/JetSweepCur/blob/main/images/cf-stack-review.png)  

The AWS CloudFormation template will take about 2-3 mins to deploy.  If the deployment is successful you will see `CREATE_COMPLETE`  
![Alt text](https://github.com/bmacdonald-jetsweep/JetSweepCur/blob/main/images/cf-create-complete.png)  

If you receive an error in AWS CloudFormation please contact support@jetsweep.co  

## AWS Cost and Usage Report  
Please allow at least 1-2 days for the AWS Cost and Usage Reports to run.  Then email your Sales or Technical contact at JetSweep 
if you are not sure who to send the AWS Cost and Usate Report to, email support@jetsweep.co 