
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
- Clicked the pen/notes icon to open Capture File Properties
 <img width="464" height="622" alt="GetImage" src="https://github.com/user-attachments/assets/e520a669-5d94-4c1f-83c7-b0f9d1157ea9" />

- It will display the Capture File Properties, on the capture file comments seccion will shows the flag 
<img width="1119" height="621" alt="GetImage (1)" src="https://github.com/user-attachments/assets/0234875d-bf17-4916-b87a-ffe47ea4ed32" />


**Answer:** TryHackMe_Wireshark_Demo

---

### 2. Packet Count

**Question:** What is the total number of packets?
<img width="1137" height="620" alt="GetImage (2)" src="https://github.com/user-attachments/assets/3f7dd92c-0f88-4bfd-a9b9-cc6245738bf5" />



**Answer:** 58,620

---

### 3. File Integrity

**Question:** What is the SHA256 hash value of the capture file?
<img width="1018" height="631" alt="GetImage (3)" src="https://github.com/user-attachments/assets/f7ba9d5a-d354-4766-a4d1-9c4f7c10b529" />


**Answer:**
f446de335565fb0b0ee5e5a3266703c778b2f3dfad7efeaeccb2da5641a6d6eb

---

## Packet Dissection — Packet #38

### 4. Protocol Analysis

**Question:** Use the "Exercise.pcapng" file to answer the questions. View packet number 38. Which markup language is used under the HTTP protocol? 
<img width="559" height="897" alt="GetImage (4)" src="https://github.com/user-attachments/assets/86c94e1f-7420-4d02-945a-fdc7b581c440" />


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
