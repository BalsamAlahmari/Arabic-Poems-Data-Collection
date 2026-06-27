# Rawaa-Hijazi

## 1. Project Overview & Goals
**Purpose:**  
This project aims to collect, extract Arabic poems—specifically Hijazi poetry—from various textual sources, including online archives and scanned books. The goal is to build a structured dataset suitable for natural language processing (NLP) tasks such as topic modeling, classification, and stylistic analysis.


**Key Deliverables:** 
- Web scraping script for collecting poem from ADAB web
- OCR pipeline to extract Arabic text from scanned books 
- Cleaned and structured dataset ready for NLP tasks

## 2. Project Structure

```text
HijazePoems/
├── data/
│   ├── raw/                    # Unprocessed text files and OCR outputs 
│   ├── processed/              # poems datase
│   └── samples                 # Sample data for quick testing
│
├── notebooks/                  # All experiments conducted
├── src/
│   ├── scraping.py             # Web scraping scripts
│   ├── extract_text.py         # OCR extraction from scanned books
│
├── requirements.txt            # Dependencies for Python environment
└── README.md                   # Project overview and documentation
```

## 3. Data Documentation
**Raw data:**

Includes scanned books and raw text scraped from online sources. Files may contain noise such as diacritics, page numbers, or scanning errors.

**Processed Data:**

Cleaned poem texts with consistent formatting. Unwanted characters removed, and verses are split and normalized for analysis.
```

##  Code Availability

The complete implementation, trained models, and datasets are maintained in a private repository.

This public repository is intended to present the project's objectives, methodologies, system architecture
```
## 📄 Copyright

© 2025 Development Data Center. All rights reserved.

The complete source code, trained models, datasets, and all implementation details are the intellectual property of the Development Data Center and are maintained in a private repository. Therefore, they are not publicly available.
