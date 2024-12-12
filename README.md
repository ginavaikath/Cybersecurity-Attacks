# Cybersecurity Threat Analysis and Dataset Integration

## 1. Project Title
**Cybersecurity Threat Analysis and Dataset Integration**

## 2. Description
This project focuses on cybersecurity threat analysis by processing multiple datasets related to attacks, vulnerabilities, and user activity. The project integrates and cleans two distinct datasets, combining them into a unified source for analysis. The goal is to explore cyberattack patterns, identify trends in attack severity, and analyze the geographic distribution of attacks. By identifying attack types and their frequency over time, we aim to improve threat detection strategies.

## 3. Features
- Data cleaning and preprocessing for multiple datasets.
- Column alignment and dataset merging.
- Identification of attack patterns, types, and severity levels.
- Export of a unified, clean dataset for further analysis.
- Data visualization with graphs and charts for better insights into attack trends.

## 4. Overview
This project focuses on analyzing cybersecurity attack patterns using a comprehensive dataset of cyberattacks. By understanding the evolving tactics and trends, we aim to enhance threat detection, inform response strategies, and explore potential solutions to mitigate emerging risks in cybersecurity. The project involves combining data from two distinct sources, analyzing trends in attack severity, anomaly scores, attack types, and geographical origins, and uncovering insights into the evolving nature of cyber threats.

## 5. Key Features of the Datasets
- 40,000 records with 25 attributes.
- Data includes attack types, IP addresses, protocols, anomaly scores, and severity levels.
- Focus on examining the severity of attacks, anomaly scores, geographic origins, and types of cyberattacks.

## 6. Data Acquisition
We gathered data from two key sources:

### Dataset 1: Kaggle
This dataset provided a foundational set of records detailing various cyberattacks. It included attributes such as timestamps, attack types, and severity levels.

### Dataset 2: Center for Strategic and International Studies (CSIS)
CSIS tracks significant cybersecurity incidents, particularly targeting government agencies, defense sectors, and high-tech industries, along with economic crimes exceeding $1 million. We extracted additional data like timestamps, geo-location, user information, attack types, and severity levels.

## 7. Data Processing Steps
1. **Data Collection**: Data was gathered from Kaggle and CSIS websites.
2. **Cleaning and Formatting**: Removed missing or invalid entries and ensured consistency in attributes like timestamps, attack types, and severity levels.
3. **PDF Conversion**: Transformed the cleaned data from a PDF format to a CSV format with five main columns:
   - Timestamp: The time when the attack occurred.
   - Geo-location Data: The geographical location of the attack.
   - User Information: Information about the affected user or system.
   - Attack Type: The type of attack (e.g., DDoS, malware, phishing).
   - Severity Level: The severity of the attack (e.g., low, medium, high).
4. **Combining Datasets**: Merged the datasets into a unified source for analysis.

## 8. Data Analysis

### Approach
We used Python and various libraries for data analysis, including Pandas for data manipulation and Matplotlib/Seaborn for visualization.

### Key Analysis Goals
- **Identify Trends**: Analyze trends in attack severity, anomaly scores, and attack types over time.
- **Geographic Analysis**: Study the geographical distribution of cyberattacks to understand which regions are more vulnerable.
- **Attack Type Classification**: Categorize the attacks based on their types and severity to identify the most common threats.

## 9. Code Implementation
- Refer to the Jupyter Notebook: `Cybersecurity Attacks Project.ipynb`.

## 10. Key Findings
### Top Targeted Locations
- **Russia, China, and Unknown Locations** are the most targeted regions.
- **"Unknown" Locations** suggest sophisticated attack methods, including:
  - Use of botnets
  - Proxies
  - VPNs
  - Masking techniques

### Increase in Cyberattacks
- Significant rise in cyberattacks from 2016 to 2023, with a peak in 2023.
- A decline in 2024, potentially due to improved cybersecurity awareness and technologies.

### Severity of Cyberattacks
- Most attacks fall under "medium" severity, followed by "high" severity.

### Anomaly Scores Distribution
- Malware, DDoS, and intrusion attacks show diverse anomaly scores.
- Espionage and ransomware exhibit consistent patterns.

## 11. Challenges and Limitations
- Inconsistent timestamp formats.
- Missing values in key columns.
- Potential schema integration issues with external datasets.
- Lack of real-time data ingestion.

## 12. Future Work
- Automate data ingestion from real-time sources.
- Implement machine learning models for threat detection.
- Build interactive dashboards for real-time monitoring.

## 13. Dependencies
- Python 3.8+
- pandas
- numpy
- matplotlib
- seaborn
- openpyxl

## 14. Potential Users
- **Cybersecurity Researchers**: Analyze attack patterns and develop threat detection models.
- **IT Security Teams**: Improve incident response processes.
- **Academics and Students**: Use the dataset for educational and research purposes.
- **Government Bodies**: Inform cybersecurity policies and regulations.

## 15. Directory Structure

```plaintext
project_root/
├── Dataset1.csv                  # Raw and processed data files
├── data.pdf                      # Supplementary dataset in PDF format
├── Cyberattack_Dataset2.xlsx     # Raw and cleaned data from additional sources
├── Combined_Cybersecurity_Dataset.csv # Consolidated and processed dataset
├── Cybersecurity Attacks Project.ipynb # Jupyter notebook for analysis and visualization
├── README.md                     # This README file
├── presentation.pptx             # Final project presentation slides
└── Final Project Presentation.mp4 # Recorded presentation video
```

## 16. Acknowledgments
- Datasets from Kaggle and the Center for Strategic and International Studies (CSIS).
- Python libraries: pandas, numpy, matplotlib, seaborn, and openpyxl.
- Special thanks to our professor for this opportunity.

## 17. References
1. [Cybersecurity and Data Analysis Resources (VizSec)](https://vizsec.org/data/)
2. [CSIS Cyber Incident Database](https://www.csis.org/programs/strategic-technologies-program/significant-cyber-incidents)
3. [Awesome Cybersecurity Datasets on GitHub](https://github.com/shramos/Awesome-Cybersecurity-Datasets)
4. [UNB Cybersecurity Datasets](https://www.unb.ca/cic/datasets/index.html)
