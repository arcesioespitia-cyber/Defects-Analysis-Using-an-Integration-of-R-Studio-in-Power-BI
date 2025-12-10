# Cap Defects Quality 4.0 — Reproducible R + Power BI Workflow

This repository contains all data, code, and reproducibility artifacts from the study:

**“Quality Control in Beverage Production – Cap Defects Analysis Using an Integration of R-Studio in Power BI”**

## Contents
- `data/`: Raw or simulated datasets for full reproducibility.
- `R/`: Complete R scripts used in the study (p-charts, OC curves, Gage R&R, capability indices, mixed models).
- `powerbi/`: ETL scripts and configuration setup for Power BI R visuals.
- `reproducibility/`: Instructions, session info, and supplementary files.
- `manuscript/`: Revised manuscript and reviewer response.

## How to Run
1. Install R and required packages:
   ```r
   install.packages(c("qcc", "ggplot2", "irr", "lme4"))
