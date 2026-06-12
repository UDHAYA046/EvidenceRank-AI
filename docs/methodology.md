
# Methodology

## EvidenceRank AI v5 Pipeline

EvidenceRank AI uses a multi-stage candidate evaluation pipeline designed to move beyond traditional keyword matching.

The system evaluates candidates through ten sequential stages.

---

## Stage 1: Broad Candidate Retrieval

Retrieve all potentially relevant candidates using title, experience, skills, and profile information.

Output:
10K–30K candidate pool.

---

## Stage 2: Evidence Extraction

Extract candidate evidence from:

- Career History
- Projects
- Skills
- Certifications
- Education

Output:
Structured evidence graph for every candidate.

---

## Stage 3: Must-Have Qualification Check

Validate critical requirements.

Examples:

- Required skills
- Experience range
- Technical background

Output:
Qualified candidate set.

---

## Stage 4: Technical Fit Scoring

Calculate candidate fit based on:

- Technical evidence
- Retrieval relevance
- Product experience
- Evaluation experience
- Skills breadth

Output:
Technical Fit Score (0–100)

---

## Stage 5: Risk Detection

Identify:

- Keyword stuffing
- Suspicious timelines
- Low engagement
- Inactive profiles

Output:
Risk Score (0–100)

Higher score indicates greater risk.

---

## Stage 6: Behavioral Hireability Analysis

Evaluate:

- Recruiter response rate
- Profile activity
- Interview completion rate
- Offer acceptance rate
- Notice period

Output:
Hireability Score (0–100)

---

## Stage 7: Hidden Gem Discovery

Boost candidates with:

- Strong skills
- Strong behavioral indicators
- Lower visibility
- Undiscovered potential

Output:
Hidden Gem Bonus

---

## Stage 8: Pairwise Re-Ranking

Compare candidates directly to improve ranking quality.

Output:
Top 500 Candidates

---

## Stage 9: Quality Calibration

Remove ranking anomalies and improve candidate diversity.

Output:
Top 100 Candidates

---

## Stage 10: Explainable Reasoning

Generate recruiter-friendly explanations describing why a candidate was selected.

Output:
Final Ranked Candidate List
