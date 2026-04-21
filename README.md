
# Corporate Network Design for SME (Lagos Company)

## Project Overview
This project simulates a real world Small and Medium Enterprise (SME) network for a company in Lagos. It demonstrates core networking services including DHCP, DNS, Web Hosting, and Secure Remote Access using SSH.

## Network Architecture
- 1 Router (Gateway + SSH Management)
- 1 Switch (LAN connectivity)
- 1 Server (DNS + Web services)
- 20 Client PCs
- Cloud (Internet simulation)

## Key Features Implemented

1. DHCP (Automatic IP Assignment)
- Router configured as DHCP server
- Clients automatically receive IP addresses in `192.168.10.0/24`

2. DNS Service
- Internal domain configured: `company.local`
- DNS server resolves domain name to internal web server IP

3. Web Server
- Internal company website hosted on server
- Accessible via browser using domain name

4. Secure Remote Management (SSH)
- SSH configured on router for secure access
- RSA encryption keys generated
- Remote login tested successfully from client PCs

5. Basic Internet Simulation
- Default route configured for external traffic
- Cloud used to simulate ISP connection

## Security Configuration
- SSH enabled for secure remote access
- Password authentication configured

## Testing Performed
- DHCP IP assignment verified
- DNS resolution tested (`company.local`)
- Web page accessible via browser
- Ping connectivity confirmed
- SSH remote login successful

## Technologies Used
- Cisco Packet Tracer
- DHCP
- DNS
- HTTP Web Server
- SSH (Secure Shell)
- IP Routing

## Skills Demonstrated
- Network design and topology creation
- IP addressing and subnetting
- Network service configuration
- Secure remote administration
- Troubleshooting and testing

## Screenshots
Full Setup 
<img width="1920" height="890" alt="FUll Setup" src="https://github.com/user-attachments/assets/afd1b7b3-21b0-4fd1-984c-0e16e6940798" />
Router Configuration
<img width="1684" height="746" alt="Router Config" src="https://github.com/user-attachments/assets/98cdf7d2-a0a5-47f7-8389-74c667fa8709" />
DHCP Assigned
<img width="1570" height="748" alt="DHCP Assigned" src="https://github.com/user-attachments/assets/76b35341-b5ec-4a57-bd9b-3e43f5d898cb" />
RSA
<img width="1297" height="743" alt="rsa key" src="https://github.com/user-attachments/assets/503dbd5b-d46a-4ec0-86bf-863fb5ccf1ba" />
SSH Enabled
<img width="1297" height="741" alt="ssh emabled" src="https://github.com/user-attachments/assets/6e0bcd74-bdb4-4172-aecf-2326787424b9" />
Web Testing
<img width="1311" height="742" alt="link done" src="https://github.com/user-attachments/assets/6614ba5f-a205-4a03-94f3-0920de13906e" />
Server Ping
<img width="1558" height="741" alt="Server ping" src="https://github.com/user-attachments/assets/74356d5c-7dae-4d1b-ba08-86652b467425" />



---

## 🚀 Future Improvements
- VLAN segmentation for departments (HR, IT, Finance)
- Firewall/ACL security rules
- Redundant DNS server
- NAT for real internet access simulation

---

## A.A Micheal
Aspiring Cloud & Network Engineer
