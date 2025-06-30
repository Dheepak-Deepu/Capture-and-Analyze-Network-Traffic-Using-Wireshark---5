# Capture-and-Analyze-Network-Traffic-Using-Wireshark---5

# Steps Performed
1. Opened Wireshark and selected the active Wi-Fi interface.
2. Started packet capture.
3. Browsed several websites and pinged `google.com`.
4. Stopped capture after 1 minute.
5. Applied filters: `http`, `dns`, `tcp`.
6. Analyzed packet summary and protocol types.


# Protocols Identified

| Protocol | Description                    | Number of Packets  |
|----------|--------------------------------|--------------------|
| TCP      | Transmission Control Protocol  | e.g., 100+         |
| DNS      | Domain Name System             | e.g., 20–30        |
| HTTP     | Web traffic (port 80)          | e.g., 40+          |
| ICMP     | Ping traffic                   | e.g., 10           |
| ARP      | Address Resolution Protocol    | e.g., 15           |


# Conclusion
The analysis confirmed multiple protocol interactions during browsing and ping activities. This task enhanced my skills in traffic capture and understanding network-layer communication.
