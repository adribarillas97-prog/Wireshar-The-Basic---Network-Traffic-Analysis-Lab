# Wireshar-The-Basic---Network-Traffic-Analysis-Lab

# Wireshark: The Basics — Network Traffic Analysis Lab

## Overview
Hands-on Wireshark lab completed on TryHackMe.
Analyzed a real packet capture file to practice file inspection,
packet dissection, and protocol analysis.

## Tools Used
- Wireshark
- TryHackMe AttackBox
- PCAP file: Exercise.pcapng

---

## Lab Walkthrough

### 1. Capture File Inspection

**Question:** Read the capture file comments. What is the flag?

**Steps:**
- Opened Exercise.pcapng in Wireshark
- <img width="464" height="622" alt="GetImage" src="https://github.com/user-attachments/assets/0f3236e6-35ce-4dfc-9055-b894fb324850" />

- Clicked the pen/notes icon to open Capture File Properties
- Found the flag in the Capture File Comments section

**Answer:** TryHackMe_Wireshark_Demo

---

### 2. Packet Count

**Question:** What is the total number of packets?

**Answer:** 58,620

---

### 3. File Integrity

**Question:** What is the SHA256 hash value of the capture file?

**Answer:**
f446de335565fb0b0ee5e5a3266703c778b2f3dfad7efeaeccb2da5641a6d6eb

---

## Packet Dissection — Packet #38

### 4. Protocol Analysis

**Question:** Which markup language is used under the HTTP protocol?

**Answer:** eXtensible Markup Language (XML)

---

### 5. Packet Arrival Date

**Steps:**
- Selected packet #38
- Clicked on the Interface ID dropdown to view frame details

**Answer:** 05/13/2024

---

### 6. TTL Value

**Steps:**
- Expanded Internet Protocol Version 4 section in packet details

**Answer:** 47

---

### 7. TCP Payload Size

**Answer:** 424 bytes

---

### 8. E-Tag Value

**Answer:** 9a01a-4696-7e354b00

---

## Key Takeaways
- Learned to inspect capture file metadata and verify
  file integrity using SHA256 hashing
- Practiced packet dissection across multiple protocol
  layers: Ethernet, IP, TCP, HTTP
- Identified HTTP headers including TTL, payload size,
  and e-tag values
- Built foundational skills for analyzing real network
  traffic in SOC environments
