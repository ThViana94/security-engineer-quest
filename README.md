# Security Analysis Report

This repository contains the results of a cybersecurity analysis conducted on network traffic data. The analysis includes detailed findings, visualizations, and mitigation recommendations.

---

## Files in This Repository

### Main Report
- **[Response-HomeWork.md](./Response-HomeWork.md)**: The main report in English detailing the findings and recommendations.
- **Attack Graphs**:
  - [Attack Distribution by Type](./attack_distribution_en.png)
  - [XSS Details](./xss_details_en.png)
  - [LFI Details](./lfi_(local_file_inclusion)_details_en.png)
  - [SQL Injection Details](./sql_injection_details_en.png)
  - [Command Injection Details](./command_injection_details_en.png)

### Additional Data
- **[Malicious Requests by Country](./malicious_requests_by_country.csv)**: A CSV file showing the distribution of malicious requests by country.

---

## Portuguese Version (Versão em Português)

- **[Resposta-HomeWork.md](./Resposta-HomeWork.md)**: Relatório principal em português detalhando as descobertas e recomendações.
- **Gráficos de Ataques**:
  - [Distribuição de Ataques por Tipo](./attack_distribution.png)
  - [Detalhes de XSS](./xss_details.png)
  - [Detalhes de LFI](./lfi_(local_file_inclusion)_details.png)
  - [Detalhes de SQL Injection](./sql_injection_details.png)
  - [Detalhes de Command Injection](./command_injection_details.png)

> **Disclaimer:** The Portuguese version of the report was created for reference purposes. It provides the same findings and recommendations as the English version but is tailored for Portuguese-speaking stakeholders.

---

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

---

## Recommendations

- Implement input validation and output encoding.
- Use a Web Application Firewall (WAF) for automated protection.
- Restrict country access based on business policies.

For more details, refer to the [main report in English](./Response-HomeWork.md) or the [Portuguese version](./Resposta-HomeWork.md).
