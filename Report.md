📑 VPN Privacy Lab — Report

Name: SHASHI PRAKASH
Date: 03/10/2025

🎯 Objective

The purpose of this lab was to understand how a Virtual Private Network (VPN) enhances privacy and security by:

Masking the real IP address and location.

Encrypting internet traffic to prevent eavesdropping.

Observing the trade-offs in speed and accessibility when using VPNs.

2. 🛠️ Tools & Setup

VPN Client: ProtonVPN 

Operating System: Windows

Verification Tools:

curl and ipinfo.io for IP checks

WhatIsMyIPAddress.com

DNSLeakTest.com

Speedtest.net
 / speedtest-cli

3. 🔄 Step-by-Step Process
🔹 Step 1: Baseline (Before VPN)

Checked my public IP: XXX.XXX.XXX.XXX

Location shown: [India]

Speed test results: Download: 222 kbps | Upload: 6.7kbps | Ping: XX ms


🔹 Step 2: Connect to VPN

Logged in to ProtonVPN and connected to Romania.

Connection status: Connected


🔹 Step 3: After VPN Connection

New public IP: 149.102.239.231

Location shown: Romania

Speed test results: Download: 800 B/s | Upload: 80 B/s | Ping: XX ms


🔹 Step 4: DNS & Encryption Check

DNS leak test: ✅ Passed — DNS requests routed through VPN.

Encryption confirmed: ProtonVPN used [WireGuard / OpenVPN / IKEv2] protocol.

Browser showed HTTPS lock for encrypted traffic.


🔹 Step 5: Disconnect & Compare

Disconnected VPN and repeated IP/speed test.

IP returned to original, speed improved.


4. 📊 Results Summary
Condition	Public IP	Location	Download Speed	Upload Speed	Ping
Before VPN	XXX.XXX.XXX	, INDIA	222 kbps	6.7kbps	XX ms
With VPN	149.102.239.231	 Romania 800 bps	80bps	XX ms
After Disconnect	Original IP	Original Loc	
5. 🔍 Analysis

IP Masking: The VPN successfully changed my visible IP and location.

Encryption: All traffic was tunneled through ProtonVPN’s encrypted connection, protecting against local ISP or Wi-Fi monitoring.

Performance Trade-off: There was a noticeable speed drop (approx. XX%). This is expected since data is routed through an extra server.

DNS Safety: DNS requests were handled by the VPN provider, reducing risk of DNS leaks.

Trust Factor: Security ultimately depends on the VPN provider’s no-log policy and jurisdiction.

6. ✅ Benefits Observed

Anonymity by hiding real IP.

Protection on public Wi-Fi networks.

Ability to access region-restricted content.

Encrypted tunnel prevents simple data sniffing.

7. ⚠️ Limitations & Concerns

Free VPN tiers limit server locations and speed.

Performance impact noticeable during browsing and streaming.

True privacy depends on provider transparency (e.g., logging policies).

Some websites block known VPN IPs.

8. 📝 Conclusion

This lab clearly demonstrated that VPNs play a vital role in enhancing privacy and security. By encrypting internet traffic and masking the real IP, they protect users from surveillance and tracking. However, free VPNs come with limitations such as fewer server choices, slower speeds, and potential trust concerns.

Final Note: VPNs should be considered one layer of security — not a complete privacy solution. For strong online privacy, combine VPN use with secure browsing habits, HTTPS, and good digital hygiene.

9. 📎 Attachments

Screenshots of the process are attatched in the screenshots folder.
