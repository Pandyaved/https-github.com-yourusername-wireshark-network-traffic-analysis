# 🔍 Wireshark Network Traffic Analysis

**A cybersecurity project analyzing real network traffic to detect suspicious activity, inspect protocols, and understand packet-level communication.**

> Built by [Ved Pandya](https://github.com/Pandyaved) | B.Tech Cyber Security | Parul University

---

## 📌 About This Project

This project demonstrates hands-on network traffic analysis using Wireshark — one of the most widely used tools in cybersecurity. It covers real-world scenarios including DNS resolution, TCP handshakes, TLS inspection, and anomaly detection.

---

## 🔬 What Was Analyzed

| Protocol | What Was Captured |
|----------|-------------------|
| DNS | Domain resolution requests and responses |
| TCP | Three-way handshake (SYN, SYN-ACK, ACK) |
| TLS/HTTPS | Encrypted traffic inspection and certificate analysis |
| HTTP | Unencrypted web traffic and headers |
| ICMP | Ping requests and network reachability |

---

## ⚙️ Tools Used

| Tool | Purpose |
|------|---------|
| Wireshark | Packet capture and analysis |
| Kali Linux | Analysis environment |
| Nmap | Network scanning for traffic generation |

---

## 🎯 Key Findings

- Identified **DNS queries** leaking browsing data in plaintext
- Captured **TCP three-way handshake** showing connection establishment
- Inspected **TLS handshake** to verify certificate validity
- Detected **suspicious port scans** via unusual packet patterns
- Analyzed **HTTP vs HTTPS** traffic to highlight encryption importance

---

## 📁 Project Structure

```
wireshark-network-traffic-analysis/
├── captures/
│   ├── dns_analysis.pcapng
│   ├── tcp_handshake.pcapng
│   └── tls_inspection.pcapng
├── screenshots/
│   └── analysis_results/
├── reports/
│   └── traffic_analysis_report.pdf
└── README.md
```

---

## 🚀 How To Replicate

1. Install [Wireshark](https://www.wireshark.org/)
2. Open any `.pcapng` file from the `captures/` folder
3. Apply display filters:
```
dns          → Show only DNS traffic
tcp          → Show only TCP traffic
tls          → Show only TLS traffic
http         → Show only HTTP traffic
```

---

## 🎓 Skills Demonstrated

- Packet capture and deep packet inspection
- Protocol analysis (DNS, TCP, TLS, HTTP)
- Network anomaly detection
- Cybersecurity monitoring techniques

---

## 📬 Connect

- GitHub: [github.com/Pandyaved](https://github.com/Pandyaved)
- LinkedIn: [linkedin.com/in/ved-pandya-2b32bb387](https://linkedin.com/in/ved-pandya-2b32bb387)
