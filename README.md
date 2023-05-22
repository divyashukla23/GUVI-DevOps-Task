# GUVI-test
<b> Step 1:  Create a small web application using AWS EC2 </b> \
a.  Launch an EC2 instance: \
    Click on "Launch Instance" on AWS Console to create a new EC2 instance. \
    Using Amazon Machine Image (AMI), create a t2 micro instance with least configurations.\
    Create security group that allows inbound traffic on port 80 (HTTP) or port 443 (HTTPS) to access your web app. \
    Connect to your EC2 instance: 

b. Install a web server: \
    Install Apache web server by running the following command:<code> sudo yum install httpd -y </code> \
    Start the Apache service: <code> sudo service httpd start. </code> \
    Enable Apache to start on system boot: <code> sudo chkconfig httpd on </code>

c. Create a simple HTML file (index.html): \
    Change to the web server's root directory: cd /var/www/html \
    Create a new HTML file: Create a new HTML file: \
    index.html file is attached in the root directory. \
    ![Screenshot](web-server.png)

<b> Step 2: Creating a Pipeline for this web-application. </b>



 



