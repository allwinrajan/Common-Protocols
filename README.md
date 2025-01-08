![reference](https://github.com/allwinrajan/Common-Protocols/blob/58fa804c73a6769c5e9fd66e35f77784cd060830/Comman%20Protocols%20diagram.png)

# Common Protocols

Protocols and How it will work 

**DNS (Domain Name System)** 

**Purpose**: Convert human readable Domain name into machine understandable IP addresses. 

**How it Works**: When we hit the URL on the browser the DNS server resolve IP address for the domain, browser connect to IP and fetch website. 

**Analogy**: It’s like a phonebook for the internet. 



**DHCP (Dynamic Host Configuration Protocol)** 

**Purpose**: Automatically Assign the IP address to the device in the network 

**How it Works**: A device requests an IP address when connected to network. DHCP server will assign available IP address, gateway and DNS settings. 

Analogy: Like a Hotel Receptionist will assign room for guest 



**ICMP (Internet Control Message Protocol)** 

**Purpose**: Used for diagnostic functions, like testing the connectivity (e.g., ping). 

**How it Works**: Ping Uses ICMP to check the device is reachable and measure response time. 

ICMP send the request to the target. If the target is reachable then it will send response. 



**ARP (Address Resolution Protocol)** 

**Purpose**: Resolve IP address into MAC address of device in network. 

**How it Works**: When Device A wants to communicate with Device B in the same network. ARP find the MAC address of Device B using its IP. 

ARP send a broadcast, asking “Who has IP?” 

Device With Same IP reply with its MAC address. 



**Ports (Static, Dynamic)** 

**Ports**: ports allow multiple application on the device use same IP for communication. Each port corresponds specific services or applications. 

**Static Port:** Permanently assign the port to the specific service. (e.g., HTTP 80, HTTPS 443, Tomcat 8080) 

**Dynamic Ports**: Temporary Port Assigned for client-side communication (Range 49512 - 65535)  

**How it Works**: Web server uses static port 80 for HTTP, but browser uses dynamic port 53152 for receive response. 



**TCP (Transmission Control Protocol)** 

**purpose**: A connection-oriented protocol ensures the reliable data transfer. 

**How it Works**: Establish the connection (Handshake), Split the data into packets, send them, arrange the data at destination, Assemble the lost packets. 

**Use cases**: Used in file transfer, email and web browsing (HTTP) 



**UDP (User Datagram Protocol)** 

**Purpose**: A connectionless protocol, it sends the data without guarantee the delivery. 

**How it Works**: Send the data packets to target without establish the connection and error checking.  

**Use cases**: Used in Gaming and live streaming where the speed is important more than reliability. 



**HTTP (Hyper Text Transfer Protocol)** 

**Purpose**: Transfer the webpage from server to browser.  

**Port: **80 

**Key Point**: Data transfer in the form of plain text, Since its less secure. 

**HTTPS (Hyper Text Transfer Protocol Secure)** 

**Purpose**: Secure Version of HTTPS uses encryption.  

**Port: 443** 

**Key Point**: Protect sensitive data (bank details, passwords). 



**IIS vs Apache Tomcat** 

**IIS (Internet Information Services)** 

**IIS Purpose**: A web server by Microsoft to deploy web application on windows and it support .NET, PHP and other technologies. 



**Apache Tomcat** 

**Tomcat purpose**: A Java based web server to deploy java applications. 

**WWW (World Wide Web)** 

**Purpose:** A collection of web pages and services accessible over internet, by using protocols HTTP/HTTPS. 



**NTP (Network Time Protocols)** 

**Purpose: **Synchronize the clock across devices on the network. 

NTP is highly accurate. 



**SNTP (Simple Network Time Protocols)** 

**Purpose:** Simpler version of NTP and SNTP used where the mile-second accuracy isn’t needed. 

**SNMP (Simple Network Management Protocol)** 

**Purpose:** Monitor and manage the devices on the network (e.g., Router, Switch) 

- SNMP agent will gather data from devices. 
- SNMP manager will gather data from analysis. 


**SSH (Secure Shell)** 

**Purpose: **Securely connect and manage the remote servers. 

**Port**: 80 

**Use cases**: Remotely connected to Linux server 



**FTP (File Transfer Protocol)** 

**Purpose: ** Transfer the file between the devices on the network. 

**Port**: 21  

**Limitation:** Less secure, Data send in the form of plain text. 



**SFTP (Secure File Transfer Protocol)** 

**Purpose:** Securely Transfer the file with encryption between the devices on the network. 

**Port**: 22  



**SCP (Secure Copy Protocol)** 

**Purpose:** Transfer the file Securely between the devices on the network using SSH encryption. 

**Port**: 22  

