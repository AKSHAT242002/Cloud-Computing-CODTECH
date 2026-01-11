# Task 2: Cloud Monitoring & Alerts using AWS CloudWatch

## EC2 Instance
- AMI: Amazon Linux 2023 (x86)
- Instance Type: t3.micro (Free Tier)
- Key Pair: cloudwatch-key.pem
- Security Group: SSH allowed (0.0.0.0/0)

## Steps Performed
1. Launched EC2 instance
2. Connected via SSH using Public IP
3. Installed stress tool and generated CPU load
4. Created CloudWatch CPU Utilization Alarm (>70%)
5. Configured SNS Topic and Email alerts
6. Verified email alert received
7. Created CloudWatch Dashboard with CPU, Network In, and Disk metrics

## Screenshots

- EC2 Instance Creation.
![EC2 Instance Creation](https://github.com/AKSHAT242002/Cloud-Computing-CODTECH/blob/286ce4e8dc4f334d4fbd85da879800ace50e2b05/Task%202/Name%20of%20instance.png)
![EC2 Instance Creation](https://github.com/AKSHAT242002/Cloud-Computing-CODTECH/blob/d8f3ded1dfda0f4da0a25bd27d2c72aeb5c5fadc/Task%202/Instance%20type.png)
![EC2 Instance Creation](https://github.com/AKSHAT242002/Cloud-Computing-CODTECH/blob/662a3da7c479491795b834e4c2870b2ca8fdf1ae/Task%202/Network%20setting.png)
![EC2 Instance Creation](https://github.com/AKSHAT242002/Cloud-Computing-CODTECH/blob/c87bc1f2f0116029a1935d14bf046fee13b35309/Task%202/Configure%20storage.png)
![EC2 Instance Running](https://github.com/AKSHAT242002/Cloud-Computing-CODTECH/blob/c67c6bafb373f071e5c4c4f3aa4d6915fb14d817/Task%202/EC2%20instance%20running.png)
![CPU Alarm Created](./screenshots/cpu_alarm.png)
![SNS Email Alert](./screenshots/email_alert.png)
![CloudWatch Dashboard](./screenshots/dashboard.png)
