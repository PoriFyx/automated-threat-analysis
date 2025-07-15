## For Educational Purpose

# 🔐 Security Scanner — Automated Threat Analysis Workflow
🛠 Description
Security Scanner is a fully responsive web application that leverages AI workflow automation to analyze and evaluate potential threats associated with:

URLs
Domains
Public IP Addresses
File Hashes (MD5, SHA-1, SHA-256)

This project is part of my AI workflow automation, aimed at showcasing how front-end interfaces can be tightly integrated with automation tools like for dynamic, real-time threat intelligence and decision automation.

Users can input threat indicators (IOCs), and the app routes the data through a custom ai workflow, which:

Performs reputation checks via APIs
Extracts risk scores (malicious, suspicious, harmless, undetected)
Returns structured results and raw responses
Dynamically renders progress indicators using circular conic gradients

# 🚀 Features
✅ Real-time threat scanning
📡 Supports multiple IOC types: URL, Domain, IP, Hash
🎯 Input validation and UI feedback to ensure clean requests
🌀 Animated circular progress indicators for threat scores
🔄 Integration with ai workflows for backend processing
💡 Error handling modal for network and input issues
📊 Raw JSON/text result preview for transparency/debugging

# 🧠 AI Workflow & Automation Highlights
The scanner integrates with an ai webhook, acting as a real-time middleware between the UI and security APIs.
It routes requests based on input type, enriches the data, and responds with structured scoring.
The UI then parses and visualizes this data using intelligent score categorization logic.

# 📸 Sample Use Cases
A security analyst wants to quickly triage an unknown IP.
A developer needs to check if a file hash has been flagged in malware databases.
A non-technical user wants a visual snapshot of a domain's safety.

#LIVE DEMO
https://PoriFyx.github.io/security-scanner/
