---
layout: post
title:  ""
date:   2018-09-17 14:02:08 -0400
categories: jekyll update
---

# 1.1 Introduction
TCP/IP is a protocol that came out of government research project in the 1960s.  By the 1990s it grew into the protocol that formed the internet and has become the de facto standard for networked communication.

# 1.2 Layering
TCP/IP is a layered protocol suite that has four different layers

|      Layer    |  Protocol     |
|---------------|---------------|
| Application   | Telnet, FTP, email, etc |
| Transport     | TCP, UDP |
| Network       | IP, ICMP, IGMP |
| Link          | device drivers |


1. **Link:** also known as the data link layer or network interface layer typically includes the device driver and the network card that interfaces with the wire
2. **Network:** also known as the internet layer handles the routing of packets throughout the network
3. **Transport:** handles the flow of data between two host for the application layer
  * *UDP:* provides unreliable communications between hosts.  Packets called datagrams are not garunteed to reach the other host so any reliability must be built in to the application layer
  * *TCP:* provides reliable communications between the two hosts using acknowlegment so that this is abstracted from the application layer
4. **Application:** handles the details for a particular application.  Examples include telnet, FTP, SNTP, and SNMP

