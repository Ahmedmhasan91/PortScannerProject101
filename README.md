 PortScannerProject101
Port Scanner Project Documentation

1. Purpose of Each Script

Simple Port Scanner (simple_port_scanner.py):
The purpose of the Simple Port Scanner script is to conduct a basic scan on a specified host to identify open ports within a given range (default 1-1024). This script utilizes socket connections to attempt connections to each port and determines if the port is open or closed based on the connection attempt.

Threaded Port Scanner (threaded_port_scanner.py):
The Threaded Port Scanner script enhances scanning efficiency by utilizing multiple threads to concurrently scan ports. This approach significantly reduces scan time by allowing parallel processing of port connections, making it suitable for scanning a wide range of ports quickly.

2. Results Obtained

Simple Port Scanner Results:

Host: 192.168.1.1
Ports Open:
Port 21 (FTP)
Port 22 (SSH)
Port 23 (Telnet)
Port 53 (DNS)
Port 80 (HTTP)
Threaded Port Scanner Results:

Host: 192.168.1.1
Ports Open:
Port 21 (FTP)
Port 22 (SSH)
Port 23 (Telnet)
Port 53 (DNS)
Port 80 (HTTP)
Port 139 (NetBIOS)
Port 445 (SMB)
3. Security Implications and Recommendations

Implications:
Port scanning reveals open ports that could potentially expose the host to unauthorized access or vulnerabilities. Identifying open ports helps in understanding the security posture of the network and enables proactive measures to mitigate risks.

Recommendations:

Implement firewall rules to restrict access to unnecessary ports.
Regularly update and patch software to prevent exploitation of known vulnerabilities.
Conduct periodic port scans as part of routine security assessments.
Obtain proper authorization before performing port scans on networks to comply with ethical standards.
4. Conclusion

The Port Scanner project demonstrates the effectiveness of Python scripts in conducting network security assessments. By identifying open ports and their associated services, organizations can enhance their cybersecurity posture and mitigate potential risks of unauthorized access.
