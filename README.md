# SOC Lab 07 — Suspicious DNS Traffic Analysis

## Table of Contents
1. [Executive Summary](#executive-summary)
2. [Lab Objectives](#lab-objectives)
3. [Environment Overview](#environment-overview)
4. [Detection Workflow](#detection-workflow)
5. [Traffic Analysis](#traffic-analysis)
6. [Detection Engineering Insights](#detection-engineering-insights)
7. [Evidence](#evidence)
8. [Conclusions](#conclusions)
9. [Next Steps](#next-steps)

---

## Executive Summary

This lab focuses on capturing and analyzing DNS traffic to understand how domain name resolution appears in packet captures.

DNS is one of the most common protocols observed in enterprise environments and is frequently used by both legitimate applications and malicious activity. Security analysts must be able to identify normal DNS behavior and recognize suspicious patterns that may indicate reconnaissance, malware communication, or data exfiltration.

In this lab, DNS traffic will be generated and captured using Wireshark. The captured traffic will then be analyzed to identify DNS queries, responses, and protocol behavior relevant to SOC investigations.

This lab demonstrates how analysts inspect DNS activity and build foundational network visibility skills for threat detection.

---

## Lab Objectives

- Generate DNS traffic in a controlled environment
- Capture DNS queries and responses using Wireshark
- Identify key DNS protocol fields
- Analyze normal DNS lookup behavior
- Recognize how DNS traffic may appear during suspicious activity
- Develop packet analysis skills relevant to SOC operations

---

## Environment Overview

**Operating System:** Ubuntu Linux (Virtual Machine)

**Tools Used**

- Wireshark
- `nslookup`

**Network Setup**

- Localhost and external DNS resolution
- Single VM environment

---

## Detection Workflow

## Traffic Analysis

## Detection Engineering Insights

## Evidence

All screenshots are stored in the repository and demonstrate DNS query generation and packet-level analysis.

![DNS Capture](dns-capture.png)

![DNS Query Terminal](dns-query-terminal.png)

![DNS Packet Analysis](dns-packet-analysis.png)

## Conclusions

## Next Steps
