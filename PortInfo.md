# Commonly Used Ports in Computer Networks

This repository lists commonly used ports in computer networks along with their protocols, potential risks, and security recommendations. It aims to provide a quick reference for network administrators and security professionals to secure their systems against potential threats.

The table includes ports for popular protocols such as FTP, SSH, SMTP, DNS, HTTP, and RDP, as well as ports for commonly used database systems and peer-to-peer file sharing protocols. The potential risks associated with each port are also listed along with recommended security measures to mitigate those risks.

#
#

| Port Number | Protocol/Service | Description | Potential Risks | Security Recommendations |
| --- | --- | --- | --- | --- |
| 21 | FTP | File transfer protocol used for transferring files between servers and clients | Data leaks, malware infections, credentials interception | Use SFTP instead of FTP, strong password policies |
| 22 | SSH | Secure Shell protocol used for secure remote access to servers and devices | Brute force attacks, malware infections, credential theft | Use key-based authentication, limit session duration, implement two-factor authentication |
| 23 | Telnet | Remote access protocol for connecting to servers and devices | Malware infections, credentials interception, lack of encryption | Use SSH instead of Telnet, implement access restrictions, enforce strong password policies |
| 25 | SMTP | Simple Mail Transfer Protocol used for sending emails | Spam emails, phishing attacks, malware infections | Implement email filtering, use sender authentication techniques, limit message size |
| 53 | DNS | Domain Name System used for resolving domain names to IP addresses | DNS attacks, data leaks, cache poisoning | Use up-to-date DNS server software, enable DNSSEC, implement access controls |
| 80 | HTTP | Hypertext Transfer Protocol used for serving web pages | Cross-site scripting (XSS) attacks, malware infections, data leaks | Use HTTPS instead of HTTP, implement web application firewalls, use up-to-date web server software |
| 110 | POP3 | Post Office Protocol used for retrieving email messages | Malware infections, credentials interception, spam emails | Use IMAP instead of POP3, enable SSL/TLS encryption, implement email filtering |
| 123 | NTP | Network Time Protocol used for time synchronization | DDoS attacks, unauthorized access, data leaks | Implement access controls, use authentication mechanisms, restrict external access |
| 135 | Microsoft RPC | Microsoft Remote Procedure Call protocol used for communication between Windows devices | Malware infections, samba exploits, ransomware attacks | Apply security patches regularly, disable unnecessary services, use firewall to block unwanted traffic |
| 139 | NetBIOS | Network Basic Input/Output System used for Windows network sharing | Malware infections, data leaks, samba exploits | Use SMBv2 or SMBv3 instead of SMBv1, disable NetBIOS over TCP/IP, enforce strong password policies |
| 143 | IMAP | Internet Message Access Protocol used for retrieving email messages | Spam emails, malware infections, credentials interception | Use POP3 instead of IMAP, use encrypted channels for authentication, implement email filtering |
| 161 | SNMP | Simple Network Management Protocol used for managing network devices | Credentials interception, data leaks, samba exploits | Use SNMPv3 with strong authentication and encryption, implement access controls, disable unnecessary features |
| 389 | LDAP | Lightweight Directory Access Protocol used for directory services | Credentials interception, data leaks, samba exploits | Use encrypted channels for authentication, implement access controls, apply security patches regularly |
| 443 | HTTPS | Hypertext Transfer Protocol Secure used for serving secure web pages | Malware infections, XSS attacks, data leaks | Implement TLS encryption, use up-to-date web server software, use web application firewalls |
| 445 | SMB | Server Message Block protocol used for Windows network sharing | Malware infections, samba exploits, ransomware attacks | Use SMBv2 or SMBv3 instead of SMBv1, enforce strong password policies, use firewalls to block unwanted traffic |
| 465 | SMTPS | Secure SMTP protocol used for sending encrypted emails | Spam emails, phishing attacks, malware infections | Implement email filtering, use sender authentication techniques, limit message size |
| 502 | Modbus | Protocol used for industrial control systems | Malware infections, cyber espionage, DDoS attacks | Use encryption and authentication for Modbus traffic, implement access controls, enforce strong password policies |
| 587 | SMTP | Simple Mail Transfer Protocol used for sending emails over encrypted connections | Spam emails, phishing attacks, malware infections | Implement email filtering, use sender authentication techniques, limit message size |
| 993 | IMAPS | Internet Message Access Protocol Secure used for retrieving encrypted email messages | Malware infections, credentials interception, spam emails | Use encrypted channels for authentication, implement email filtering, enforce strong password policies |
| 995 | POP3S | Post Office Protocol Secure used for retrieving encrypted email messages | Malware infections, credentials interception, spam emails | Use encrypted channels for authentication, implement email filtering, enforce strong password policies |
| 1194 | OpenVPN | VPN protocol used for secure remote access to networks | Brute force attacks, data leaks, Man-in-the-Middle attacks | Use strong encryption, limit access to OpenVPN server, implement two-factor authentication |
| 1433 | Microsoft SQL Server | Microsoft SQL Server database protocol | SQL injection attacks, malware infections, data leaks | Use strong authentication mechanisms, limit access to SQL Server, apply security patches regularly |
| 1434 | Microsoft SQL Server | Microsoft SQL Server database protocol (alternative port) | SQL injection attacks, malware infections, data leaks | Use strong authentication mechanisms, limit access to SQL Server, apply security patches regularly |
| 1521 | Oracle | Oracle database protocol | SQL injection attacks, malware infections, data leaks | Implement access controls, use encrypted channels for authentication, apply security patches regularly |
| 1701 | L2TP | Layer 2 Tunneling Protocol used for VPN connections | Brute force attacks, data leaks, Man-in-the-Middle attacks | Use strong encryption, limit access to L2TP server, implement two-factor authentication |
| 1723 | PPTP | Point-to-Point Tunneling Protocol used for VPN connections | Brute force attacks, data leaks, samba exploits | Use secure VPN protocols like IPSec, implement access controls, enforce strong password policies |
| 1900 | UPnP | Universal Plug and Play protocol used for automatic discovery of devices on a network | Unauthorized access, data leaks, malware infections | Disable UPnP if not needed, restrict access to UPnP services |
| 2222 | SSH | Secure Shell protocol used for secure remote access to servers and devices (alternative port) | Brute force attacks, malware infections, credential theft | Use key-based authentication, limit session duration, implement two-factor authentication |
| 3306 | MySQL | MySQL database protocol | SQL injection attacks, malware infections, data leaks | Use strong authentication mechanisms, limit access to MySQL, apply security patches regularly |
| 3389 | RDP | Remote Desktop Protocol used for remote access to Windows machines | Brute force attacks, data leaks, malware infections | Limit RDP access to trusted networks, use strong authentication mechanisms, apply security patches regularly |
| 5353 | mDNS | Multicast Domain Name System used for automatic discovery of devices on a network | Unauthorized access, data leaks, malware infections | Disable mDNS if not needed, restrict access to mDNS services |
| 5432 | PostgreSQL | PostgreSQL database protocol | SQL injection attacks, malware infections, data leaks | Use strong authentication mechanisms, limit access to PostgreSQL, apply security patches regularly |
| 5900 | VNC | Virtual Network Computing protocol used for remote access to desktop environments | Brute force attacks, data leaks, malware infections | Limit VNC access to trusted networks, use strong authentication mechanisms, apply security patches regularly |
| 6001 | X11 | X Window System protocol used for remote access to graphical desktops (alternative port) | Brute force attacks, data leaks, malware infections | Limit X11 access to trusted networks, use strong authentication mechanisms, apply security patches regularly |
| 6666 | IRC | Internet Relay Chat protocol used for group communication (alternative port) | Malware infections, phishing attacks, data leaks | Implement access controls, use encrypted channels for authentication, limit IRC use |
| 8008 | HTTP | Hypertext Transfer Protocol used for serving web pages (alternative port) | Cross-site scripting (XSS) attacks, malware infections, data leaks | Use HTTPS instead of HTTP, implement web application firewalls, use up-to-date web server software |
| 8080 | HTTP | Hypertext Transfer Protocol used for serving web pages (alternative port) | Cross-site scripting (XSS) attacks, malware infections, data leaks | Use HTTPS instead of HTTP, implement web application firewalls, use up-to-date web server software |
| 8088 | HTTP | Hypertext Transfer Protocol used for serving web pages (alternative port) | Cross-site scripting (XSS) attacks, malware infections, data leaks | Use HTTPS instead of HTTP, implement web application firewalls, use up-to-date web server software |
| 8888 | HTTP | Hypertext Transfer Protocol used for serving web pages (alternative port) | Cross-site scripting (XSS) attacks, malware infections, data leaks | Use HTTPS instead of HTTP, implement web application firewalls, use up-to-date web server software |
| 8999 | HTTP | Hypertext Transfer Protocol used for serving web pages (alternative port) | Cross-site scripting (XSS) attacks, malware infections, data leaks | Use HTTPS instead of HTTP, implement web application firewalls, use up-to-date web server software |
| 9091 | HTTP | Hypertext Transfer Protocol used for serving web pages (alternative port) | Cross-site scripting (XSS) attacks, malware infections, data leaks | Use HTTPS instead of HTTP, implement web application firewalls, use up-to-date web server software |
| 9200 | Elasticsearch | Open source search and analytics engine | Data leaks, unauthorized access, denial of service attacks | Use strong authentication mechanisms, limit access to Elasticsearch, apply security patches regularly |
| 27017 | MongoDB | MongoDB database protocol | Injection attacks, malware infections, data leaks | Use strong authentication mechanisms, limit access to MongoDB, apply security patches regularly |
| 33890 | RDP | Remote Desktop Protocol used for remote access to Windows machines (alternative port) | Brute force attacks, data leaks, malware infections | Limit RDP access to trusted networks, use strong authentication mechanisms, apply security patches regularly |
| 33899 | RDP | Remote Desktop Protocol used for remote access to Windows machines (alternative port) | Brute force attacks, data leaks, malware infections | Limit RDP access to trusted networks, use strong authentication mechanisms, apply security patches regularly |
| 49152 | Windows RPC | Windows Remote Procedure Call protocol used for communication between Windows devices | Malware infections, samba exploits, ransomware attacks | Apply security patches regularly, disable unnecessary services, use firewall to block unwanted traffic |
| 49153 | Windows RPC | Windows Remote Procedure Call protocol used for communication between Windows devices (alternative port) | Malware infections, samba exploits, ransomware attacks | Apply security patches regularly, disable unnecessary services, use firewall to block unwanted traffic |
| 49153 | Windows RPC | Windows Remote Procedure Call protocol used for communication between Windows devices (alternative port) | Malware infections, samba exploits, ransomware attacks | Apply security patches regularly, disable unnecessary services, use firewall to block unwanted traffic |
| 49154 | Windows RPC | Windows Remote Procedure Call protocol used for communication between Windows devices (alternative port) | Malware infections, samba exploits, ransomware attacks | Apply security patches regularly, disable unnecessary services, use firewall to block unwanted traffic |
| 49155 | Windows RPC | Windows Remote Procedure Call protocol used for communication between Windows devices (alternative port) | Malware infections, samba exploits, ransomware attacks | Apply security patches regularly, disable unnecessary services, use firewall to block unwanted traffic |
| 49156 | Windows RPC | Windows Remote Procedure Call protocol used for communication between Windows devices (alternative port) | Malware infections, samba exploits, ransomware attacks | Apply security patches regularly, disable unnecessary services, use firewall to block unwanted traffic |
| 49157 | Windows RPC | Windows Remote Procedure Call protocol used for communication between Windows devices (alternative port) | Malware infections, samba exploits, ransomware attacks | Apply security patches regularly, disable unnecessary services, use firewall to block unwanted traffic |
| 50000 | SAP | SAP database protocol | Injection attacks, data leaks, malware infections | Use strong authentication mechanisms, limit access to SAP, apply security patches regularly |
| 50070 | Hadoop | Hadoop Distributed File System protocol | Data leaks, unauthorized access, denial of service attacks | Use strong authentication mechanisms, limit access to Hadoop, apply security patches regularly |
| 51413 | BitTorrent | BitTorrent protocol used for peer-to-peer file sharing | Malware infections, copyright violations, data leaks | Use legal file sharing options, implement network traffic monitoring, enforce security policies |
| 5800 | VNC | Virtual Network Computing protocol used for remote access to desktop environments (alternative port) | Brute force attacks, data leaks, malware infections | Limit VNC access to trusted networks, use strong authentication mechanisms, apply security patches regularly |
| 5901 | VNC | Virtual Network Computing protocol used for remote access to desktop environments (alternative port) | Brute force attacks, data leaks, malware infections | Limit VNC access to trusted networks, use strong authentication mechanisms, apply security patches regularly |
| 6000 | X11 | X Window System protocol used for remote access to graphical desktops | Brute force attacks, data leaks, malware infections | Limit X11 access to trusted networks, use strong authentication mechanisms, apply security patches regularly |
| 6667 | IRC | Internet Relay Chat protocol used for group communication | Malware infections, phishing attacks, data leaks | Implement access controls, use encrypted channels for authentication, limit IRC use |
| 8000 | HTTP | Hypertext Transfer Protocol used for serving web pages (alternative port) | Cross-site scripting (XSS) attacks, malware infections, data leaks | Use HTTPS instead of HTTP, implement web application firewalls, use up-to-date web server software |
| 8081 | HTTP | Hypertext Transfer Protocol used for serving web pages (alternative port) | Cross-site scripting (XSS) attacks, malware infections, data leaks | Use HTTPS instead of HTTP, implement web application firewalls, use up-to-date web server software |
| 8443 | HTTPS | Hypertext Transfer Protocol Secure used for serving secure web pages (alternative port) | Malware infections, XSS attacks, data leaks | Implement TLS encryption, use up-to-date web server software, use web application firewalls |
| 9090 | HTTP | Hypertext Transfer Protocol used for serving web pages (alternative port) | Cross-site scripting (XSS) attacks, malware infections, data leaks | Use HTTPS instead of HTTP, implement web application firewalls, use up-to-date web server software |
| 9201 | Elasticsearch | Open source search and analytics engine (alternative port) | Data leaks, unauthorized access, denial of service attacks | Use strong authentication mechanisms, limit access to Elasticsearch, apply security patches regularly |
| 11211 | Memcached | Distributed memory caching system protocol | Distributed denial of service attacks, data leaks, malware infections | Implement access controls, use encrypted channels for communication, apply security patches regularly |
| 27018 | MongoDB | MongoDB database protocol (alternative port) | Injection attacks, malware infections, data leaks | Use strong authentication mechanisms, limit access to MongoDB, apply security patches regularly |
| 27019 | MongoDB | MongoDB database protocol (alternative port) | Injection attacks, malware infections, data leaks | Use strong authentication mechanisms, limit access to MongoDB, apply security patches regularly |
| 27020 | MongoDB | MongoDB database protocol (alternative port) | Injection attacks, malware infections, data leaks | Use strong authentication mechanisms, limit access to MongoDB, apply security patches regularly |
| 50030 | Hadoop | Hadoop Distributed File System protocol (alternative port) | Data leaks, unauthorized access, denial of service attacks | Use strong authentication mechanisms, limit access to Hadoop, apply security patches regularly |
| 50060 | Hadoop | Hadoop Distributed File System protocol (alternative port) | Data leaks, unauthorized access, denial of service attacks | Use strong authentication mechanisms, limit access to Hadoop, apply security patches regularly |
| 51415 | BitTorrent | BitTorrent protocol used for peer-to-peer file sharing (alternative port) | Malware infections, copyright violations, data leaks | Use legal file sharing options, implement network traffic monitoring, enforce security policies |
| 54321 | malware | Commonly used port by malware | Malware infections, data leaks, unauthorized access | Use firewalls to block unwanted traffic, implement access controls, apply security patches regularly |

