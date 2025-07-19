**📝 Codetech Task 4 – Multi-Cloud Architecture Report**


Name: Y. Sherisha
Task: Design a Multi-Cloud Architecture Where Services Are Distributed Across Two Cloud Providers
Platform Used: AWS EC2 + GCP Cloud Storage
AWS Instance ID: i-03aaff0e727ab36a6
Instance Name: multitech11
Public IP: 15.207.223.7
GCP Bucket Name: multicloud11
GCP Public File URL: https://storage.googleapis.com/multicloud11/hm.jpg

**📌 Steps Performed:**

Created EC2 instance on AWS
  – Type: t2.micro, Amazon Linux 2
  – Port 80 opened in security group
  – Connected via SSH using kp11.pem

Set up a web server on AWS
  – Created index.html with basic message and GCP image embed
  – Served using: sudo python3 -m http.server 80
  – Verified at: http://15.207.223.7

Created GCP Cloud Storage bucket
  – Bucket Name: multicloud11
  – Uploaded image file (hm.jpg)
  – Enabled public access for allUsers with Storage Object Viewer role

Embedded GCP content in AWS
  – Updated HTML on EC2 to reference GCP image
  – Verified successful image display on AWS-served web page

**✅ Result:**
Multi-cloud architecture successfully deployed.
AWS EC2 instance served a web page with content sourced from GCP Cloud Storage.
Live link: http://15.207.223.7
Embedded image: https://storage.googleapis.com/multicloud11/hm.jpg
