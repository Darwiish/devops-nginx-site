# Install NGINX
sudo yum install -y nginx

# Start NGINX
sudo systemctl start nginx

# Enable on boot
sudo systemctl enable nginx

# Check status
sudo systemctl status nginx

# Git commands
git add .
git commit -m "update project"
git push origin main

# SSH into EC2
ssh ec2-user@<EC2-IP>