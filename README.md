# Corporate Attack Surface Intelligence — GenuineFind Ltd.

## Overview
This project demonstrates a full corporate attack surface assessment for a fictional company, GenuineFind Ltd. It showcases the process of mapping public-facing assets, employee identities, cloud/hosting infrastructure, and metadata to simulate real-world reconnaissance activities used in penetration testing and threat intelligence.

## Objectives
- Identify and catalog all company digital assets: domains, subdomains, email addresses, and GitHub profiles.
- Simulate employee and identity mapping to demonstrate potential attack vectors.
- Extract metadata from publicly available documents to identify potential information leaks.
- Map hosting and cloud infrastructure to understand potential exposure points.
- Compile all findings into a structured intelligence report suitable for security analysis and executive review.

## Project Workflow
1. **Asset Creation:** Defined company domain, subdomains, sample employees, emails, GitHub profiles, and job listings.
2. **OSINT Mapping:** Simulated reconnaissance using `theHarvester` and other OSINT tools to build a comprehensive asset map.
3. **Metadata Analysis:** Extracted and documented document metadata to identify potential information leaks.
4. **Infrastructure Mapping:** Simulated cloud and hosting provider analysis.
5. **Reporting:** Consolidated all findings into [`final_intel_report.txt`](./final_intel_report.txt) to illustrate risk exposure and corporate visibility.

## Deliverables
- [`README.md`](./README.md)
- [`outputs/proof_log_clean.txt`](./outputs/proof_log_clean.txt)
- [`final_intel_report.txt`](./final_intel_report.txt)

## Key Takeaways
This project demonstrates how attackers can gather intelligence on corporate targets before engaging in more intrusive activities. It highlights the importance of managing digital footprint, securing employee data, and controlling document metadata to reduce organizational risk.
