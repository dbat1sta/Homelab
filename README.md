# Homelab
## Home Network Security Lab Overview

To enhance my hands-on cybersecurity skills and gain practical experience in log analysis, SIEM management, and security event visualization, I built a **Virtualized Network Detection Lab**. This lab replicates an enterprise network environment, allowing me to simulate cyber-attacks, analyze logs, and visualize data through interactive dashboards. Below are the key components and configurations of my lab:

### Lab Components

1. **Virtual Machines (VMs) Setup**
   - Using **VirtualBox**, I deployed and managed multiple virtual machines running both **Windows** and **Linux** operating systems. These VMs simulate an enterprise network's diverse environment, offering a realistic playground for system and network security testing.

2. **Firewall & Network Segmentation (pfSense)**
   - I installed and configured **pfSense**, a robust open-source web firewall, to protect the virtual network by filtering and controlling incoming and outgoing traffic. 
   - To enforce **network segmentation**, I set up **VLANs (Virtual Local Area Networks)**, each with its own tailored security policies. This configuration allowed me to define clear rules and permissions, creating isolated network segments, which is vital for limiting the lateral movement of potential attackers.

3. **SIEM and Log Management (Elastic Stack)**
   - I integrated **Elastic Stack (ELK)**, which includes **Elasticsearch, Logstash**, and **Kibana**, to collect, process, and analyze security logs from the network and VMs. Using **SIEM (Security Information and Event Management)** capabilities, I monitored security events in real-time, identifying suspicious activities and potential threats.
   - Kibana’s visualization tools were utilized to create **dashboards**, which provided a detailed view of system performance, network traffic, and potential security threats through graphical representations of the logs.

4. **Simulating and Mitigating Cyber-Attacks**
   - I designed and executed a series of **simulated cyber-attacks** to test the lab’s defenses, ranging from network-based attacks to system vulnerabilities. These attacks were tracked using **NMAP** for network discovery and vulnerability scanning.
   - Leveraging **SIEM log analysis**, I successfully identified and mitigated these threats by correlating events and applying actionable security measures based on real-time data analysis.

5. **Ongoing Lab Maintenance**
   - Regular system updates and patches were applied to all virtual machines, ensuring the lab remains secure and aligned with the latest software versions. This practice mirrors industry-standard IT security protocols, where keeping systems updated is critical for preventing vulnerabilities.

### Tools and Technologies Used

- **VirtualBox**: Virtual machine management and deployment.
- **pfSense**: Web firewall for network protection and segmentation.
- **Elastic Stack (SIEM)**: Log analysis, event correlation, and data visualization using Elasticsearch, Logstash, and Kibana.
- **NMAP**: Network discovery and vulnerability scanning tool.
- **Windows/Linux**: Operating systems used for virtual machines.
- **Incident Response**: Processes established for identifying, analyzing, and mitigating security incidents.
- **Security Onion**: Comphrenensive Suite of security tools.

### Conclusion

By building this **Virtualized Network Detection Lab**, I was able to simulate a dynamic and secure network environment. It provided me with crucial hands-on experience in **log analysis, SIEM usage, incident response**, and **threat detection**, all of which are essential skills for a cybersecurity analyst role. My lab demonstrates my ability to apply these tools and techniques in a controlled, virtual environment, further solidifying my expertise in network security.

