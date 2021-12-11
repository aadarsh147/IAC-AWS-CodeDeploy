# IAC-AWS-CodeDeploy
Cloudformation template to create CodeDeploy and its components

Resources to be created under cloudformation- 

1. codeDeploy Application
2. codeDeploy Deployment Group
3. codeDeploy IAM Role
4. Instance Profile
5. 2 S3 buckets

Details - 

Compute Platform - EC2
Deployment Strategy - Allatonce (you can modify)
Template is parameterized - Pass following parameters based on your environment - 

CodeDeployApplicationName - Provide name you wish
DeploymentGroup - Provide name you wish
AutoScalingGroupName - Your Autoscaling group name
CodeDeployBucketName - provide unique name (bucket will be created as part of the teamplate)
ConfigBucketName - provide unique name (bucket will be created as part of the teamplate)

To Run - 

Go to AWS Console -> Services -> CodeDeploy -> import template -> pass variable
