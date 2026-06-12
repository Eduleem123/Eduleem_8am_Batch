Step 1: Login into to AWS account dashboard. To know how to create an AWS account free tier refer to Amazon Web Services (AWS) – Free Tier Account Set up.

Step 2: From the AWS Management Console, type VPC into the search bar and select VPC under the Networking & Content Delivery section.

Vitual Private Cloud 
Step 3: In the VPC dashboard, on the left-hand panel, click on Your VPCs and then click the Create VPC button.

Create VPC 
Step 4:

For Resources to create, choose VPC and more
For Name tag auto-generation, enter any name you like for example: "Nitin-vpc"
IPv4 CIDR Block: Enter an IP range for your VPC. A common CIDR block for a VPC is 10.0.0.0/16, which provides 65,536 IP addresses.
Configure VPC 
For Availability Zones (AZs), choose 2.
For the Number of public subnets, choose 2.
For the Number of private subnets, choose 2.
For NAT gateways, choose none
For VPC endpoints, choose S3 gateway
VPC_Config
VPC Settings
Step 5: AWS will show a diagram preview of your VPC configuration. Review it to ensure that your subnets, CIDR blocks, and settings align with your requirements.

Privew Of Coustmized VPC 
Step 6: After configuring all the options, click Create VPC. AWS will begin creating your custom VPC, which might take a minute or two.

Step 7: Once the creation process is complete, click on View VPC to review your settings and make any necessary changes.

Creating VPC 
Best Practices After Creation
