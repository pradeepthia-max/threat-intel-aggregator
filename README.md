# Threat Intelligence Aggregator & Parser

**IBM SkillsBuild Cyber Security BootCamp 2026 Project**  
**Author:** PRADEEPTHI ARE  
**Institution:** Malineni Perumallu Pharmacy College  

---

## 📌 Project Overview
The **Threat Intelligence Aggregator & Parser** is an automated Python-based tool designed to ingest, sanitize, deduplicate, and format Indicators of Compromise (IoCs) such as IP addresses, domains, and file hashes. It standardizes threat data into a structured format suitable for integration with SIEM, SOAR, and threat-hunting platforms.

## 🛠️ Technologies Used
- **Python 3.10+**
- **Pandas** (Data manipulation & deduplication)
- **Regex** (Indicator validation)
- **JSON & STIX 2.1 Schema** (Output formatting)

## 📁 Repository Structure
```text
├── PRADEEPTHI_ARE_ThreatIntelligenceAggregator.ipynb  # Main Project Jupyter Notebook
├── PRADEEPTHI_ARE_ProjectReport.docx                  # Full Project Documentation
├── requirements.txt                                    # Python Dependencies
└── README.md                                           # Project Setup & Overview
```

## 🚀 Setup & Execution Instructions

1. **Clone or Download the Repository**
   ```bash
   git clone https://github.com/your-username/threat-intel-aggregator.git
   cd threat-intel-aggregator
   ```

2. **Install Required Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Jupyter Notebook**
   ```bash
   jupyter notebook PRADEEPTHI_ARE_ThreatIntelligenceAggregator.ipynb
   ```

## 📊 Dataset & Mock Feeds
The project utilizes structured mock feeds representing threat telemetry data (IPv4, Domains, SHA-256 hashes) for testing ingestion and deduplication pipelines.

---
*Submitted for IBM SkillsBuild Cyber Security BootCamp 2026 | BharatCares*
