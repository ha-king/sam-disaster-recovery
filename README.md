# SAM Recovery Solution

## CloudFormation - SAM
This serverless application generates AMI backups from properly tagged EC2 using Lambda and DynamoDB w/ CloudWatch Events scheduling.

#### Ohio region only

### Installation Guide
1. <a href="https://console.aws.amazon.com/cloudformation/home#/stacks/new?stackName=VPC-Kubernetes&templateURL=https://s3-us-east-2.amazonaws.com/inf-kube-setup/cfn-templates/nested-master.template" target="_blank">![Launch](./img/launch-stack.png?raw=true "Launch")</a>
1. Click **Next** to proceed with the next step of the wizard.
1. Specify a name and all parameters for the stack.
1. Click **Next** to proceed with the next step of the wizard.
1. Click **Next** to skip the **Options** step of the wizard.
1. Check the **I acknowledge that this template might cause AWS CloudFormation to create IAM resources.** checkbox.
1. Click **Create Change Sets** to generate the stack transformations.
1. Click **Create** to start the stack creation. 
1. Wait until the stack reaches the state **CREATE_COMPLETE**
