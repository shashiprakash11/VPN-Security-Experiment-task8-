# VPN-Security-Experiment-task8-
Exploring the role of VPNs in privacy & amp; secure communication. Includes setup steps, screenshots, and findings.”
# 🌐 VPN Privacy Lab

> Understanding how Virtual Private Networks (VPNs) help protect privacy and enable secure communication.

## 🎯 Objective
The goal of this project was to:
- Explore how VPNs change IP address and location visibility.
- Verify traffic encryption using simple tools and tests.
- Measure the performance trade-offs (speed before/after VPN).
- Reflect on VPN benefits and limitations.

## 🛠️ Tools Used
- **VPN Clients:** ProtonVPN 
- **Verification Tools:** WhatIsMyIPAddress, DNSLeakTest, Speedtest.net, `curl`
- **OS:** WINDOWS

## 📸 Screenshots
Screenshots of IP change, connection status, and speed tests are in the [`/screenshots`](./screenshots) folder.  

## 📑 Report
The detailed step-by-step report is available in [REPORT.md](./REPORT.md).  
It includes:
- Setup steps  
- IP/Speed comparisons  
- DNS leak check results  
- Benefits & limitations analysis  

## 📚 Key Learnings
- VPNs successfully mask IP and change perceived location.
- Traffic is encrypted (TLS + VPN tunnel).
- Free VPN tiers have speed/data limitations.
- VPN privacy depends on provider trust and policies.

## 🚀 How to Reproduce
1. Sign up for a free VPN (ProtonVPN/Windscribe).
2. Install the VPN client and connect to a server.
3. Run `curl https://api.ipify.org` before and after connection.
4. Compare IP results and run speed tests.
5. Document findings and screenshots.

## 🔒 Notes
- Sensitive account details are excluded from screenshots.
- No VPN credentials/config files are uploaded.
- This repo is for **educational purposes** only.



