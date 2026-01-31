# Analytics and Machine Learning Components

## Purpose
Predicta incorporates an analytics layer designed to extract operational
insights from SME data collected through conversational interaction.

The current implementation prioritises robustness, interpretability, and
deployability, while remaining extensible toward more advanced machine
learning methods.

---

## Current Implementation (Rules-Based Analytics)

At present, Predicta primarily employs deterministic and statistical methods
to generate insights from operational data. These include:

- Aggregation of transactional records (e.g., totals, counts, summaries)
- Trend identification over time windows
- Threshold-based signals (e.g., unusually low or high activity)
- Simple descriptive analytics for reporting and feedback

This approach is intentional, as SME data is often sparse, noisy, and
insufficient for immediate deployment of complex models.

---

## Feature Abstraction

Raw conversational inputs are transformed into structured representations
suitable for analysis. Feature abstraction includes:

- Temporal features (e.g., daily, weekly aggregates)
- Categorical groupings derived from user inputs
- Normalised numerical summaries

This abstraction layer decouples data ingestion from analytics logic and
enables future model-based learning.

---

## ML-Ready Design Considerations

Although advanced machine learning models are not yet fully deployed,
the system architecture supports their integration. Planned extensions
include:

- Time-series forecasting for sales and activity patterns
- Anomaly detection for unusual operational behaviour
- Lightweight predictive models suited to small datasets
- Incremental learning as data volume grows

These extensions are designed to balance predictive performance with
interpretability and operational stability.

---

## Evaluation Considerations

Evaluation focuses on practical utility rather than benchmark optimisation.
Key considerations include:

- Stability under small and incomplete datasets
- Transparency of outputs to non-technical users
- Alignment with real operational decision-making needs

---

## Summary
The analytics layer in Predicta reflects a pragmatic applied-AI approach,
where rule-based methods provide immediate value while laying the foundation
for progressive integration of machine learning techniques.
