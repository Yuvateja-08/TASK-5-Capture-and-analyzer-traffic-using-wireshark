# TASK-5-Capture-and-analyzer-traffic-using-wiresharkNetwork Traffic Capture and Analysis Using Wireshark

#Introduction
For this task, Wireshark was used to capture and analyze live network packets with the goal of identifying basic protocols and different traffic types.

#Tools Used
- *Wireshark 
Procedure
1. Wireshark Installation: Wireshark was downloaded and installed from the official website.
2. Network Interface Setup: Wireshark was configured to monitor the active network interface (Wi-Fi).
3. Traffic Generation: Regular web browsing and a file download were performed to ensure varied network activity.
4. Capture Start: Packet capture was started in Wireshark.
5. Stop Capture: After several minutes, capturing was stopped.
6. Protocol Identification: At least three different protocols were observed: HTTP, DNS, and TCP.
7. Export: The capture was saved in .pcap format.
8. Result Compilation: Protocol details, key findings, and packet analysis are summarized below.

# Protocols Identified
- HTTP: Hypertext Transfer Protocol traffic was visible from visits to web pages.
- DNS: Domain Name System queries were captured when resolving website addresses.
- TCP: Transmission Control Protocol sessions were recorded for reliable data transfer.

#Packet Analysis and Insights
- HTTP packets included GET and POST requests, showing clear-text traffic between browser and web server.
- DNS packets included standard queries and responses, resolving domain names to IP addresses.
- TCP packets established connections with SYN, ACK flags, indicating session management.
- This exercise improved understanding of network traffic flow, protocol characteristics, and packet structure.

#Troubleshooting Insights
Packet capture demonstrated how Wireshark can be used to:
- Diagnose connectivity issues by identifying failed protocol handshakes.
- Detect unusual or unauthorized protocols on the network.

#Security Limitation
Wireshark could not decrypt encrypted HTTPS traffic unless provided with appropriate cryptographic keys.

#Conclusion
This exercise built foundational skills in packet analysis, protocol recognition, and network troubleshooting using Wireshark.
