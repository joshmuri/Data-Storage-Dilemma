# Data-Storage-Dilemma
Week 17 Assignment: Amazon EBS and EFS

Problem Statement.

You're tasked with creating data storage solutions using Amazon EBS and EFS for different use cases.

Guidelines/Goals:
1. Amazon EBS Setup:
   - Create an Amazon EBS volume and attach it to an ECS instance.
   - Format and mount the volume to a specific directory.
     
2. Use EBS for application Data:
   - Create a simple text file on the EBS volume.
   - Ensure the data persists even if the instance is stopped and started.
     
3. Amazon EFS Setup:
   - Create an Amazon EFS system.
   - Mount the file system on multiple EC2 instances.
     
4. Use EFS for Shared Data:
   - Create a file on one instance and verify its presence on another.
   - Observe how changes to the file on one instance are reflected on the other.
  
