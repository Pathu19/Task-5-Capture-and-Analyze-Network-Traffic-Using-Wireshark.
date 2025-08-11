# Task-5-Capture-and-Analyze-Network-Traffic-Using-Wireshark.
 To capture live network packets using Wireshark

**Wireshark Network Traffic Analysis**
The goal of this task was to capture live network packets using Wireshark, identify common protocols, and understand the basic flow of network communication.

**Procedure:**
Installed Wireshark along with Npcap for packet capturing.

Selected the active Wi-Fi interface to monitor live network traffic.

Started packet capture while performing activities such as:

Visiting various websites in a browser.

Running ping commands to external servers.

Stopped capture after approximately one minute.

Applied filters (dns, http, tcp) to isolate and examine specific types of traffic.

Identified at least three protocols from the captured packets.

Exported the capture file in .pcapng format for future reference and analysis.

**Protocols Identified**
**DNS (Domain Name System)**

Function: Resolves domain names (e.g., example.com) into IP addresses.

Observation: Queries were made to DNS servers before initiating HTTP/HTTPS requests.

**HTTP (Hypertext Transfer Protocol)**

Function: Facilitates communication between web browsers and servers in plain text.

Observation: Captured HTTP GET requests and corresponding responses, including headers and HTML content.

**TCP (Transmission Control Protocol)**

Function: Provides reliable, connection-oriented data transfer.

Observation: Noticed the standard three-way handshake (SYN → SYN-ACK → ACK) before data transfer began.

**Findings**
DNS lookups always occurred prior to web requests, showing the dependency on name resolution.

HTTP traffic displayed full request and response details, making it easy to analyze.

TCP ensured reliable packet delivery and reordering where necessary.

Encrypted HTTPS traffic appeared in the capture but its contents were not readable due to encryption.

**Conclusion**
This exercise provided practical exposure to real-time packet capturing, filtering, and protocol analysis. By understanding how these protocols operate and interact, it becomes easier to troubleshoot network issues and monitor communication patterns.


