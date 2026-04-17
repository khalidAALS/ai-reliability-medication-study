# AI Reliability in Medication Decision Systems

## Paper

DOI: https://doi.org/10.5281/zenodo.19342171  
arXiv: https://arxiv.org/abs/2604.01449  
Zenodo: https://zenodo.org/records/19342172  

## Overview

This repository contains the experimental implementation supporting the paper:

**When AI Gets It Wrong: Reliability and Risk in AI-Assisted Medication Decision Systems**

This project demonstrates how different types of AI errors — false negatives, false positives, and dosage errors — can lead to significantly different levels of risk in healthcare contexts.

## Key Insight

The results highlight that aggregate performance metrics can obscure high-risk failure modes, particularly in safety-critical domains such as healthcare.

## Contents

- Simulated dataset of medication decision scenarios  
- Analysis of error types  
- Visualisation of error distributions  

## Results

The analysis focuses on how different error types contribute to risk, with emphasis on:
- False negatives (missed treatments)  
- False positives (unnecessary treatments)  
- Dosage errors (incorrect treatment levels)  

### Error Distribution

![Error Distribution](outputs/figures/error_distribution.png)

The distribution highlights how different error types contribute unevenly to overall system risk.

## How to Run

Install dependencies:

```
pip install -r requirements.txt
```

Run the notebook:

```
analysis.ipynb
```

## Reproducibility

This repository provides the dataset and notebook used to simulate AI decision-making scenarios and analyse error types.

## Citation

If you use this work, please cite:

Alsayed, K. A. (2026). *When AI Gets It Wrong: Reliability and Risk in AI-Assisted Medication Decision Systems.*

```bibtex
@article{alsayed2026ai_reliability,
  title={When AI Gets It Wrong: Reliability and Risk in AI-Assisted Medication Decision Systems},
  author={Alsayed, Khalid Adnan},
  year={2026},
  doi={10.5281/zenodo.19342171}
}
```

## Author

Khalid Adnan Alsayed
