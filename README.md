# Day5
Title: Network Traffic Analysis using Wireshark
Tool Used: Wireshark
Objective: To capture live network traffic and identify different network protocols.

Procedure
1) Installed Wireshark and started packet capture on the active Wi-Fi interface.
2) Visited several websites and performed a ping command to generate traffic.
3) Stopped the capture after 1 minute and applied protocol filters.
4) Identified multiple protocols (DNS, HTTP, TCP, ICMP).
5) Exported the captured data as a .pcap file.


Protocols Identified
   Protocol	                         Description	                                   Observation
1) DNS	Domain Name System –      translates domain names to IP addresses	     Queries to google.com and wikipedia.org observed
2) HTTP	Hypertext Transfer Protocol – used for web page requests	           GET and POST requests found in captured packets
3) TCP	Transmission Control Protocol – ensures reliable communication	       Established TCP handshakes between client and server
4) ICMP	Internet Control Message Protocol – used for ping requests	         Echo request/reply packets seen during ping test


Findings / Summary
1) Multiple protocols observed, confirming layered communication (Application → Transport → Network).
2) DNS and HTTP packets show website activity, while ICMP verifies connectivity.
3) Capture demonstrates how everyday internet activity involves multiple network protocols working together.


Outcome
✅ Successfully captured and analyzed live network packets.
✅ Gained practical understanding of protocol functions and communication flow.
✅ Exported capture as .pcap file for analysis and documentation.
