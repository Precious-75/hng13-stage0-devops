# DevOps Stage 0 - First DevOps challenge.

# Project Description
In this project i was asked to  deploy an NGINX web server on any Cloud Provider and manage a Github repisoty. 
- The Cloud Provider Platform used is Azure Virtual Machine.
- Operating System: Ubuntu 24.04 LTS
- Web Server: NGINX ( as requested )
- Server IP: http://40.113.169.124/

# Steps Taken
1. I began by creating a Azure Resource Group named HNGDevops and the Virtual Machine named preciousnwabunike, then configured the neccessary settings making sure that the web service will be running on port 80.
2. Configured Network Security Group to allow HTTP (port 80).
3. Installed and configured NGINX on the bash command line.
4. Created the required custom index.html file.
5. Deployed and tested accessibility on both my mobile phone and laptop web browsers(both wifi and mobile data)
Challenges Faced and Solutions

# Challenge 1: Initial SSH Connection Timeout
Problem: Could not connect to Azure VM via SSH initially,
Solution: So i had to Verify the Inbound rules in my resource group and manually create a new inbound rule for the ssh port 22 to ensure that it is accessible, which led the connection to be successful after the resolve.

# Author
Precious Nwabunike 

# Date
October 16, 2025
