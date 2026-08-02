# Data for: Affordances in Ambient Intelligence Interaction — A Systematic Literature Review

This repository contains the raw data underlying the systematic literature review (SLR) presented in:

> **Affordances in Ambient Intelligence Interaction: A Systematic Literature Review**
> *International Journal of Human–Computer Interaction* (under review)

The dataset is provided to ensure transparency and reproducibility of the review process, allowing readers and reviewers to verify every step from identification to final inclusion.

## Repository contents

| File | Description |
|------|-------------|
| `SLR_rawdata.xlsx` | Complete raw dataset from the SLR, organised across two worksheets (see below). |

### Worksheet 1 — `Data extraction`

Structured data extracted from each of the **42 included studies**, following the extraction template reported in Table 3 of the paper. This is the synthesised dataset that underpins the results in Section 4.

| Column | Content |
|--------|---------|
| `ID` | Study identifier (matches reference numbering where applicable) |
| `Authors` | Author(s) of the study |
| `Document Title` | Full title |
| `Year` | Publication year |
| `Database` | Source database (ACM DL, IEEE Xplore, Scopus, WoS, ScienceDirect, SpringerLink, T&F) |
| `DOI` | Digital Object Identifier |
| `Theoretical Focus` | How the study defines / uses affordance |
| `Domain` | Application domain (e.g. Smart Home, Healthcare, Workplace) |
| `Sub-domain` | Fine-grained category |
| `Technologies` | Technologies applied or addressed |
| `Strategies` | Design and development approach |
| `Evaluation Methods` | Evaluation and statistical methods employed |

### Worksheet 2 — `Selection Process`

The complete screening record for **every record** identified in the search, documenting its trajectory through the review pipeline. This single worksheet captures both the PRISMA flow and the quality scoring in one place.

| Column | Content |
|--------|---------|
| `Database` | Source database |
| `Title` | Record title |
| `Year` | Publication year |
| `Records screened by keywords` | Passed the "affordance" keyword filter (6,969 → 328) |
| `Screened by title and abstract` | Passed title/abstract screening against inclusion criteria |
| `Final` | Included in the final set of 42 |
| `Score` | Quality assessment score (0–5 scale, see Section 3.3 of the paper) |
| `Exclusion Tag` | Reason for exclusion, where applicable (Contextual Mismatch, Lack of Theoretical Contribution, Theoretical Redundancy, Ineligible Document Type, Full-text Unavailability) |
| `Authors` | Record authors |

## How these data map to the paper

| Paper element | Where to look |
|---------------|---------------|
| PRISMA flow diagram (Figure 1) | `Selection Process` — counts at each stage |
| Inclusion / exclusion criteria (Table 2) | `Selection Process` — `Exclusion Tag` column |
| Data extraction form (Table 3) | `Data extraction` — column structure |
| Summary of reviewed studies (Table 4) | `Data extraction` — 42 included rows |
| Quality assessment protocol (Section 3.3) | `Selection Process` — `Score` column |
| Paradigm comparison evidence (Table 9) | `Data extraction` — `Theoretical Focus`, `Strategies` |

## Methodology summary

- **Databases searched:** ACM DL, IEEE Xplore, Scopus, Web of Science, ScienceDirect, SpringerLink, Taylor & Francis Online
- **Search period:** 2000 – September 2025
- **Records identified:** 6,969
- **After keyword filter:** 328
- **After deduplication:** 286
- **After title/abstract screening:** 107
- **Studies included in synthesis:** 42
- **Reviewers:** Two independent reviewers; conflicts resolved by consensus or a third reviewer

Full methodological detail is provided in Section 3 of the paper.

## Citation

If you use these data, please cite the associated paper:

```
Li, Y., Dong, Y., & Yue, Y. (2026). Affordances in Ambient Intelligence Interaction:
A Systematic Literature Review. International Journal of Human–Computer Interaction
(under review).
```

## Contact

**Corresponding author:** Yuji Dong — yuji.dong02@xjtlu.edu.cn
School of Internet of Things, Xi'an Jiaotong-Liverpool University, Suzhou, China
