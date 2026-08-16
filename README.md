\# 🎣 End-to-End Phishing Email Investigation \& Header Analysis



Investigated a malicious phishing email (.eml) to verify sender authenticity and extract threat indicators, simulating a real-world SOC/Incident Response workflow.



\## 🛠️ Tools Used

\- \*\*CyberChef\*\* – decoding obfuscated payloads (Base64/URL encoding)

\- \*\*AbuseIPDB\*\* – sending IP reputation lookup

\- \*\*VirusTotal\*\* – URL \& attachment hash verification



\## 📋 What I Did

\- Analyzed malicious email headers to verify \*\*SPF, DKIM, and DMARC\*\* alignment

\- Identified spoofed sender domains by tracing the `Received` header chain

\- Extracted malicious URLs and attachment hashes from the email

\- Decoded obfuscated payloads using CyberChef

\- Cross-referenced extracted indicators (IPs, URLs, hashes) with threat intelligence feeds (AbuseIPDB, VirusTotal) to confirm malicious activity



\## 📄 Full Report

Detailed findings — including header analysis, authentication results, extracted IOCs, threat intel verification, and recommendations — are documented in the full report:



📎 \*\*\[Phishing\_Investigation\_Report.pdf](./Phishing\_Investigation\_Report.pdf)\*\*



\## 📁 Repo Structure



├── Phishing\_Investigation\_Report.pdf # Full detailed investigation report

├── sample.eml # Sanitized phishing email sample

└── README.md



\---

\*This project was conducted in a controlled environment for educational/defensive security purposes. No malicious content is actively hosted or executed in this repository.\*

