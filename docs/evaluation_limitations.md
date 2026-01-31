# Evaluation and Limitations

## Evaluation Objectives
The evaluation strategy for Predicta focuses on assessing the practical
usefulness, stability, and interpretability of analytics outputs in real
operational contexts.

Rather than optimising for benchmark performance, evaluation prioritises
robustness under realistic SME data constraints.

---

## Evaluation Approach

Given the nature of SME data, evaluation is primarily conducted using
offline and operational criteria, including:

- Consistency of outputs across repeated inputs
- Sensitivity to missing or incomplete data
- Stability of trends and summaries over time
- Clarity and interpretability of generated insights

Where historical data is available, simple train/validation splits are
used to assess predictive components.

---

## Practical Constraints

Several real-world constraints shape the evaluation process:

- Limited data volume for many users
- High variability in data quality and structure
- Dependence on manual data entry via conversational interfaces
- Need for low-latency responses in live environments

These constraints necessitate conservative modelling choices and
careful validation of outputs.

---

## Limitations

The current system has several acknowledged limitations:

- Absence of large, labelled datasets for supervised learning
- Limited support for long-horizon forecasting
- Reliance on rules-based analytics for early-stage users
- Potential biases introduced by inconsistent user input

These limitations are explicitly considered in system design and
documentation.

---

## Ethical and Responsible AI Considerations

Predicta is designed as a decision-support system rather than an
autonomous decision-maker. Outputs are presented as guidance, with
explanatory context, to support human judgement.

Data handling practices prioritise user privacy, minimal data retention,
and transparency in system behaviour.

---

## Future Evaluation Directions

As data volume and system maturity increase, future evaluation will
explore:

- Comparative assessment of rule-based vs model-based approaches
- Longitudinal performance tracking
- User trust and adoption metrics
- Error analysis and failure mode characterisation

---

## Summary
The evaluation and limitations framework reflects a pragmatic applied-AI
approach, balancing immediate operational value with responsible system
development and research transparency.
