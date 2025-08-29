# AI-ML-Assisted-Incident-Classification-and-Playbook-Generation

AI-Assisted Incident Classification & Playbook Suggestion.  
Trains models on CIC-IDS-2017 to classify incidents (DoS, Web Attacks, Brute Force, etc.) and generate contextual response recommendations with performance evaluation.

## Dataset
This project uses a **cleaned and concatenated version** of the CIC-IDS-2017 dataset.  

- Download the preprocessed dataset here: [Google Drive Link](https://drive.google.com/file/d/1V4f9KWXAQTBYLeQVTshIk_TXNWg_34cS/view?usp=drive_link)  
- The original CIC-IDS-2017 dataset can also be found at the [Canadian Institute for Cybersecurity](https://www.unb.ca/cic/datasets/ids-2017.html).  
- The code in this repository is written to work with the cleaned dataset provided above.

## Features
- Incident classification using Random Forest & XGBoost  
- Dynamic playbook generation with contextual awareness  
- Classification of incidents such as DoS, Web Attacks, Brute Force, Malware, Phishing, Unauthorized Access, etc.  
- Emphasis on bridging the gap between detection and automated response  

## Usage
1. Clone the repository  
   ```bash
   git clone https://github.com/UdyamanSuryanshi/AI-ML-Assisted-Incident-Classification-and-Playbook-Generation.git
   cd AI-ML-Assisted-Incident-Classification-and-Playbook-Generation

