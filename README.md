# Real-Time Phishing Email Analysis & Incident Response

## Project Overview

This project demonstrates a practical SOC-style phishing email
investigation and incident response workflow in a controlled lab
environment.

A simulated phishing email was created and analyzed to identify
suspicious indicators, inspect email headers, investigate URLs, analyze
an attachment, calculate a SHA-256 hash, verify reputation using
VirusTotal, collect evidence, and provide a final analyst verdict.

## Project Objectives

-   Identify common phishing indicators
-   Analyze suspicious email content and headers
-   Examine SPF, DKIM, and DMARC information
-   Investigate suspicious URLs safely
-   Generate and analyze SHA-256 file hashes
-   Perform attachment reputation analysis
-   Collect Indicators of Compromise (IOCs)
-   Preserve investigation evidence
-   Produce an analyst verdict

## Tools Used

-   Mozilla Thunderbird
-   Gmail
-   VirusTotal
-   Windows PowerShell
-   Email Header Analysis
-   SHA-256 Hashing

## Investigation Workflow

### 1. Phishing Email Simulation

A controlled phishing-style email was created for cybersecurity
training. The test used common social-engineering indicators such as
urgency, an account suspension warning, a request for verification, and
an external URL.

### 2. Email Header Analysis

Email headers were reviewed to investigate sender/recipient information,
Return-Path, Message-ID, Received headers, SPF, DKIM, and DMARC.

### 3. URL Analysis

The URL used in the controlled simulation was investigated using
VirusTotal and handled as a safe lab artifact rather than blindly
opening an unknown link.

### 4. Attachment Analysis

The test attachment `Invoice_Test.txt` was analyzed using file
identification, SHA-256 hashing, and VirusTotal reputation analysis.

### 5. Threat Intelligence Analysis

VirusTotal was used to check the test attachment against multiple
security engines. The observed lab result was **0/59 detections**. A
clean VirusTotal result alone does not guarantee that an unknown file is
safe; it was one data point used in this controlled investigation.

## Analyst Verdict

**Final Classification: BENIGN TEST / PHISHING SIMULATION**

The investigation demonstrated phishing triage, social-engineering
indicator identification, email header analysis, URL reputation
analysis, SHA-256 hashing, attachment reputation analysis, IOC-oriented
investigation, evidence collection, and incident response documentation.

## Evidence

Detailed screenshots and investigation evidence are available in:

**Real_Time_Phishing_Email_Analysis_Strong_Evidence.pdf**

## Skills Demonstrated

-   SOC Analysis
-   Phishing Investigation
-   Email Security
-   Incident Response
-   Threat Intelligence
-   Email Header Analysis
-   SPF / DKIM / DMARC Analysis
-   VirusTotal
-   SHA-256 Hashing
-   IOC Analysis
-   Security Documentation

## Key Learning

This project improved my understanding of how a SOC analyst investigates
suspicious emails by combining email inspection, header analysis, URL
and attachment reputation checks, file hashing, evidence preservation,
and analyst decision-making.

## Disclaimer

This project was performed only in a controlled lab environment for
cybersecurity education and portfolio development. No real users were
targeted, no credentials were collected, and no malicious payloads were
used.
