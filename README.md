# 🌐 Linux Web Server Setup

This guide helps you set up an Apache web server on **Amazon Linux / RedHat** and **Ubuntu**.

---

## 🟥 Amazon Linux / RedHat

### 🔧 Install and Start Apache

```bash
sudo yum install httpd -y  
sudo systemctl start httpd  
sudo systemctl enable httpd 
cd /var/www/html  
sudo chmod 700 /var/www/html  
sudo touch index.html 
sudo nano index.html
<h1> webserver </h1>

## 🟥 Ubuntu

sudo apt install apache2  
sudo systemctl start apache2  
sudo systemctl enable apache2  
cd /var/www/html  
sudo chmod 700 /var/www/html  
sudo touch index.html  
sudo nano index.html
<h1> webserver </h1>
