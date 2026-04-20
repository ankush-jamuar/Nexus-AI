# AWS EC2 Static Website Hosting with IAM

## 🌐 Live Project

[http://your-elastic-ip](http://16.16.247.58/)

## ⚙️ Implementation Steps

* Launched EC2 instance (Amazon Linux)
* Connected via MobaXterm (SSH)
* Installed Apache (httpd)
* Cloned GitHub repository
* Deployed website to /var/www/html
* Configured Elastic IP

## 🔐 IAM Users

* User 1 (user1-no-access):

  * No permissions assigned
  * Shows authorization errors while accessing EC2

* User 2 (user2-ec2-access):

  * Attached AmazonEC2FullAccess policy
  * Can view and manage EC2 instances

## 📸 Screenshots
<img width="1919" height="998" alt="image" src="https://github.com/user-attachments/assets/3b07f5bd-46c6-4262-ae2e-a0828a0dfb26" />
<img width="1917" height="1044" alt="image" src="https://github.com/user-attachments/assets/907f28b4-2bc5-4aaf-af98-3be5d93d5cb4" />
<img width="1919" height="997" alt="Screenshot 2026-04-20 155818" src="https://github.com/user-attachments/assets/1749cbce-626b-4ddc-9b3e-f8a7035b7c04" />
<img width="1917" height="996" alt="Screenshot 2026-04-20 160158" src="https://github.com/user-attachments/assets/c8c100de-85b5-4d33-961c-bafc1d230fe1" />

* EC2 Instance Dashboard
* Website Running (Elastic IP)
* IAM User 1 (No Access - Error)
* IAM User 2 (EC2 Access)

## ⚠️ Challenges Faced

* Permission issues with Apache directory
* Understanding IAM access control behavior
* Security group configuration

## 🚀 Tech Stack

* AWS EC2 (Amazon Linux)
* Apache (httpd)
* IAM
* GitHub
* HTML, CSS, JavaScript
