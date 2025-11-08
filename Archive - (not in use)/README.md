# n8n-installation

### Add Firewall 
```
# Update system
sudo apt update && sudo apt upgrade -y

# Configure firewall safely
sudo ufw allow 22/tcp
sudo ufw allow 80/tcp
sudo ufw allow 443/tcp
sudo ufw enable
sudo ufw status
```

### Get and run the installation 
```
# Download the raw installation script
wget https://raw.githubusercontent.com/0xSmokey/n8n-installation/main/installscript.sh

# Make it executable
chmod +x installscript.sh

# Run the installation
sudo ./installscript.sh --domain="yourdomain.com" --email="your.email@gmail.com"
```
