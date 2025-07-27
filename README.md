# Hack The Box Machines

This repository contains write-ups and reports for Hack The Box machines.

## Repository Structure

- All reports are stored as PDF files in the root of the repository.
- Each PDF file is named after the corresponding machine.
- Inside each file, you will find a detailed step-by-step explanation of the exploitation process — from initial reconnaissance to flag capture.

## Tools Used


The following tools were used to solve the machines included in this repository.  
This list will be expanded as new machines are solved, and new tools are applied:

### Reconnaissance & Scanning
- **Nmap** – Port scanning and service/version detection  
- **RustScan** – Fast port scanner (can be used together with Nmap)  
- **Masscan** – Extremely fast port scanner  
- **Gobuster** – Directory and file brute-forcing  
- **Feroxbuster** – Recursive content discovery tool for web paths and files
- **ffuf** – Fast web fuzzer for discovering directories, files, and parameters

### Web Exploitation
- **Burp Suite** – Web proxy for analyzing and manipulating HTTP traffic  
- **SQLMap** – Automated SQL injection exploitation  
- **whatweb / Wappalyzer** – Web technology fingerprinting  

### Exploitation & Post-Exploitation
- **Metasploit** – Exploitation framework used for initial access and privilege escalation 
- **smbclient** – Interacting with SMB shares and enumerating accessible files
- **redis-cli** – Accessing exposed Redis instances and retrieving stored keys 

### Cracking & Passwords
- **John the Ripper / Hashcat** – Password hash cracking tools  
- **hydra / Medusa** – Login brute-force tools for SSH, FTP, HTTP, and other protocols  

### Miscellaneous
- **Wireshark** – Network traffic analysis and packet capture  
- **Tcpdump** – Command-line traffic sniffing (especially useful for pivoting and capturing data)  
- **MongoDB shell** – Interacting with exposed MongoDB instances  




## How to Read the Reports

Simply open the PDF file named after the machine you're interested in. Each report provides a clear breakdown of the entire pwned process.

---

**Note:** All machines in this repository were pwned on my own. Each solution was based either on prior experience or on studying the relevant tools
