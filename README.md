# Big Fish in a Little Pond - Traffic Analysis Exercise (2024-09-04)

## Overview

This project involves a traffic analysis exercise based on a captured PCAP file simulating a network compromise. The goal is to identify suspicious behavior, extract Indicators of Compromise (IOCs), and understand the post-exploitation activities through forensic analysis using Wireshark.

## 🧪 How to Use This Exercise

### 1. Unzip the Folder

* Download and extract the archive to access the PCAP and exercise PDF file.

### 2. Open the PCAP File in Wireshark

* Use [Wireshark](https://www.wireshark.org/) to load the `.pcap` file and begin traffic inspection.

### 3. Analyze Network Traffic

* Focus on:

  * DNS queries and responses
  * HTTP GET/POST requests
  * TCP connections to external IPs
  * Any files or payloads transferred

### 4. Refer to the Exercise PDF

* Contains step-by-step questions and space for answers
* Use it to guide your analysis and findings

### 5. Run Python Code for SHA256 Hashing (if applicable)

* If you extract any files from the PCAP, use the provided Python script to compute their SHA256 hash values.


python sha256_hash.py extracted_file.exe


## Tools Used

* Wireshark
* Python (for hashing and decoding)
* Custom scripts for IOC extraction

## Author

Pradeep B wijerathna
Final Year Cybersecurity Student | Network Security & Ethical Hacking Enthusiast

## License

This project is for educational and research purposes only.

