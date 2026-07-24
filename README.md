# Wireshark Network Traffic Analysis

## Project Overview

This project documents a hands-on network traffic analysis lab performed using **Wireshark on Kali Linux**.

The objective was to capture live network traffic, apply protocol-specific display filters, and analyze **ICMP and DNS packets** at the packet level.

The lab demonstrates foundational network analysis skills relevant to **SOC analysis, network security, incident investigation, and troubleshooting**.

---

## Lab Environment

- **Operating System:** Kali Linux 2026.2
- **Virtualization:** Oracle VirtualBox
- **Packet Analyzer:** Wireshark 4.6.6
- **Network Interface:** eth0
- **Kali IPv4 Address:** 10.0.2.15/24
- **Default Gateway:** 10.0.2.2
- **External Test Host / DNS Resolver:** 8.8.8.8

---

## Objectives

The objectives of this lab were to:

- Verify the Wireshark installation
- Identify the active network interface
- Capture live network traffic
- Generate ICMP traffic using `ping`
- Filter and analyze ICMP packets
- Generate DNS traffic using `nslookup`
- Filter and analyze DNS packets
- Correlate network requests with their responses
- Interpret packet-level protocol information

---

# Lab Walkthrough

## 1. Verify Wireshark Installation

I first verified the installed version of Wireshark.

```bash
wireshark --version
