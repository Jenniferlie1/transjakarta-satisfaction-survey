# Jakarta Barat Student Satisfaction with Transjakarta
A survey and machine learning study measuring university students' satisfaction with Transjakarta, Jakarta's public bus rapid transit system.

## Course: Survey and Sampling Methods

## Background
Transjakarta is one of the primary modes of public transportation for university students in West Jakarta. This study measures how satisfied students are with the service and identifies the key factors driving that satisfaction.

## Methodology
- Population: ~41,200 students across Universitas Bina Nusantara (BINUS), Universitas Kristen Krida Wacana (UKRIDA), and Universitas Trisakti
- Sampling: Simple Random Sampling with Finite Population Correction, target of 568 samples
- Data collection: Online questionnaire (Google Forms) + face-to-face interviews with 4 respondents
- Valid responses: 359 out of 377 submissions
- Weighting: Sample weighting applied based on each university's population proportion

The questionnaire measured 4 main constructs: **Reliability, Comfort, Safety and Security, and Customer Satisfaction**.

## Modeling
Satisfaction levels were classified into 3 categories (Dissatisfied, Neutral, Satisfied/Very Satisfied) using a **Random Forest Classifier**.

Metric	Value
- Accuracy	83.33%
- Macro F1-Score	0.71

**Top predictive factors (feature importance)**: likelihood to recommend Transjakarta to peers, seat comfort, staff service quality, cabin temperature comfort, bus cleanliness, driver behavior, and perceived safety.

## Key Findings
- The majority of students (71.7%) reported being Satisfied or Very Satisfied overall
- Best-rated aspects: route coverage, women-only sections, and fare-to-service value
- Most common complaints (from open-ended feedback): fleet size & bus frequency (29.8% of comments), route coverage (20.2%), and safety (16.0%)

## Recommendations
1. Increase fleet size, especially during peak hours
2. Improve schedule punctuality and consistency
3. Develop real-time journey information systems
4. Strengthen enforcement of dedicated busway lanes
5. Conduct regular driver evaluation and training

## Tech Stack
Python pandas scikit-learn (Random Forest) Google Forms

**Note**: The full report (including detailed statistical methodology and interview data) is kept separate as it contains respondent contact information.

Team

Hanna Felicia Gunawan · Jennifer Liyanto · Jocellyn Jonathan · Virgie Queena Shallomitha
