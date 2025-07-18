# 🐚 reverse.shell_sniffing
This project demonstrates how reverse shell payloads are transferred and executed on a victim machine, while monitoring and analyzing network traffic using Wireshark.

> ⚠️ **Disclaimer**: This lab is intended strictly for **educational and ethical hacking** purposes. Do not use these techniques on unauthorized systems.

---

## 📌 Objective
To capture, inspect, and understand how reverse shell payloads behave on the network. This helps blue teamers recognize suspicious traffic and red teamers test payload delivery visibility.

---

## 🧰 Tools Used
- **Kali Linux** (Attacker)
- **Metasploitable / DVWA** (Victim)
- **Wireshark**
- **Netcat** / **msfvenom**
- (Optional) **Bettercap** or **Ettercap** for MITM scenarios

---

## 🧪 Lab Setup
| Component | IP Address | Role       |
|----------:|------------|------------|
| Kali      | 192.168.X.X | Attacker   |
| Metasploitable | 192.168.X.X | Victim |

- Both devices are on the same virtual NAT or bridged network.
- Wireshark is run on Kali to sniff traffic in real-time.

---
