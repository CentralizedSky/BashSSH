#!/bin/bash

# Install SSH server (OpenSSH) if not already installed
sudo apt-get update
sudo apt-get install openssh-server

# Start the SSH server
sudo service ssh start

# Get the local IP address of the machine
ip_address=$(hostname -I | cut -d' ' -f1)

echo "SSH server started. You can now connect to this machine using SSH."
echo "Connect using: ssh username@$ip_address"
