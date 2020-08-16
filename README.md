# Amazon Web Services : EC2 
Basic Steps to start with EC2 Instances and install web server on perticular instance

PROJECT 1:
Deploying a web server in Windows instance
Task 1:Create a windows instance using AMI :Windows 2012 R2 base

Task 2:Launch the Windows instance using RDP

Task 3:Install IIS web server using Powershell ISE
Note:Simply copy the command below and paste in the powershell ISE to install the IIS web server.!!!!
Powershell is case sensitive.

Command: Install-WindowsFeature -name Web-Server -IncludeManagementTools

Task 4:Verify successful installation of IIS Web Server
Note :You should be able to see the Internet Information Services Web page when you paste the public IPinto the browser.


PROJECT 2:
Deploying a web server in Windows instance

Task 1:Create a windows instance using AMI :Ubuntu Server 18.04 LTS (HVM)

Task 2:Download and install MobaXterm Portable Edition

Task 2:Launch the Ubuntu instance using SSH
Note:Username is ubuntu

Task 3:Install ngnix web server using bash
Note:Simply copy the command below and paste in the bash to install the ngnix web server.

Command: sudo apt-get -y update

Command: sudo apt-get -y install nginx

Task 4:Verify successful installation of ngnix
Note :You should be able to see the Welcome to ngnix Web page when you paste the public IP into thebrowser
