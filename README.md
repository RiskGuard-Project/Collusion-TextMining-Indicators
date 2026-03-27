# Collusion-TextMining-Indicators
Risk indicators development in portuguese public procurement (https://doi.org/10.54499/2024.07601.IACDC)

The riskguard project integrates the development of two key indicators for public procurement using data from portuguese procurement contracts. 

## 🧠 Motivation

### Collusion and irregular behaviour in procurement is inherently difficult to detect due to:
- Lack of labeled data
- Legal and textual ambiguity

### RiskGuard addresses this by combining:
- Unsupervised learning (to discover latent structures)
- Text Mining techniques for procurement texts.

The project structure is as follows

RiskGuard/
│
├── Collusion/
│   │
│   ├── 1.Data_Preprocessing.ipynb                  # Data preprocessing of procurement contracts
│   │
│   ├── 2.Unsupervised_Approach.ipynb               # Construction of bid-rigging indicators
│   │
│   ├── 3.Arquivo.ipynb                  # Data collection & enrichment (e.g., Arquivo.pt)
│
├── Text analysis in public procurement/
│   ├── 0_EDA.ipynb                  # Exploratory Data Analysis of procurement data
│   │
│   ├── 1_indicators/                # Construction of risk indicators realted to exception regimes and the contractual object
│   │
│   ├── 2_scrape/                    # Data collection & enrichment with other procurement procedures
│
└── README.md
