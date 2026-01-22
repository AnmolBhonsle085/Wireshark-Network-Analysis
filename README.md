# Wireshark Network Traffic Analysis

##  Project Overview
This project demonstrates basic network traffic analysis using Wireshark. 
The goal is to capture and analyze live network packets to understand how 
DNS, TCP, and HTTP protocols work in real-world scenarios.

---

##  Objectives
- Capture live network traffic
- Analyze DNS queries and responses
- Observe TCP 3-way handshake (SYN, SYN-ACK, ACK)
- Analyze HTTP request and response traffic
- Identify normal network behavior using Wireshark filters

---

##  Tools Used
- Wireshark
- Windows OS
- Web Browser (Chrome / Firefox)

---

##  Methodology
1. Started live packet capture on active network interface.
2. Generated traffic by visiting websites.
3. Applied Wireshark display filters such as:
   - `dns`
   - `tcp`
   - `tcp.flags.syn == 1`
   - `http`
4. Captured and analyzed packets related to DNS, TCP, and HTTP.
5. Documented observations using screenshots.

---

##  Screenshots Included
- DNS Query and Response Analysis
- TCP 3-Way Handshake (SYN, SYN-ACK, ACK)
- HTTP GET Request and HTTP 200 OK Response

Screenshots are available in the `/screenshots` folder.

---

##  Observations & Findings
- DNS successfully resolved domain names to IPv4 addresses.
- TCP connections were established using a proper 3-way handshake.
- HTTP traffic was visible in plain text, showing GET requests and responses.
- No suspicious or malicious traffic was observed during analysis.

---

##  Key Learnings
- Understanding how DNS works at packet level
- Identifying TCP handshake packets in Wireshark
- Difference between HTTP and HTTPS traffic
- Importance of encrypted communication

---

##  Project Structure
wireshark-network-analysis/
│
├── screenshots/
│ ├── dns-analysis.png
│ ├── tcp-3way-handshake.png
│ └── http-get-200ok.png
│
├── report/
│ └── Wireshark_Project_Report.pdf
│
└── README.md


##  Conclusion
This project helped in understanding real network communication and packet 
analysis using Wireshark. It provides a strong foundation for roles such as 
SOC Analyst and Network Security Analyst.

##  Author
ANMOL BHONSLE
