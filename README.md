# n8n-installation

### Add Firewall 
```
sudo apt update && apt upgrade

# Enable firewall
ufw enable

# Allow HTTP and HTTPS
ufw allow 80/tcp
ufw allow 443/tcp
ufw allow 22/tcp

# Check status
ufw status
```

### Get and run the installation 
```
# Download the script
wget https://raw.githubusercontent.com/0xSmokey/n8n-installation/main/installscript.sh

# Make it executable
chmod +x installscript.sh

# Run the installation
sudo ./installscript.sh --domain="yourdomain.com" --email="your.email@gmail.com"
```
