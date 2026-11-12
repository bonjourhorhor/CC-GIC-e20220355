Cloud Lab 4 Submission — Amazon VPC
Copy this template to cc-lab-YOUR_ID/lab4/README.md in your own repository. Follow the instructions. Put your screenshots in lab4/images/ with the file names below.

Student name:
Student ID:
Learner Lab user name:
Date completed:
VPC and internet gateway
lab4-vpc

Internet gateway attached

Public subnet
Public subnet

Public route table

EC2 instance in the public subnet

Internet test from the public subnet

Private subnet
Private subnet

NAT gateway

Private route table

EC2 instance in the private subnet

Internet test from the private subnet

Questions
The VPC is 10.0.0.0/24 and the subnets are 10.0.0.0/25 and 10.0.0.128/25. How many IP addresses does each block contain, and why do the two subnets not overlap?
Both subnets are in the same VPC. What exactly makes lab4-public-subnet public and lab4-private-subnet private?
Why is the NAT gateway placed in the public subnet and not in the private one?
lab4-ec2-02 has no public IP address. Can someone on the internet open a connection to it? Can it download updates? Explain both answers.
You tested internet access with Systems Manager instead of SSH. Why did the instances need LabInstanceProfile for this?