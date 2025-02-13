##### **AWS CLI Demo 🚀**  

##### **Project Summary**  
This project demonstrates the installation and usage of AWS CLI on a Linux system. It includes:  
- Installing AWS CLI  
- Configuring AWS credentials  
- Running basic AWS commands to interact with services like EC2 and S3  

##### **Steps Covered 🛠️**  
1️⃣ Install and verify AWS CLI  
2️⃣ Configure AWS CLI with access keys  
3️⃣ List S3 buckets  
4️⃣ Retrieve EC2 instance details  

##### **AWS CLI Commands Used**  
```bash
# Check AWS CLI version
aws --version

# Configure AWS credentials
aws configure

# List S3 buckets
aws s3 ls

# List all EC2 instance IDs
aws ec2 describe-instances --query "Reservations[].Instances[].InstanceId" --output text
```

##### **How to Use?**  
1. Clone this repository  
2. Follow the step-by-step guide in `images` 
3. Run the AWS CLI commands  

##### **Author**  
👤 **Vaishnavi Golhar**  

##### **Connect with Me**  
🌐 [LinkedIn]https://www.linkedin.com/in/vaishnavi-golhar-673b0b349/
