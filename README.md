# Computational Efficiency Reporting Gaps in Deep Learning for Time Series Forecasting: A Systematic Review of 202 Studies and Implications for Industrial Deployment

**PRISMA-compliant systematic review** examining computational efficiency (FLOPs, latency, memory, energy, carbon footprint, etc.) in deep learning models for time series forecasting.

- **Initial search**: 2640+ records  
- **Final included for full-text review**: 202 studies  
- **AI-assisted screening**: Three models (`gpt-4o-mini`, `deepseek-v4-flash`, `qwen-3.6`) with human validation

---

## Protocol Information

- **Version**: 1.4 (Updated: 2026-07-09)
- **Registration**: OSF (link will be added)
- **Authors**: Ali Shahzadi¹, Hamid Reza Deihimfar¹
- **Affiliation**: Faculty of Electrical and Computer Engineering, Semnan University, Iran
- **DOI (Protocol)**: Will be added after Zenodo upload

---

## Repository Contents

- `/protocol/` — Full protocol document (PDF + DOCX)
- `/data/` — Screening results and extracted data
- `/code/` — Python scripts for AI-assisted screening and analysis
- `/supplementary/` — Search strings, PRISMA checklist, quality assessment form, data dictionary
- `/figures/` — PRISMA flow diagram and other visualizations (will be added)

---

## Data Files

- `screening_results_full.xlsx` — Complete screening results from 3 AI models
- `included_studies_public.csv` — **Public version** (bibliographic information only)
- `data_dictionary.md` — Description of all variables
- `FINAL_FULLTEXT_ARTICLES.xlsx` — List of 202 studies selected for full-text review

---

## Data Availability

The **full extracted dataset** (detailed accuracy and efficiency metrics for 202 studies) will be made publicly available in this repository and on OSF **upon acceptance of the manuscript**.

**Currently available**:
- A public version containing only bibliographic information and basic metadata (`included_studies_public.csv`).

The complete dataset (including RMSE, FLOPs, parameters, latency, energy consumption, hardware details, etc.) is available upon reasonable request to the corresponding author or after publication.

---

## Reproducibility

- All AI screening was performed using documented prompts and three models (`gpt-4o-mini`, `deepseek-v4-flash`, `qwen-3.6`).
- Human validation and inter-rater reliability (Cohen’s kappa) were applied.
- Full search strings, data extraction form, and quality assessment checklist are provided in `/supplementary/`.
- See `/code/README.md` for setup and usage instructions.

---

## Citation (Protocol)

Deihimfar, H. R., & Shahzadi, A. (2026). Beyond Accuracy: A Systematic Review of Computational Efficiency in Deep Learning Models for Time Series Forecasting – Protocol v1.4. OSF. [DOI will be added]

---

## License

This repository is licensed under **CC BY 4.0** (Attribution 4.0 International).

You are free to share and adapt the material as long as you give appropriate credit.

---

**Last updated:** 26 June 2026
