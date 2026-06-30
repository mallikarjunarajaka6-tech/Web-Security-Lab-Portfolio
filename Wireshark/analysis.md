## Lab 1: DNS Traffic Analysis with Wireshark
**Date**: 2026-06-30
**Interface**: Wi-Fi | **Filter**: dns

### Commands
nslookup google.com
nslookup github.com
ping 8.8.8.8

### Key Findings
- Captured DNS query: android.clients.google.com type A
- Response IPs: 142.251.221.110, 142.250.66.14, 142.250.193.174
- Protocol: DNS over UDP/53 via IPv6
- Transaction ID: 0x4dc9
