# Biomedical Semantic Audit

This repository contains the computational framework and structural audit data for the study: 
*"Quantifying Semantic Attrition: An Architectural Audit of Biomedical Knowledge Organization Systems"*.

## Project Overview
This study investigates the systemic information loss (semantic attrition) that occurs when clinical data is mapped from polyhierarchical clinical ontologies (SNOMED CT) to monohierarchical administrative registries (ICD-11).

## Repository Structure
- **/src**: Python ingestion scripts using NLM UMLS REST API.
- **/data**: Structural matrices for Maximum Taxonomic Depth and Mean Parent Degree.
- **/notebooks**: Analysis and visualization of the 'Tracer Triad' scenarios.

## Reproducibility
To replicate the structural metrics, please provide your NLM UMLS API Key in `src/config.py`. 
Detailed instructions are available in the repository documentation.

---
*Developed for the Journal of Biomedical Informatics (2026).*
