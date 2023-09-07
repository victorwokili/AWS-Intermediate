
1. Create a VPC 

![image](https://github.com/victorwokili/AWS-Intermediate/assets/18079443/42ec85ed-d44c-45a0-8fa2-54dc5c3e419f)

![image](https://github.com/victorwokili/AWS-Intermediate/assets/18079443/8e15f61d-f387-4182-bc35-b20c1bcc9def)

![image](https://github.com/victorwokili/AWS-Intermediate/assets/18079443/956132fb-6a67-4db4-b1cd-0121561aa2a0)


<br><br>


2. Create Security Groups for the Public and Private Subnet below
  - WebServerSG1
  - WebServerSG2
  - App-SG1
  - App-SG2
  - RDS-SG1
  - RDS-SG2

3. 
2. Create A Launch Template (Web &App Servers) for an Auto Scaling Group, take advantage of the user data field 
a. Don't forget to include an auto scaling group access IAM Role to the template
b. Ensure you it is a public IP 

4. Create an autoscaling group for both Web and App Servers

5. Create the BastionHostServer EC2 instance
  - Ensure the Security Group of the Bastion Host Server has port 22 connected to 0.0.0.0/0
  - 
   

## Test VPC Gateway Endpoint
6.  
