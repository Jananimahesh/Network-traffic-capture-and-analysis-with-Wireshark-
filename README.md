# Network-traffic-capture-and-analysis-with-Wireshark
## AIM:
To capture and analyze network traffic using Wireshark in order to observe protocols, packets, and potential anomalies.
## Requirements:
- **Hardware:**
    - Computer with internet access
    - Network adapter (Ethernet/Wi-Fi)
- **Software:**
    - Wireshark (latest stable version)
    - Sample PCAP files (optional for offline analysis)
## Architecture:
```mermaid
flowchart TD
    A[Network Interface Card] --> B[Wireshark Packet Capture Engine]
    B --> C[Packet Decoder & Protocol Analyzer]
    C --> D[Packet Display & Filtering Interface]
    D --> E[Investigator Analyzes Network Data]
    E --> F[Findings: IPs, Ports, Protocols, Anomalies]
```
## DESIGN STEPS:
### Step 1:
Install Wireshark on the system.


### Step 2:
Launch Wireshark and select the network interface (Ethernet/Wi-Fi).

### Step 3:
Start the capture, apply filters (like http, tcp, ip.addr == x.x.x.x) to analyze specific traffic, and stop the capture after observing relevant data.
### Step 4:
**Analyze traffic to identify:**
  - Source & Destination IP addresses
  - Protocols (HTTP, DNS, TCP, UDP, etc.)
  - Suspicious activities (e.g., unusual ports, repeated requests).
## PROGRAM:
Wireshark Packet Capture and Filter Usage

## OUTPUT:
Captured Packets with Protocol Analysis and Detailed Packet Info
A. Capturing Traffic in Wireshark

<img width="343" height="166" alt="image" src="https://github.com/user-attachments/assets/b78aed3d-11cf-4fb6-80af-528fcbd04fa7" />


<img width="384" height="190" alt="image" src="https://github.com/user-attachments/assets/02f8c0b4-91f8-4c03-b661-0f96160b0729" />



<img width="385" height="180" alt="image" src="https://github.com/user-attachments/assets/8e05b7aa-dc9a-446c-8ed8-e0f15e2b34d9" />


<img width="255" height="184" alt="image" src="https://github.com/user-attachments/assets/21e2f063-0c44-4074-b8ff-f1f478f3959e" />


## RESULT:
Network traffic was successfully captured and analyzed using Wireshark.
