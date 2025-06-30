# 🧪 Network Traffic Analysis using Wireshark

This project documents a basic packet capture and analysis exercise performed using **Wireshark**, a popular network protocol analyzer. The goal was to observe real-time traffic, identify various protocols, and export the findings.

---

## 📋 Steps Performed

1. **Installed Wireshark** on a Windows/Linux system.
2. **Started capturing packets** on the active network interface (Wi-Fi/Ethernet).
3. **Generated network traffic** by:
   - Browsing to a few websites.
   - Pinging a public DNS server (`ping 8.8.8.8`).
4. **Stopped the capture** after approximately one minute.
5. **Filtered packets by protocol** using Wireshark’s display filter bar:
   - `http` for HTTP traffic
   - `dns` for DNS queries
   - `tcp` for general TCP connections
6. **Identified at least 3 protocols** from the captured traffic.
7. **Exported the capture** as a `.pcap` file via `File > Save As`.
8. **Summarized findings** and analyzed key packet details.

---

## 📦 Files

- `capture.pcap` – The exported packet capture file.
- `summary.txt` – Summary of identified protocols and observations.
- `README.md` – This documentation.

---

## 🔍 Identified Protocols

| Protocol | Description                         | Purpose                     |
|----------|-------------------------------------|-----------------------------|
| **DNS**  | Domain Name System                  | Resolving domain names to IP addresses |
| **TCP**  | Transmission Control Protocol       | Reliable transport layer protocol |
| **HTTP** | HyperText Transfer Protocol         | Web communication protocol  |

---


## ✅ Tools Used

- **Wireshark** – Network traffic capture and analysis
- **Command Prompt / Terminal** – For ping operations
- **Web browser** – For generating HTTP traffic

---

## 📚 How to Open `.pcap` File

1. Install [Wireshark](https://www.wireshark.org/download.html).
2. Open Wireshark and go to `File > Open`.
3. Select `capture.pcap` to view the traffic analysis.

---


