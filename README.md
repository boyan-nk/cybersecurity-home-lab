# Cybersecurity Home Lab

This project demonstrates a simple isolated cybersecurity laboratory environment built for networking and cybersecurity fundamentals.

## Setup

* Ubuntu Server VM
* Kali Linux VM
* Internal VirtualBox network (labnet)

## Network

* Private isolated network (labnet)
* No external internet exposure
* Manual IP configuration

## Network Topology

```text
                   Cybersecurity Home Lab

┌─────────────────────┐
│    Kali Linux VM    │
│                     │
│ IP: 192.168.56.10   │
│                     │
│ • Wireshark         │
│ • Ping Testing      │
│ • Traffic Analysis  │
└──────────┬──────────┘
           │
           │ Internal Network
           │ (labnet)
           │
┌──────────▼──────────┐
│   Ubuntu Server VM  │
│                     │
│ IP: 192.168.56.11   │
│                     │
│ • Linux Server      │
│ • Network Target    │
│ • Administration    │
└─────────────────────┘

Environment:
• VirtualBox
• Isolated Lab Network
• No External Internet Exposure
```

## Activities

* Network connectivity testing (ping)
* Packet capture and analysis using Wireshark
* Basic Linux system interaction and configuration

## Tools Used

* VirtualBox
* Ubuntu Server
* Kali Linux
* Wireshark

## Skills Demonstrated

* Linux Administration
* Network Configuration
* Virtualization
* Packet Analysis
* Troubleshooting
* Technical Documentation

## What I Learned

* Basic networking concepts (IP, communication, ping)
* Virtual machine infrastructure and isolation
* Network traffic analysis and packet inspection
* Linux system fundamentals
