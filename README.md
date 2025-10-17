# DFRWS Longitudinal Analysis (2002–2025)

This repository contains the data, code, and LaTeX sources for a longitudinal study of the DFRWS ecosystem across USA, EU, and APAC venues (2002–2025). We combine LLM-assisted metadata extraction with manual validation to analyze 527 papers, tool practices (UA/CA/EA), venue/domain trends, and subdomain evolution.

> **Highlights**
> - Corpus: **527** papers (66 null; 1,501 paper–tool instances; 1,435 with actions)
> - Tool actions: **UA 64.3% (922)**, **CA 28.8% (414)**, **EA 6.9% (99)**
> - Created tools by DFRWS authors: **396/414 (95.7%)**
> - Domains (cumulative by 2025): **CF 142, SF 148, NF 63, DF 55, KS 38, IoT 31**

---
## Environment
- Python 3.10+
  (pandas, numpy, matplotlib)
## Repository Structure

## Main script
- **dfrws_llm_current** `main.py`

## Key input files (data/) 
- `tools_new_expanded.csv.xlsx` (IT HAS ALL PAPER-TOOL instances)
- `results_combined_prompts_new.csv`   (IT HAS ALL METADATA, DF VS AF AND DOMAINS)
- `cdf_all_plus_top6_cumulative_counts.csv`
- `cdf_all_plus_top6_yearly_counts.csv`
- `discipline_trend_by_year_all.csv`
- `subdiscipline_yearly_trends_top15.csv`
- `venue_discipline_matrix.csv`
