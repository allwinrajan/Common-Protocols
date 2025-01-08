### Common Protocols 📡

---

**DNS (Domain Name System)**  
- **Purpose**: Converts human-readable domain names into machine-understandable IP addresses.  
- **How it Works**: When you hit a URL in the browser, the DNS server resolves the IP address for the domain, allowing the browser to connect to the IP and fetch the website.  
- **Analogy**: Like a phonebook for the internet. 📖📞

---

**DHCP (Dynamic Host Configuration Protocol)**  
- **Purpose**: Automatically assigns an IP address to a device in the network.  
- **How it Works**: A device requests an IP address upon connecting to the network, and the DHCP server assigns an available IP address, gateway, and DNS settings.  
- **Analogy**: Like a hotel receptionist assigning rooms to guests. 🏨

---

**ICMP (Internet Control Message Protocol)**  
- **Purpose**: Used for diagnostic functions, like testing connectivity (e.g., ping).  
- **How it Works**: Ping uses ICMP to check if a device is reachable and measures the response time. ICMP sends a request to the target, and if the target is reachable, it sends a response.  
- **Analogy**: A “heartbeat” check for devices. 💓

---

**ARP (Address Resolution Protocol)**  
- **Purpose**: Resolves IP addresses into MAC addresses of devices in the network.  
- **How it Works**: When Device A wants to communicate with Device B in the same network, ARP finds Device B's MAC address using its IP. ARP sends a broadcast asking “Who has IP?” and the device with the matching IP replies with its MAC address.  
- **Analogy**: A “name lookup” on a local network. 🔍

---

### Ports 🔌

**Static Port**: Permanently assigned to a specific service (e.g., HTTP - 80, HTTPS - 443).  
**Dynamic Port**: Temporarily assigned for client-side communication (range: 49512 - 65535).  
- **How it Works**: Web servers use static ports (e.g., port 80 for HTTP), while browsers use dynamic ports (e.g., port 53152) to receive responses.  
- **Analogy**: Like hotel rooms (static) vs. temporary conference rooms (dynamic). 🏨🔄

---

**TCP (Transmission Control Protocol)**  
- **Purpose**: A connection-oriented protocol ensuring reliable data transfer.  
- **How it Works**: Establishes a connection (handshake), splits data into packets, sends them, and reassembles them at the destination. It ensures lost packets are resent.  
- **Use Cases**: File transfer, email, and web browsing (HTTP). 📂📧🌐

---

**UDP (User Datagram Protocol)**  
- **Purpose**: A connectionless protocol that sends data without guaranteeing delivery.  
- **How it Works**: Sends data packets to the target without establishing a connection or performing error checking.  
- **Use Cases**: Used in gaming and live streaming, where speed is prioritized over reliability. 🎮🎥

---

### Web Protocols 🌐

**HTTP (Hypertext Transfer Protocol)**  
- **Purpose**: Transfers web pages from server to browser.  
- **Port**: 80  
- **Key Point**: Data transfer in plain text, making it less secure.  

**HTTPS (Hypertext Transfer Protocol Secure)**  
- **Purpose**: Secure version of HTTP, using encryption for protection.  
- **Port**: 443  
- **Key Point**: Protects sensitive data (e.g., bank details, passwords). 🔒💳

---

### Web Servers 🖥️

**IIS (Internet Information Services)**  
- **Purpose**: A Microsoft web server for deploying web applications on Windows, supporting .NET, PHP, and other technologies.  
- **Use Cases**: Hosting applications on Windows servers. 🖥️🔧

**Apache Tomcat**  
- **Purpose**: A Java-based web server for deploying Java applications.  
- **Use Cases**: Hosting Java-based applications. ☕️📊

---

### Time Protocols 🕰️

**NTP (Network Time Protocol)**  
- **Purpose**: Synchronizes the clock across devices on the network with high accuracy.  
- **Use Cases**: Ensures devices on the network have the same time. ⏰

**SNTP (Simple Network Time Protocol)**  
- **Purpose**: A simpler version of NTP, used where millisecond accuracy isn't critical.  
- **Use Cases**: Less critical applications where time synchronization is still important. 🕐

---

### Network Management 📡

**SNMP (Simple Network Management Protocol)**  
- **Purpose**: Monitors and manages devices on the network (e.g., routers, switches).  
- **How it Works**: SNMP agents gather data from devices, and the SNMP manager analyzes and monitors the data.  
- **Use Cases**: Managing network devices. ⚙️📊

---

### Secure Access 🔐

**SSH (Secure Shell)**  
- **Purpose**: Securely connects and manages remote servers.  
- **Port**: 22  
- **Use Cases**: Remotely accessing Linux servers. 💻🔒

---

### File Transfer 🚚

**FTP (File Transfer Protocol)**  
- **Purpose**: Transfers files between devices on the network.  
- **Port**: 21  
- **Limitation**: Less secure, as data is sent in plain text. 📂

**SFTP (Secure File Transfer Protocol)**  
- **Purpose**: Securely transfers files using encryption.  
- **Port**: 22  
- **Key Point**: More secure than FTP. 🔒📁

**SCP (Secure Copy Protocol)**  
- **Purpose**: Transfers files securely between devices using SSH encryption.  
- **Port**: 22  
- **Key Point**: A more secure way of copying files over a network. 🔑📁

---
**by Alvin Irudaya Rajan**
