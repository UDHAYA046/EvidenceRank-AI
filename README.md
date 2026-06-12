# EvidenceRank AI

AI-powered candidate discovery and ranking system designed for large-scale recruitment workflows.

## Overview

EvidenceRank AI processes candidate profiles and ranks applicants using an evidence-first scoring framework.

The system combines:

- Technical Fit Scoring
- Behavioral Hireability Analysis
- Risk Detection
- Hidden-Gem Discovery
- Pairwise Re-Ranking
- Explainable AI Reasoning

## Dataset

- 100,000 candidate profiles
- JSONL format
- Multiple structured candidate attributes

## Pipeline

1. Broad Candidate Retrieval
2. Evidence Extraction
3. Must-Have Qualification Check
4. Technical Fit Scoring
5. Risk Detection
6. Behavioral Hireability Scoring
7. Hidden Gem Discovery
8. Re-Ranking
9. Quality Calibration
10. Explainable Candidate Reasoning

## Results

- Candidates Processed: 100,000
- Final Ranked Candidates: 100
- Runtime: ~5 minutes
- Throughput: ~333 candidates/sec

## Technologies

- Python
- Pandas
- JSONL Processing
- Heap-Based Top-K Selection
- Google Colab

## Future Enhancements

- Embedding-based retrieval
- Learning-to-Rank models
- Graph-based evidence networks
- LLM-powered reasoning
