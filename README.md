
# Networking Task 01 Report

**Intern Name:** Seema
**Task:** Understanding Your Network Environment
**Date:** June 2026

## Task Objective

The objective of this task was to understand the basic components of a computer network, identify the network configuration of my device, and perform basic network connectivity tests.

## Part A: Network Information

The following network details were collected using the `ipconfig /all` command:

| Network Detail         | Value           |
| ---------------------- | --------------- |
| Hostname (Device Name) | LAPTOP-RO30QS6M |
| IPv4 Address           | 192.168.1.61    |
| MAC Address            |                 |
| Default Gateway        | 192.168.1.1     |
| DNS Server             | 192.168.1.1     |

Screenshots of the command output are included in the Screenshots folder.

## Part B: Basic Networking Concepts

### What is an IP Address?

An IP (Internet Protocol) Address is a unique numerical address assigned to a device connected to a network. It allows devices to communicate with each other over the internet or a local network.

### What is a MAC Address?

A MAC (Media Access Control) Address is a unique hardware identifier assigned to a network adapter. It helps identify devices within a local network.

### What is a Default Gateway?

A Default Gateway is a network device, usually a router, that forwards traffic from a local network to other networks, including the internet.

### What is DNS?

DNS (Domain Name System) converts website names such as google.com into IP addresses that computers use to locate and connect to websites.

### Difference Between Public IP and Private IP

| Public IP               | Private IP                           |
| ----------------------- | ------------------------------------ |
| Assigned by ISP         | Assigned by Router                   |
| Used on the Internet    | Used within a local network          |
| Globally unique         | Can be reused in different networks  |
| Accessible from outside | Not directly accessible from outside |

## Part C: Basic Network Diagram

```text
Internet
   │
   ▼
Wi-Fi Router
IP: 192.168.1.1
   │
   ▼
Laptop (LAPTOP-RO30QS6M)
IP: 192.168.1.61
```

A graphical network diagram has been included in the repository.

## Part D: Network Connectivity Test

### Commands Executed

```cmd
ipconfig
ping google.com
tracert google.com
```

### Results

#### Was the ping successful?

Yes. The ping was successful and all 4 packets were received with 0% packet loss.

#### How many hops were shown?

The traceroute displayed 13 hops before reaching Google's server.

#### What is the purpose of traceroute?

Traceroute is used to track the route taken by data packets from a source device to a destination server. It helps identify network paths, delays, and connectivity issues.

### Connectivity Summary

* Packets Sent: 4
* Packets Received: 4
* Packet Loss: 0%
* Average Ping Time: 123 ms
* Total Hops: 13

## Files Included

* Screenshots
* Network Diagram
* Command Outputs
* Answers to Questions
* README.md

## Conclusion

This task provided hands-on experience with network configuration, IP addressing, DNS, MAC addresses, and network troubleshooting tools. By using commands such as ipconfig, ping, and tracert, I gained a better understanding of how devices communicate over a network and access internet resources.
