# 🚀 AWS Automated Web Hosting (S3 + EC2)

This project showcases a fully automated web server setup on AWS. Instead of manual configuration, I used **EC2 User Data** to bootstrap the server.

## 🛠️ Tech Stack
- **Cloud:** AWS (EC2, S3, IAM)
- **Linux:** Bash Scripting, Amazon Linux 2023
- **Web Server:** Nginx

## 🏗️ How it Works
1. **S3 Bucket:** Acts as the central repository for website files.
2. **IAM Role:** Securely allows the EC2 instance to read from S3 (No Access Keys needed).
3. **User Data:** A Bash script that runs at launch to:
   - Install and Start Nginx.
   - Sync the latest files from S3 to the web directory.
   - Set correct folder permissions.

## 📸 Proof of Work
*(Check the uploaded screenshots for the S3 configuration and Live Website output!)*
