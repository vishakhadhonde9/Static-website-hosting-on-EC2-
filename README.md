# Static-website-hosting-on-EC2-
Hosting a static website on Amazon EC2 involves deploying a web server on an EC2 instance and serving static HTML, CSS, and other files. EC2 is a scalable cloud computing service, and hosting a static website on it means you're responsible for configuring the web server, managing security, and maintaining the infrastructure.
1) Login into AWS Cloud Account

2) Launch EC2 Instance ( AMI : Amazon Linux )

3) Connect to EC2 instance using Putty / MobaXterm

4) Install HTTPD Webserver in EC2 instance

5) Setup Website in EC2 instance

6) Configure Security Groups
	(SSH - 22 for admin access & HTTP - 80 for users to access our website)

7) Access Website from Browser using EC2 Instance Public IP


Commands To Execute
-------------------------
$ sudo su

$ yum update -y

$ yum install httpd -y

$ cd /var/www/html

$ echo "Hello! Welcome to AWS Session " > index.html

$ service httpd start
