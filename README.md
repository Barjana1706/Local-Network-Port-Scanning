Task 1 – Local Network Port Scanning

System IP: 10.155.107.92 Network Range: 10.155.107.0/24

Tool Used: Nmap

Description: Using Nmap, I scanned my local network through a mobile hotspot to identify active devices and open ports. The scan results showed open ports such as 3306 and 7070 on one of the connected devices. These ports indicate the presence of database and application/web services running on the system.

Vulnerability Analysis: Port 3306 (MySQL) can be a security risk if the database service is exposed without proper authentication or access restrictions. Port 7070 is commonly associated with application or web services and may allow unauthorized access if not securely configured.

Conclusion: Unused ports should be closed, and firewall rules should be applied to restrict access to sensitive services. Regular port scanning helps in identifying vulnerabilities and securing the local network.# Local-Network-Port-Scanning
