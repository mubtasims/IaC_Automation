# IaC_Automation

This IaC Automation project consists of IaC constructed by Terraform, Jenkins, and AWS EC2. A Terraform script is generated which builds an EC2 in the AWS platform and is also triggered by Jenkins.

A Jenkinsfile, which sits on GitHub, is configured from Jenkins which consists of the necessary AWS credentials configured from the AWS platform through IAM, along with a Terraform script that contains IaC codes to build the EC2 on the AWS platform. The Jenkinsfile is then triggered by buidling a job, which provides an end to end view of the infrasturecture as it builds.
