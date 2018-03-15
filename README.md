# SAM Recovery Solution

## CloudFormation - SAM
This serverless application generates AMI backups from properly tagged EC2 using Lambda and DynamoDB w/ CloudWatch Events scheduling.

### Setup steps
1. Upload the zip files from /archive directory into an S3 bucket in your AWS account

### Ohio region only

### Installation Guide
1. <a href="https://console.aws.amazon.com/cloudformation/home#/stacks/new?stackName=SAM-Recovery&templateURL=https://s3-us-east-2.amazonaws.com/sam-recovery/cfn-templates/sam-recovery.template" target="_blank">![Launch](./img/launch-stack.png?raw=true "Launch")</a>
1. Click **Next** to proceed with the next step of the wizard.
1. Specify a name and all parameters for the stack.
1. Click **Next** to proceed with the next step of the wizard.
1. Click **Next** to skip the **Options** step of the wizard.
1. Check the **I acknowledge that this template might cause AWS CloudFormation to create IAM resources.** checkbox.
1. Check the **I acknowledge that this template might cause AWS CloudFormation to create IAM resources with custom names.** checkbox.
1. Click **Create Change Set** to generate the stack transformations.
1. Click **Execture** to start the stack creation. 
1. Wait until the stack reaches the state **CREATE_COMPLETE**

## Diagram
![Diagram](./img/sam-recovery.png?raw=true "Diagram")
