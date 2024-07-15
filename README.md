aws-load-balancer-demo/
#!/bin/bash
sudo yum update -y
sudo yum install nginx
sudo systemctl start nginx
sudo systemctl enable nginx
sudo vim/usr/share/nginx/html/index.html
