# AWS
AWS-Notes

**Understanding of AWS services**

Automation and efficiency- DevOps engineer main responsibilty 
Monitoring and observability -key components

AWS services for devops engineers
EC2-- 
VPC--Virtual private cloud -Securing AWS resources- components include like for ex- SG, CIDR blocks, Inbound and outbound rules.

EBS-volume- How to attach to EC2 instance -attach or detach.

S3-storage-widely used , it is encrypted by default now.

IAM-Identity and Access management--- permissions to users 

Cloud watch- monitoring on AWS services - tracks every action on AWS, also tracks compliance of the project is followed like Guardrails and best practices are being followed by all members.
              ex: if any developer creates EBS volume without encryption as it is in project compliance and as it is not follwed a mail notification can be sent to ask for the reason after
              checking from cloud watch logs.

LAMBDA- serverless compute - short actions, execute and tear down automatically. ex: above problem can be solved with Lamda function by encryting the EBS volume.

Cloud build services- for CI/CD.
            AWS code pipeline, code build, code deploy.

AWS configuration- configure some actions like guardrails one and take necessary actions for remediation.

Billing and costing - we can understand billing and costing of AWS services.

AWS KMS- to secure any resource we need secrets or keys. key managment service - to store cert, or any secure data.

Cloud trail- enable operational and risk audting, preserve logs for api calls for last 30 or more days as well.

AWS EKS- elaastic K8s service- **very imp**. it is managed service as ideally provided by k8S but below ECS is from AWS.

Other containers- Fargate, ECS- by AWS.

ELK- elastic search log stack kibana-- logging info and querying the data or info from it.
      to monitor errors and efficient logging.


      









            
            

