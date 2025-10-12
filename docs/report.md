# 🧾 AI Ethics Casefiles — Report

_Augusto Mate, 2025_

---

## 📘 Introduction

This case study explores two real-world AI systems through a lens of ethical analysis,
with a focus on bias, transparency, and fairness. The aim is to identify
problematic patterns and suggest responsible alternatives grounded in academic and real-world best practices.

---

## 📂 Case 1: COMPAS — Algorithmic Risk Assessment 

> “Predicting recidivism isn’t neutral when historical data is biased.”

- **System**: COMPAS (Correctional Offender Management Profiling)
- **Context**: Used in U.S. courts to assess likelihood of reoffending
- **Ethical Issues**:
  - Racial bias in training data
  - Lack of transparency
  - Opaque decision logic

### Ethical Evaluation

Using principles from AI4People and the EU Ethics Guidelines, the COMPAS system fails in:

- **Fairness**: Reinforces systemic bias
- **Transparency**: Proprietary algorithm resists scrutiny
- **Accountability**: Judges rely on automated scores with minimal oversight

### Suggested Redesign

- Replace opaque scoring with interpretable models (e.g., logistic regression with weights shown)
- Require local explainability (e.g., SHAP values)
- Independent audits and open datasets

---

## 📁 Case 2: Hiring Algorithm by Amazon (Discontinued)

> “An algorithm trained on past hires mirrors past biases.”

- **System**: Internal hiring tool used between 2014–2017
- **Problem**: Penalized resumes with “women’s” indicators (e.g., women’s college)
- **Outcome**: Discontinued after bias detection

### Ethical Evaluation

Fails in:

- **Justice and fairness**
- **Human oversight**
- **Inclusive design**

---

## 🧭 Conclusion

AI systems, even unintentionally, can amplify existing biases and exclusions.
Ethical evaluations should not be afterthoughts, but foundational to system design.

### Key Takeaways

- Data is not neutral — neither are models
- Interpretability is key to transparency
- Accountability frameworks must exist beyond code

---

## 📚 References

- AI4People (Floridi et al.)
- EU Ethics Guidelines for Trustworthy AI
- ProPublica (2016). Machine Bias.
