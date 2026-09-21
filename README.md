# Md Sibbir Hossain

**AI/ML Researcher & Software Engineer · Explainable AI for Payment Integrity and Fraud Detection**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mdsibbirhossain/)
[![Google Scholar](https://img.shields.io/badge/Google%20Scholar-Publications-4285F4?logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?user=MMJRxLEAAAAJ)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0002--0795--4512-A6CE39?logo=orcid&logoColor=white)](https://orcid.org/0009-0002-0795-4512)
[![Zenodo](https://zenodo.org/badge/DOI/10.5281/zenodo.22869687.svg)](https://doi.org/10.5281/zenodo.22869687)

---

## 🎯 Mission
I design **explainable, real-time AI systems that protect U.S. payment systems from fraud**: card and digital payments in the financial sector, and public healthcare spending in Medicaid. My work connects published research, open-source software, and hands-on engineering inside a regulated U.S. healthcare payment environment.

### Why this problem matters
| Official source | Finding |
|---|---|
| Federal Trade Commission (2025) | Consumers reported **$12.5 billion** in fraud losses in 2024, up 25% in one year |
| FBI Internet Crime Complaint Center (2024 report) | **$16.6 billion** in reported cybercrime losses, up 33% |
| U.S. Government Accountability Office (GAO-24-105833) | Federal programs lose an estimated **$233–$521 billion per year** to fraud |

Fraud is increasingly **organized** (rings that coordinate across accounts, devices, and merchants) and **adaptive** (new tactics that models have never seen). My research targets both problems, and I build systems explainable enough for analysts and auditors to trust.

---

## 🔬 Research & engineering at a glance
- **Three published research papers** on AI for fraud detection, credit risk, and healthcare payment integrity
- **Editorial board member** and **journal peer reviewer**
- **Open-source research software** with archived, citable releases (DOI), CI-tested code, and reproducible experiments
- **Industry practice:** Software Engineer building Medicaid billing automation, EVV compliance tracking, and multi-payer authorization workflows at a New York home-care agency

---

## 🚀 Flagship work

### 1. FinGuard-XAI: real-time graph AI against coordinated and never-seen payment fraud
[![Repo](https://img.shields.io/badge/GitHub-finguard--xai-181717?logo=github)](https://github.com/sibbirhossain/finguard-xai) [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.22869687.svg)](https://doi.org/10.5281/zenodo.22869687)

Extends my 2025 published research into an open, working system that models payments as a live graph of cards, devices, merchants, and networks.

| Measured result (5 seeds, controlled benchmark) | Conventional ML | **FinGuard-XAI** |
|---|---|---|
| Detection quality (PR-AUC) | 0.70 | **0.93** |
| Legitimate customers wrongly flagged | 2.5% | **0.6%** (4× fewer false alarms) |
| Fraud types never seen in training | 6% caught | **34% caught** (dual-channel novelty alerting) |
| Detection under combined evasion attack | 84% (unstable) | **98%** |
| Scoring speed | | **< 5 ms per transaction** |

Explainable alerts · adversarial-robustness testing · drift monitoring · FastAPI + React · Colab notebooks · preprint

### 2. MedicaidGuard-XAI: explainable AI for Medicaid fraud and Electronic Visit Verification
[![Repo](https://img.shields.io/badge/GitHub-medicaidguard--xai-181717?logo=github)](https://github.com/sibbirhossain/medicaidguard-xai)

A statistically validated ML framework built on **real CMS (Centers for Medicare & Medicaid Services) data** to flag anomalous billing and visit-verification patterns in Medicaid, the program that funds most U.S. home-care services. Informed directly by my day-to-day engineering work on Medicaid billing and EVV compliance.
- Random Forest: **ROC-AUC 0.950**, F1 0.649 on real CMS data
- Published 2026 (peer-reviewed), with explainable outputs for program-integrity review

### 3. Auditable Credit Risk Intelligence (ACRIS)
A five-layer explainable-AI architecture that reconciles predictive performance with U.S. fair-lending and model-governance requirements: the **Equal Credit Opportunity Act (ECOA)**, the **Fair Credit Reporting Act (FCRA)**, and model risk management.

---

## 📄 Publications
1. **Safeguarding Public Healthcare Spending with Explainable AI:** A Statistically Validated Machine Learning Framework for Medicaid Fraud Detection and Electronic Visit Verification (2026). [DOI](https://doi.org/10.32996/jcsts.2026.5.3.4)
2. **Auditable Credit Risk Intelligence for the U.S. Financial System:** A Scalable Explainable-AI Framework Reconciling Predictive Performance with ECOA, FCRA, and Model Risk Governance. *Journal of Business and Management Studies* (2026)
3. **Detecting Financial Fraud in Real-Time Transactions Using Graph Neural Networks and Anomaly Detection Techniques.** *JEFAS* 7(6), 2025. [DOI](https://doi.org/10.32996/jefas.2025.7.6.1)

📚 Complete list and citations: [Google Scholar](https://scholar.google.com/citations?user=MMJRxLEAAAAJ)

---

## 🧭 Research direction (next 3–5 years)
- **Public-benchmark validation:** evaluating graph fraud detection on large public datasets and publishing reproducible benchmarks
- **Adaptive-adversary defense:** detection that stays reliable as fraudsters change tactics
- **Healthcare program integrity:** extending graph-based and explainable methods to Medicaid billing networks (providers, caregivers, visits, claims)
- **Trustworthy AI in regulated finance:** auditable models that meet fair-lending and model-risk expectations

---

## 🎓 Education
- **M.S. Computer Science**, The City College of New York (CUNY)
- **B.S. Computer Science & Engineering**, American International University-Bangladesh

## 🛠️ Tech stack
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white) ![PyG](https://img.shields.io/badge/PyTorch%20Geometric-3C2179?logo=pyg&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=white)

## 📫 Contact
Open to research collaboration with universities, financial institutions, and public-sector program-integrity teams.
[LinkedIn](https://www.linkedin.com/in/mdsibbirhossain/) · [ORCID](https://orcid.org/0009-0002-0795-4512) · [Google Scholar](https://scholar.google.com/citations?user=MMJRxLEAAAAJ)
