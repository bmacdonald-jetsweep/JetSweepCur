# JetSweep AWS Cost and Usage Report Configuration  

## About
The AWS Cost and Usage Reports contain a comprehensive report of your costs and usages in your AWS Account. JetSweep
has configured an AWS CloudFormation template that will configure an AWS Cost and Usage Report in the format that 
JetSweep requires for data review.  The AWS Cost and Usage Reports require an AWS S3 Bucket as a destination to store
the AWS Cost and Usage Reports.  This CloudFormation template will configure a new S3 Bucket and configure the AWS
Cost and Usage Report with the S3 Bucket as the report destination.   

## Deployment
Sign into the AWS Management Console and click the button below to launch the `jetsweep-aws-cur.json` AWS 
CloudFormation Template.  
[![Stack](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/new?stackName=JetSweepCUR&templateURL=https://jetsweep.s3.amazonaws.com/jetsweep-aws-cur.template)

1.  Click Next on the AWS CloudFormation Create Stack page.  
![Alt text](https://github.com/bmacdonald-jetsweep/JetSweepCur/blob/main/images/cf-create-stack.png)