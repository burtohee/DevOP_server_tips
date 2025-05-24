```bash

sudo apt update
sudo apt update -y

sudo iptables -F
sudo apt install ufw

sudo iptables -L -v -n



# Allow SSH (very important if you're on a remote server)
sudo ufw allow ssh

# Allow specific port (e.g., 3000 for your Node.js app)
sudo ufw allow 3000

# Check status
sudo ufw status

# Enable UFW
sudo ufw enable

sudo systemctl is-enabled ufw
sudo systemctl enable ufw
sudo ufw status verbose


sudo ufw reload
sudo systemctl restart ufw
```
