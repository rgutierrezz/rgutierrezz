# Rafael Gutierrez
www.linkedin.com/in/rafaelgutierrezjr 


## Objective
Skilled in network configuration, system administration, and security tooling with hands-on experience managing VPNs, firewalls, DNS services, and intrusion detection systems on Linux-based servers. Proficient in troubleshooting connectivity, routing, and security issues using command-line tools and open-source software. Committed to applying practical solutions to enhance network reliability and system security, with a strong foundation in Linux server management, network protocols, and automated monitoring. Continuously adapting to emerging technologies to address real-world IT and network challenges.

## Skills

| Skill                                         | Associated Project         |
|-----------------------------------------------|----------------------------|
| Linux Server Administration  | [Homemade VPN](https://github.com/rgutierrezz/homemade-vpn) , [UFW Firewall Setup](https://github.com/rgutierrezz/homemade-firewall)|
| Encrypted VPN Tunnel Setup and Routing   | [Homemade VPN](https://github.com/rgutierrezz/homemade-vpn)|
| DNS Filtering and Threat Blocking         | [DNS Sinkhole](https://github.com/rgutierrezz/dns-sinkhole)|
| Firewall Configuration and Port Access Control       | [UFW Firewall Setup](https://github.com/rgutierrezz/homemade-firewall)|
| Intrusion Detection and Packet Inspection                 | [Snort Intrusion Detection System (IDS)](https://github.com/rgutierrezz/IDS-using-Snort)|
| Network Traffic Monitoring with CLI Tools   | [Snort Intrusion Detection System (IDS)](https://github.com/rgutierrezz/IDS-using-Snort)|

## Tools


### Network
- WireGuard (for creating encrypted VPN tunnels)
- UFW (for configuring firewall rules and traffic filtering)
- BIND9 (for managing DNS resolution and creating sinkholes)
- dig (for testing DNS responses)
- Wireshark (for monitoring and analyzing network traffic)
- Snort (for real-time network intrusion detection)
- curl (for testing HTTP traffic and DNS leaks)
- ping (for testing connectivity)

### System/Endpoint
- SSH (for secure remote access to servers)
- Ubuntu Server/DigitalOcean VPS (for hosting all self-managed services)
- Homebrew (for managing software installations on macOS)

### Security/Monitoring
- Snort (for detecting suspicious/unauthorized packets)
- BIND9 logging (for observing DNS query patterns)
- iptables logging (for packet filtering and auditing)

## Certifications
- CodePath Intermediate iOS Development – Spring 2023
- CompTIA Network+ (In progress)

## Projects
### 🔐 [Homemade VPN](https://github.com/rgutierrezz/homemade-vpn)
A secure, self-hosted VPN built using WireGuard on a cloud-based Ubuntu VPS.

- Configured WireGuard for encrypted tunneling of internet traffic
- Enabled IP forwarding and NAT using `iptables`
- Generated and managed cryptographic key pairs for client-server authentication
- Troubleshooted DNS and routing issues post-deployment
- Verified anonymity using `curl` and DNS leak checks

---

### 🔥 [UFW Firewall Setup](https://github.com/rgutierrezz/homemade-firewall)
Configured a firewall using UFW (Uncomplicated Firewall) on a Linux VPS.

- Enabled default-deny policy with explicit allow rules for SSH, HTTP, and HTTPS
- Secured remote server access while ensuring web availability
- Tested access rules and verified port restrictions using browser and CLI tools

---

### 🛡️ [DNS Sinkhole](https://github.com/rgutierrezz/dns-sinkhole)
Set up a DNS sinkhole using BIND9 to block malicious domains.

- Configured a recursive DNS server to intercept and redirect queries
- Created a zone file to sinkhole `badsite.com` and redirect it to `0.0.0.0`
- Verified sinkhole success with `dig` and browser testing

---

### 👁️ [Snort Intrusion Detection System (IDS)](https://github.com/rgutierrezz/IDS-using-Snort)
Deployed Snort 3 on macOS to monitor and log suspicious network traffic.

- Installed Snort using Homebrew and created a basic ICMP detection rule
- Captured ping traffic using `ping` and verified alerts in real time
- Parsed and interpreted Snort logs to confirm packet detection accuracy
