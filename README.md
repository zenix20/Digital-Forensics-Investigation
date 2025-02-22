# Digital-Forensics-Investigation

# Digital Forensics Investigation Report

## Overview
This repository contains a comprehensive digital forensics investigation report covering multiple forensic techniques and tools. The report documents the analysis performed on various digital artifacts, including forensic disk images, memory dumps, network traffic captures, and mobile device images.

## Table of Contents
- [Tools Used](#tools-used)
- [Investigations Conducted](#investigations-conducted)
  - [Examining a Forensic Image with Autopsy](#examining-a-forensic-image-with-autopsy)
  - [Network Forensics using Wireshark](#network-forensics-using-wireshark)
  - [Memory Analysis with Autopsy](#memory-analysis-with-autopsy)
  - [Email Forensics](#email-forensics)
  - [Android and iPhone Analysis](#android-and-iphone-analysis)
  - [Velociraptor Server Investigation](#velociraptor-server-investigation)
  - [Malware and Bot Investigations](#malware-and-bot-investigations)
- [Conclusion](#conclusion)

## Tools Used
- **Autopsy** - Open-source digital forensics tool for examining disk images and memory dumps.
- **Wireshark** - Network protocol analyzer used for investigating network traffic.
- **Velociraptor** - Endpoint monitoring and digital forensics tool.
- **FTK Imager** - Tool for capturing and analyzing forensic images.
- **7-Zip** - File compression utility used for extracting forensic data.
- **ADB (Android Debug Bridge)** - Used for Android device forensics.
- **Sysmon** - Windows system monitoring tool for logging system events.

## Investigations Conducted

### Examining a Forensic Image with Autopsy
- Analysis of forensic disk images (.E01 format) to extract evidence.
- Identification of suspicious files and metadata.
- Extraction of file system artifacts and registry information.

### Network Forensics using Wireshark
- Analyzing packet captures (pcapng files) to extract credentials.
- Investigating encrypted communications and protocol analysis.
- Identifying attacker traffic patterns and malicious behavior.

### Memory Analysis with Autopsy
- Extraction of volatile memory data.
- Analysis of processes, network connections, and registry hives.
- Identification of malware artifacts within memory dumps.

### Email Forensics
- Investigation of harassing emails using header analysis.
- Tracing IP addresses and geolocation.
- Extracting metadata from SMTP communication logs.

### Android and iPhone Analysis
- Forensic acquisition and analysis of mobile devices.
- Extraction of call logs, messages, browser history, and application data.
- Rooting and analysis of Android Studio emulators.

### Velociraptor Server Investigation
- Deployment and configuration of Velociraptor on a Linux server.
- Monitoring Windows endpoints for forensic analysis.
- Detecting malicious activities and system intrusions.

### Malware and Bot Investigations
- Simulating malware infections and analyzing their behavior.
- Capturing network traffic and identifying C&C servers.
- Detecting persistence mechanisms and mitigating threats.

## Conclusion
This project provides an in-depth exploration of various digital forensic techniques using industry-standard tools. The investigation covered disk forensics, memory analysis, network forensics, and mobile device analysis, demonstrating practical applications for cybersecurity professionals.

---
For more details, refer to the full **Digital Forensics Investigation Report** included in this repository.

