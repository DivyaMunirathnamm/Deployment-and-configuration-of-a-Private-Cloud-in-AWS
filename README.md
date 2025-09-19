# EX - 4 Deployment-and-configuration-of-a-Private-Cloud-in-AWS
# Name: DIVYA M
# Reg no: 212223040043
# Aim:
To set up of a Private Cloud in AWS.

Setting up of a private cloud in AWS:
Setting up a private cloud within AWS, also known as a Virtual Private Cloud (VPC), involves creating a logically isolated virtual network that you can use to launch AWS resources. This provides you with full control over your virtual networking environment, including resource placement, connectivity, and security. Amazon Virtual Private Cloud (Amazon VPC) gives you full control over your virtual networking environment, including resource placement, connectivity, and security. Get started by setting up your VPC in the AWS service console. Next, add resources to it such as Amazon Elastic Compute Cloud (EC2) and Amazon Relational Database Service (RDS) instances. Finally, define how your VPCs communicate with each other across accounts, Availability Zones, or AWS Regions.

# Procedure:
Plan Your VPC:

● Determine your needs: Define your use case, including application requirements, security needs, and compliance standards.

● Plan IP address ranges: Choose appropriate IP address ranges for your VPC and subnets to avoid conflicts.

● Select Availability Zones: Decide which Availability Zones (AZs) you'll use for your resources, considering redundancy and performance.

● Plan internet connectivity: Determine if you need public internet access and how to configure it.

● Define security: Plan your security groups, network ACLs, and access controls to ensure a secure environment.

Create Your VPC:

• Sign in to AWS Management Console: Access the VPC console and navigate to the VPC dashboard.

• Choose "Create VPC": Initiate the VPC creation process.

• Configure VPC details: Enter the VPC name, CIDR block, Availability Zones, and other necessary settings.

• Create subnets: Define subnets within your VPC to isolate different parts of your network.

• Create route tables: Specify how traffic is routed within and outside the VPC.

• Create security groups: Define access control rules for your resources

Deploying Resources:

• Launch EC2 instances: Create and launch virtual machines within your VPC.

• Set up RDS instances: Deploy databases for your applications.

• Configure networking: Connect your resources to the appropriate subnets, security groups, and route tables.

• Deploy other AWS services: Integrate other services like S3 for storage and Lambda for serverless computing.

4.Managing and Monitoring:

• Use AWS CloudWatch: Monitor your VPC and resources for performance and health.

• Configure logging and auditing: Track access and activity within your VPC for security and compliance.

• Implement security best practices: Regularly review and update your security configuration.

• Scale and adjust as needed: Adjust your VPC infrastructure to meet changing demands.

# Snap Shots:

1: Create VPC 
<img width="956" height="566" alt="image" src="https://github.com/user-attachments/assets/4a32e14f-145e-460c-8886-ed7639506750" />


2: Configuring Subnets 
<img width="971" height="494" alt="image" src="https://github.com/user-attachments/assets/9beebde2-5fbc-40bc-8bab-baf5815ae428" />

3: Configure Subnets 
<img width="971" height="555" alt="image" src="https://github.com/user-attachments/assets/5f6c9ff9-c801-4f0e-8c48-1aa329a9668a" />

4: Setting Internet gateway 
<img width="1008" height="554" alt="image" src="https://github.com/user-attachments/assets/6cd47ccb-ae79-4876-a4b1-af7845ac4fed" />

5: Setting Internet gateway
<img width="1041" height="629" alt="image" src="https://github.com/user-attachments/assets/8f07b245-e207-4a4b-95a5-c93956555e5c" />

6: Setting Internet gateway
<img width="1042" height="562" alt="image" src="https://github.com/user-attachments/assets/a1d6f893-32e8-42e4-b9eb-10d78cc6384b" />

7: Creating route table
<img width="993" height="636" alt="image" src="https://github.com/user-attachments/assets/8ebdc1b3-e5ed-48ec-bfea-eba7660bc730" />


8: Configuring route table
<img width="995" height="565" alt="image" src="https://github.com/user-attachments/assets/41ba222a-e9b7-498d-924d-21c5fdd4b883" />


9: Editing routes
<img width="1002" height="552" alt="image" src="https://github.com/user-attachments/assets/1bfa3641-f38c-44f4-b313-7220660b9e81" />

10: Creating route table
<img width="978" height="517" alt="image" src="https://github.com/user-attachments/assets/204de61f-d566-455d-bb72-45404674f50b" />

# Result:
Thus, a private cloud on AWS involves using VPCs has been created for a dedicated, isolated network where we can manage our resources and control access according to our requirements.
