Linux Server Administration Project

📌 Project Overview

This project demonstrates the configuration of essential Linux server services including DHCP, DNS, and a web server (Apache2) on Ubuntu.

The setup was completed as part of a semester project at the Euro Mediterranean University of Fès, School of Digital Engineering and Artificial Intelligence (EIDIA).

🔧 Services Configured:

🖥️ DHCP Server: Automatic IP address assignment for clients

🌐 DNS Server: Domain name resolution for eidia.ma

🕸️ Web Server: Apache2 hosting a custom webpage and student management platform

📋 Project Structure

Linux-Server-Admin/
├── DHCP/
│   ├── dhcpd.conf             # DHCP server configuration
│   └── README.md              # DHCP setup instructions
├── DNS/
│   ├── named.conf.local       # DNS zone declarations
│   ├── eidia.ma.zone          # Forward zone file
│   ├── eidia.ma.rev           # Reverse zone file
│   └── README.md              # DNS setup instructions
├── WebServer/
│   ├── eidia.ma.conf          # Apache virtual host config
│   ├── index.html             # Custom webpage
│   ├── StudentPlatform/       # Student management system
│   └── README.md              # Web server instructions
└── README.md                  # Main project documentation



