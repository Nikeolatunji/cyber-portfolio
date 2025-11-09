# Cyber Security Portfolio **Jr. SOC Analyst | CompTIA Security+ | Transfer Ready** --- ## 🚀 Projects (Live & Hands-On)
###1. **Splunk SIEM Dashboard** * > Detecting brute-force & suspicious traffic in real time > ![SIEM](siem.png) * 
# 2. **Public Vulnerability Report** *(in progress)* > CVE scan on bug-bounty target (BBC) > [bbc-vulns.txt] 
### 3.**Phishing Triage Playbook** *(in progress)* > Full incident response workflow > [phishing.md](phishing.md) *coming in 24h* ---
## 🔐 Certifications - **CompTIA Security+ (SY0-701)** | ID: [COMP001022689965] | Expires: [14/02/2028] ## 📍
Visa Status - **Transferable [H-1B / Skilled Worker] Visa** – No cap gap - Ready to relocate (UK/US) --- *Built from scratch — , just proof I can do the job.*

 *Splunk SIEM Dashboard* [LIVE]
> Detected *2000+ brute-force failures* from simulated Windows logs  
> SPL: source="OpenSSH.csv" index="openssh" "Failed password"
| rex field=_raw "from (?<src_ip>\d{1,3}(?:\.\d{1,3}){3}) port"
| stats count as attempts by src_ip
| sort -attempts
| head 10 
> [View PDF Report](splunk dashboard.png+splunk-report.pdf) | ![Dashboard](Brute-Force Detection with Splunk SIEM.png)
>
> **Public Vulnerability Report** *(in progress)* > CVE scan on bug-bounty target (BBC) > [bbc-clean-proof.png](bbc-enterprise-scan.pdf)
> # Enterprise Vulnerability Assessment – bbc.co.uk
>  **Researcher**: YOUR NAME **Date**: 09 Nov 2025
> **Tool**: Nuclei v3 – Kali Linux
>  **Scope**: BBC HackerOne public program (legal)
>  ## Scan Statistics
> • Templates loaded: 4,310
> • Requests sent: 8,454
> • Duration: 1m 9s
> • **Vulnerabilities found: 0**
> **Conclusion**: BBC maintains exceptional security hygiene.
> 
