# Anatomical Dataset Curation using Large Language Models

## Project Overview
This repository contains resources for a research project focused on developing and implementing a novel approach to curating anatomical datasets using Large Language Models (LLMs). The project addresses the critical challenge of standardizing complex anatomical terminology through a hybrid curation pipeline that combines semantic embedding techniques with LLM-based decision making.

## Research Objectives
- Develop a hybrid curation methodology that leverages bio-specific embeddings and LLM contextual analysis
- Implement and evaluate automated curation pipelines for anatomical terminology
- Create standardized datasets that adhere to FAIR (Findable, Accessible, Interoperable, Reusable) principles
- Optimize computational resource usage for efficient curation of large-scale anatomical datasets

## Repository Structure
- `/data` - Data storage and processing scripts
  - `/raw` - Original anatomical terminology from FaceBase
  - `/processed` - Curated and standardized datasets
  - `/embeddings` - Bio-specific vector embeddings
- `/code` - Implementation of the curation pipeline
  - `/embedding` - Bio-specific embedding generation
  - `/llm` - LLM prompting and curation logic
  - `/evaluation` - Metrics and evaluation tools
- `/docs` - Documentation and research materials
  - `/methodology` - Detailed approach documentation
  - `/results` - Research outcomes and analyses

## Data Sources
The primary data source for this project is anatomical terminology from FaceBase.org, accessed through their Deriva API. The project works with both standardized anatomical terms and their variations to develop and evaluate curation methodologies.

## Methodology
The research employs a three-phase approach:
1. Data Acquisition and Preparation - Collection and standardization of anatomical datasets
2. Variation Generation - Creation of valid anatomical term variations for testing
3. Hybrid Curation - Implementation of embedding-based similarity with LLM contextual analysis

