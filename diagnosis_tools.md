### **Network Diagnosis Tools**  
Network diagnosis tools are utilities used to analyze, troubleshoot, and monitor network connections. These tools help in identifying issues such as connectivity problems, packet loss, network latency, and incorrect configurations.

#### **1. whois**  
   - **Definition**: A command-line tool used to retrieve domain registration information, such as the domain owner, registrar, and expiration details.  
   - **Usage**: Helps in investigating domain ownership and identifying malicious websites.  
   - **Example Command**:  
     ```sh
     whois example.com
     ```

#### **2. ping**  
   - **Definition**: A diagnostic tool used to test the connectivity between a local machine and a remote server by sending ICMP echo requests.  
   - **Usage**: Helps in checking whether a server is reachable and measures response time (latency).  
   - **Example Command**:  
     ```sh
     ping google.com
     ```

#### **3. traceroute (Windows: tracert)**  
   - **Definition**: A network tool that traces the path packets take to reach a destination, showing each hop along the route.  
   - **Usage**: Helps in identifying network bottlenecks, latency issues, and routing problems.  
   - **Example Command**:  
     ```sh
     traceroute google.com  # Linux/macOS
     tracert google.com      # Windows
     ```

#### **4. ifconfig**  
   - **Definition**: A command-line tool used for configuring and displaying network interface information, such as IP addresses and MAC addresses. (Replaced by `ip` command in newer Linux distributions).  
   - **Usage**: Helps in checking and configuring network settings, such as enabling/disabling interfaces.  
   - **Example Command**:  
     ```sh
     ifconfig
     ```
   - On modern Linux systems, use:  
     ```sh
     ip addr show
     ```

Would you like more details or additional tools? 🚀
