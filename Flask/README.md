# S3 BUCKET CREATION
Bucket created in us-east-2 Region

![image](https://user-images.githubusercontent.com/60090421/115689851-1b0b6000-a37a-11eb-8216-ac995ead3e09.png)

Folders(A,B,C) in 1767-bucket

![image](https://user-images.githubusercontent.com/60090421/115690084-53ab3980-a37a-11eb-8244-2ca0a53f2e87.png)

Files uploaded in Folder B

![image](https://user-images.githubusercontent.com/60090421/115690167-6756a000-a37a-11eb-804d-24f0e97c8273.png)

# LOCAL EXECUTION OF FLASK APP
http://127.0.0.1:5000/
![image](https://user-images.githubusercontent.com/60090421/115690981-3f1b7100-a37b-11eb-855b-72c552c6f2fb.png)

# EC2 INSTANCE IN THE SAME REGION WHERE S3 HAS BEEN CREATED

![image](https://user-images.githubusercontent.com/60090421/115691990-2fe8f300-a37c-11eb-8c27-ed8d71f87c33.png)

# CONNECTION TO INSTANCE

(base) tiger0531@tiger0531:~$ cp /mnt/c/Users/aishwarya.somasu/Downloads/Aishwarya.pem .

 Grant Permission

(base) tiger0531@tiger0531:~$ chmod 400 Aishwarya.pem

![image](https://user-images.githubusercontent.com/60090421/115735624-40af5e00-a3a8-11eb-896c-60617359ec98.png)

Connection has been made to the Instance using the public DNS via the Ubuntu app

![image](https://user-images.githubusercontent.com/60090421/116125745-825f4200-a6e3-11eb-8a8e-5a9f5c07e85b.png)

 ubuntu@ip-172-31-16-71:~$ curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"

 ubuntu@ip-172-31-16-71:~$ sudo apt install unzip

 ubuntu@ip-172-31-16-71:~$ unzip awscliv2.zip

 ubuntu@ip-172-31-16-71:~$ sudo ./aws/install

# AWS Version

![image](https://user-images.githubusercontent.com/60090421/116126086-dbc77100-a6e3-11eb-8a84-ab3733269408.png)

# AWS CREDENTAILS CONFIGURATION

![image](https://user-images.githubusercontent.com/60090421/116126148-eb46ba00-a6e3-11eb-9645-76c6d41f3b65.png)

# CREATING App.py File using NANO

![image](https://user-images.githubusercontent.com/60090421/116126248-0adde280-a6e4-11eb-9cc3-7d8278b3bcbb.png)

# SECURITY GROUP TO ALLOW INCOMING TRAFFIC ONLY THROUGH 8085

![image](https://user-images.githubusercontent.com/60090421/115692111-5018b200-a37c-11eb-97a5-e20a0f7e9ed6.png)

# INSTALLATION OF REQUIRED PACKAGES

 ubuntu@ip-172-31-16-71:~$ sudo apt-get update

 ubuntu@ip-172-31-16-71:~$ sudo apt-get install python3

 ubuntu@ip-172-31-16-71:~$ sudo apt-get install python3-pip

 ubuntu@ip-172-31-16-71:~$ sudo pip3 install flask

 ubuntu@ip-172-31-16-71:~$ sudo pip3 install boto3

# ACCESING THE EC2 DEPLOYED FLASK APP VIA EC2 PUBLIC URL AT PORT 8085

![image](https://user-images.githubusercontent.com/60090421/116126849-c0109a80-a6e4-11eb-9130-e218c04ef488.png)

http://52.14.228.251:8085

![image](https://user-images.githubusercontent.com/60090421/115692874-011f4c80-a37d-11eb-98e9-9791e1b1a784.png)

# BILLING-REPORTS & BILLING-CONFIGURATION
Budget

![image](https://user-images.githubusercontent.com/60090421/115694029-1cd72280-a37e-11eb-9877-c68e7faa6409.png)

Bills

![image](https://user-images.githubusercontent.com/60090421/115694118-2f515c00-a37e-11eb-89bd-49bfe99b8257.png)

Free Tier Usage

![image](https://user-images.githubusercontent.com/60090421/115694203-44c68600-a37e-11eb-9907-adf8447113c1.png)

Grouping by Services and Tags

![image](https://user-images.githubusercontent.com/60090421/116261786-9c595d00-a795-11eb-9c60-c777e1e3d152.png)
