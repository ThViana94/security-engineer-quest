# Security Analysis Report

This repository contains the results of a cybersecurity analysis conducted on network traffic data. The analysis includes detailed findings, visualizations, and mitigation recommendations.

## Files in This Repository

### Main Report
- **[Response-HomeWork.md](./Response-HomeWork.md)**: The main report detailing the findings and recommendations.
- **Attack Graphs**:
  - [Attack Distribution by Type](./attack_distribution_en.png)
  - [XSS Details](./xss_details_en.png)
  - [LFI Details](./lfi_(local_file_inclusion)_details_en.png)
  - [SQL Injection Details](./sql_injection_details_en.png)
  - [Command Injection Details](./command_injection_details_en.png)

### Additional Data
- **[Malicious Requests by Country](./malicious_requests_by_country.csv)**: A CSV file showing the distribution of malicious requests by country.

## Summary of Findings

1. **Analyzed Data**:
   - Total IPs: 18,589
   - Total Requests: 30,000
   - Malicious IPs Identified: 452

2. **Highlighted Attack Types**:
   - Cross-Site Scripting (XSS)
   - Local File Inclusion (LFI)
   - SQL Injection
   - Command Injection

## Recommendations

- Implement input validation and output encoding.
- Use a Web Application Firewall (WAF) for automated protection.
- Restrict country access based on business policies.

For more details, refer to the [main report](./Response-HomeWork.md).
