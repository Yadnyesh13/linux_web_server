# linux_web_server

 // amazon linux/redhat  
  
 sudo yum install httpd -y  
 sudo systemctl start httpd  
 sudo systemctl enable httpd  
 cd /var/www/html  
 sudo chmod 700 /var/www/html  
 sudo touch index.html 
 sudo nano index.html 
  
 <h1> webserver </h1>
 / ec2-public-ip:80 

 // ubuntu  
  
 sudo apt install apache2 
 sudo systemctl start apache2 
 sudo systemctl enable apache2 
 cd /var/www/html  
 sudo chmod 700 /var/www/html  
 sudo touch index.html 
 sudo nano index.html 
  
 <h1> webserver </h1> 
  
 // www.localhost:80 
