# 🔐 Task 4: Setup and Use a Firewall (Windows & Linux)

## 🎯 Objective
Configure and test basic firewall rules on both Windows and Linux systems to control network traffic and improve system security.

## 🧰 Tools Used
- Windows Defender Firewall with Advanced Security
- UFW (Uncomplicated Firewall) on Kali Linux

## 🪟 Windows Steps
- Opened Windows Firewall GUI
- Added inbound rule to block port **23** (Telnet)
- Verified blocking using `telnet localhost 23`
- Removed the rule to restore original state

## 🐧 Linux (Kali) Steps
- Installed and enabled **UFW**
- Added rule to deny port **23**: `sudo ufw deny 23`
- Verified with `telnet localhost 23`
- Allowed SSH (port **22**) for remote access
- Deleted test rule to restore state

## 📁 Deliverables
- Screenshots showing firewall rules on both systems
- Terminal output showing UFW status and telnet test

## 📝 Summary
Firewalls filter traffic based on defined rules. Blocking or allowing ports helps protect systems from unauthorized access and attacks. UFW and Windows Firewall provide simple yet powerful control over traffic.
