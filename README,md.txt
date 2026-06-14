# Network Traffic Analysis Using Wireshark

## Overview

This project demonstrates the analysis of live network traffic using Wireshark. The objective was to understand how modern network communication works by capturing and inspecting packets generated during web browsing and system activity.

## Objectives

* Capture live network traffic.
* Analyze DNS queries and responses.
* Investigate the TCP three-way handshake.
* Examine TLS/HTTPS communication.
* Identify domains using Server Name Indication (SNI).
* Develop practical packet analysis skills for cybersecurity and network troubleshooting.

## Tools Used

* Wireshark 4.6.6
* Windows 11
* Wi-Fi Network Interface

## Protocols Analyzed

* DNS
* TCP/IP
* TLS/HTTPS
* QUIC

## Analysis Performed

### 1. DNS Analysis

Applied the `dns` filter to inspect domain name resolution traffic. Observed DNS query and response packets and identified requested domains.

### 2. TCP Handshake Analysis

Applied filters to identify TCP SYN packets and examined the TCP three-way handshake process:

* SYN
* SYN-ACK
* ACK

### 3. TLS Analysis

Applied the `tls` filter to inspect encrypted HTTPS traffic. Analyzed:

* Client Hello
* Server Hello
* TLS Versions (TLS 1.2 and TLS 1.3)

### 4. SNI Inspection

Extracted Server Name Indication (SNI) information from TLS Client Hello packets and identified legitimate Microsoft service traffic.

## Key Findings

* Successfully captured and analyzed live network traffic.
* Observed DNS resolution processes.
* Investigated TCP connection establishment.
* Examined secure communication using TLS.
* Identified domains through SNI inspection.
* Gained hands-on experience with network packet analysis.

## Skills Demonstrated

* Network Traffic Analysis
* Packet Capture and Inspection
* DNS Analysis
* TCP/IP Fundamentals
* TLS/HTTPS Analysis
* Network Troubleshooting
* Cybersecurity Fundamentals

## Screenshots

Screenshots demonstrating DNS analysis, TCP handshake analysis, TLS traffic inspection, and SNI identification are included in the repository.

## Future Improvements

* Analyze HTTP traffic in a controlled environment.
* Investigate suspicious network traffic scenarios.
* Integrate packet analysis with SIEM tools such as Splunk.
* Perform malware traffic analysis using packet captures.

## Author

Ved Pandya

Cybersecurity Enthusiast | Network Security 
