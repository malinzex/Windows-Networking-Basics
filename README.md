# Windows Networking Basics

## Overview

This project documents my first hands-on networking practical as part of my cybersecurity learning journey.

I used the Windows Command Prompt to explore basic network configuration, test connectivity, and understand DNS resolution.

## Objectives

- Examine network configuration.
- Test network connectivity.
- Understand how DNS resolves domain names.

## Tools Used

- Windows Command Prompt
- Windows networking utilities

## Practical Exercises

### 1. IP Configuration – `ipconfig`

**Command:**
```cmd
ipconfig
```

**Purpose:**

Displays the computer's network configuration, including IP addresses, subnet masks, and default gateways.

**Findings:**

- Identified my active Wi-Fi network adapter.
- Examined its IPv4 address.
- Identified its subnet mask and default gateway.
- Observed other network adapters, including disconnected adapters.

### 2. Connectivity Testing – `ping`

**Command:**
```cmd
ping 8.8.8.8
```

**Purpose:**

Tests whether my computer can communicate with another device over an IP network.

**Findings:**

- Packets sent: 4
- Packets received: 4
- Packets lost: 0
- Packet loss: 0%
- Average response time: 57 ms

The test was successful, with all four packets receiving replies.

### 3. DNS Lookup – `nslookup`

**Command:**
```cmd
nslookup google.com
```

**Purpose:**

Queries a DNS server to find the IP addresses associated with a domain name.

**Findings:**

- Successfully resolved `google.com`.
- Retrieved IPv4 and IPv6 addresses.
- Identified the DNS server address used for the lookup.

## Key Lessons Learned

- IP addresses help identify devices on networks.
- Subnet masks define network boundaries.
- Default gateways provide routes to other networks.
- Ping helps test network reachability.
- DNS translates domain names into IP addresses.

## Conclusion

This practical helped me understand basic networking concepts through hands-on experience with Windows command-line tools.

## Screenshots

### 1. IP Configuration
![ipconfig](ipconfig.png)

### 2. Connectivity Test
![ping](ping.png)

### 3. DNS Lookup
![nslookup](nslookup.png)
