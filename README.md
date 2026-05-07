# BTEMF: Blockchain‑Based Transparent Evidence Management Framework for Phishing Attacks in FinTech



## 📌 Overview

Phishing attacks cost the global FinTech industry over **$12 billion annually**, with a single incident averaging **$1.6 million**. Digital evidence (malicious URLs, fraudulent email headers, transaction logs) collected from such attacks must be preserved in a verifiable **chain of custody** to be legally admissible in court and before financial regulators.  

Current detection systems store evidence in centralised databases without cryptographic integrity verification. This makes evidence vulnerable to insider tampering and prevents trusted cross‑institutional sharing.  

**BTEMF** (Blockchain‑based Transparent Evidence Management Framework) solves this by integrating:

- 🔷 **Ethereum smart contracts** – for automated validation and immutable anchoring  
- 📦 **IPFS** – decentralised off‑chain storage of full evidence files  
- 🔒 **SHA‑256 hashing** – deterministic tamper detection  

The framework consists of **five core components**: incident capture, evidence preprocessing, blockchain ledger, smart contract validation, and regulatory reporting.

## 🎯 Key Results

| Metric | Target | Achieved |
|--------|--------|----------|
| Evidence Integrity Rate (EIR) | 100% | 100% ✅ |
| Tamper Detection Rate (TDR) | 100% | 100% ✅ |
| Avg. Confirmation Latency | 12–30 s | 20.58 s ✅ |
| Throughput (35 parallel channels) | >100 rec/min | 102 rec/min ✅ |
| Chain‑of‑Custody Completeness (CCCS) | 100/100 | 100/100 ✅ |

- **Gas cost** ≈ 0.001 ETH per submission (≈ $1.50–$3.00)  
- **Resilience** against tampering, replay attacks, and unauthorised submissions (100% detection)

Reproduce all results
Open notebooks/btemf_analysis.ipynb in Google Colab or Jupyter.

Run all cells to regenerate every graph and metric table.

📚 Datasets
Dataset	Records	Use in project	Original link
PhiUSIIL Phishing URL Dataset	235,795 URLs	Load testing, tamper detection	UCI Repository
Ethereum Phishing Transaction Network	13.5M edges, 1,165 phishing nodes	Chain‑of‑custody testing	Kaggle – XBlock
Full citations and download instructions are in data/dataset_links.md.

📄 Research Paper
The final IEEE‑style research paper is available in the docs/ folder.
Download PDF

Overleaf source
https://www.overleaf.com/project/69e3838710cc5d35a73908ea

Google Colab notebook
https://colab.research.google.com/drive/1Au2H7Nb3Iy6wW2bxd2jHufHC8rpDlK85?usp=sharing

Github Link
https://github.com/Hudaimran12/BTEMF-Evidence-Management

Google Site Link:
https://sites.google.com/view/blockchain-basedtransparentevi/home?authuser=0
