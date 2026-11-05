# Day 01 – Networking Fundamentals

**Date:** 5 November 2026  
**Learning Journey:** 90-Day Cybersecurity Roadmap  
**Career Goal:** SOC Analyst / Cybersecurity Analyst

## 1. Introduction

Today, I started my cybersecurity learning journey by reviewing networking fundamentals and practising essential Windows networking commands.

My goal is to strengthen my technical knowledge and develop practical skills relevant to SOC Analyst roles.

## 2. Computer Networks

A computer network is a group of connected devices that communicate and share information.

**Types of Networks:**

- **LAN (Local Area Network):** Connects devices within a small area, such as a home or office.
- **WAN (Wide Area Network):** Connects networks across larger geographical areas.

## 3. IP Addresses

An IP address identifies a device's network interface and supports communication across networks.

**Private IP:** Used within private networks.

Example: `192.168.1.10`

**Public IP:** Globally routable on the internet.

I also learned about subnet masks, default gateways and Network Address Translation (NAT).

## 4. TCP vs UDP

**TCP (Transmission Control Protocol):**
- Connection-oriented
- Reliable data delivery
- Maintains data order

**UDP (User Datagram Protocol):**
- Connectionless
- Low overhead
- No built-in delivery guarantee
- Commonly used for real-time applications

## 5. Common Network Ports

| Port | Service |
|---|---|
| 22 | SSH |
| 53 | DNS |
| 80 | HTTP |
| 443 | HTTPS |
| 3389 | RDP |

## 6. DNS

DNS (Domain Name System) translates domain names into IP addresses.

I used `nslookup` to examine how a domain name resolves to an IP address.

## 7. Windows Networking Commands

### IP Configuration

`ipconfig`

Used to view IP address information, subnet masks and default gateways.

### DNS Lookup

`nslookup google.com`

Used to query DNS records and identify IP addresses associated with a domain.

### Connectivity Testing

`ping google.com`

Used to test whether a destination responds to ICMP Echo Requests.

### Network Route

`tracert google.com`

Used to examine the network path towards a destination.

### Active Connections

`netstat -ano`

Used to display active connections, listening ports and associated process IDs.

### Process Identification

`tasklist /FI "PID eq 1234"`

Used to identify a running process associated with a PID.

I successfully identified a Chrome process using its PID.

## 8. HTTP vs HTTPS

HTTP is a protocol used for web communication.

HTTPS uses TLS encryption to protect communication between a browser and a website.

I checked HTTPS connection information using Google Chrome.

## 9. Cybersecurity Relevance

Networking fundamentals are essential for SOC Analysts because they help with:

- Understanding network traffic
- Investigating suspicious IP addresses
- Identifying active network connections
- Analysing DNS activity
- Recognising common ports and protocols
- Supporting security incident investigations

## 10. Personal Reflection

Today's session helped me revise networking concepts and practise useful Windows commands.

My previous Linux administration experience provides a foundation for understanding systems and networking. I want to build on this experience by developing stronger security monitoring and incident investigation skills.

## Day 1 Progress

**Status:** Completed

**Practical Exercises:** 7

**Next Topic:** Networking fundamentals revision and introduction to the OSI model.