#

# Command-Line Tools by HalilDeniz

### Port Scanner

This is a Python command line tool for scanning open ports on a target machine. The tool allows the user to specify a range of ports, a specific port, or a comma-separated list of ports. It also allows the user to specify the number of threads to use for scanning. You can also find the use of the tool on my youtube address.
[Port-Scanner](https://github.com/HalilDeniz/Port-scanner)

### PathFinder

Web Path Finder is a Python program that provides information about a website. It retrieves various details such as page title, last updated date, DNS information, subdomains, firewall names, technologies used, certificate information, and more.
[Path Finder](https://github.com/HalilDeniz/PathFinder)

### MacChanger

The Mac Address Changer is a command-line tool designed to change the MAC address of a network interface. It provides a simple and convenient way to modify the MAC address for privacy, security, or network testing purposes.
[MacChanger](https://github.com/HalilDeniz/MacChanger)

### PrivacyNet

PrivacyNet is an anonymization tool that configures iptables and Tor to route all services, traffic and DNS through the Tor network. This tool allows users to route internet traffic through Tor and hide their real IP address.
[PrivacyNet](https://github.com/HalilDeniz/PrivacyNet)


## Contact
For any inquiries or further information, you can reach me through the following channels:

- LinkedIn: [Halil Ibrahim Deniz](https://www.linkedin.com/in/halil-ibrahim-deniz/)
- TryHackMe: [Halilovic](https://tryhackme.com/p/halilovic)
- Instagram: [deniz.halil333](https://www.instagram.com/deniz.halil333/)
- YouTube: [Halil Deniz](https://www.youtube.com/c/HalilDeniz)
- Email: halildeniz313@gmail.com
