# 🏥 FQHC Performance & Equity Analysis (2019–2023)
This project analyzes patient demographics and service trends from Federally Qualified Health Centers (FQHCs) across Texas and peer states (California, Massachusetts, New York, and Oregon) using HRSA Uniform Data System (UDS) data from 2019 to 2023. The goal is to support data-driven decisions for health equity planning and resource allocation.


## 📊 Project Goals

- Compare Texas FQHC performance to high-performing states (e.g., CA, MA, OR, NY, MN)
- Key Metrics Analyzed:
  Total patients served per year per state
  % adults aged 18–64
  % racial/ethnic minority patients
  % Hispanic/Latino patients
  These indicators were selected to highlight equity-relevant service delivery patterns.
- Provide visualizations and insights to inform public health strategy and funding decisions

## 🗂 Directory Structure

fqhc-performance-analysis/
│
├── data/
│ ├── raw/ # Raw ZIP or CSV files from HRSA UDS by state and year
│ └── processed/ # Cleaned or aggregated files
│
├── notebooks/
│ └── 01_eda_fqhc.ipynb # Main analysis notebook
│
├── output/
│ └── charts/ # Visualizations exported for reports/presentations
│
├── scripts/ # Optional Python scripts for data processing
│
├── requirements.txt # Python dependencies
└── README.md # Project overview (this file)

## 🔍 Data Source

All data used in this project comes from the U.S. Health Resources and Services Administration (HRSA):

🔗 [HRSA Data Portal – UDS Data Download](https://data.hrsa.gov/data/download)

**Topic**: Health Center Program  
**Years**: 2018–2023  
**Files**: State-level ZIP files containing clinical, demographic, financial, and quality metrics


### 📈 Output
Line charts and bar graphs comparing TX vs. other states over 5 years

Summary tables highlighting performance gaps and strengths

Visual materials for presentation to public health leadership

### 🤝 Contributing
This project is part of a graduate practicum and is not open for public contributions at this time.

### 📄 License
This repository is for educational and public health research purposes only. Please cite HRSA if using data derived from their downloads.
