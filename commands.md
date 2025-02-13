##**Step-by-step command history for installing AWS CLI, configuring it, and listing EC2 instances and S3 Buckets.**
##### AWS CLI Installation and Basic Commands 🚀  

1️⃣*Update and Check Versions**

sudo apt-get update

aws --version

python3 --version

2️⃣ **Download & Install AWS CLI**

sudo curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"

sudo apt install unzip

unzip awscliv2.zip

sudo ./aws/install

3️⃣ **Configure AWS CLI**

aws configure

🔹 **This will prompt for:**

Access Key

Secret Key

Default Region

Output Format


4️⃣ **Basic AWS CLI Commands**

aws s3 ls                 # List S3 Buckets

aws ec2 describe-instances --query "Reservations[].Instances[].InstanceId" --output text                     # List EC2 Instances
