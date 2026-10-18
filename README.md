# Alfredo (Ed) Garcia — IT Governance Portfolio & Decision Lab 🌐

[![Live Website](https://img.shields.io/badge/Live_Website-edgarcia--id.github.io-blue?style=for-the-badge)](https://edgarcia-id.github.io)
[![Maintained By](https://img.shields.io/badge/Maintained_By-NusaIT-indigo?style=for-the-badge)](https://nusait.com)
[![Decision Lab v2](https://img.shields.io/badge/Decision_Lab-v2-0ea5e9?style=for-the-badge)](https://edgarcia-id.github.io/#decision-lab-v2)
[![GitHub](https://img.shields.io/badge/GitHub-edgarcia--id-181717?style=for-the-badge&logo=github)](https://github.com/edgarcia-id)

Welcome to the source repository for my professional portfolio and open-source IT Governance Toolkit.

I am **Alfredo (Ed) Garcia**, an IT Governance consultant and Principal at [Nusa Industri Teknologi (NusaIT)](https://nusait.com), based in Indonesia. My work focuses on bridging IT governance, enterprise architecture, business process improvement, and practical software engineering.

This repository contains the front-end landing page for a growing collection of tools designed to help IT leaders, CIOs, business owners, students, lecturers, and researchers make more structured, transparent, and evidence-based decisions.

**Explore the portfolio:** [https://edgarcia-id.github.io](https://edgarcia-id.github.io)

---

## 📌 Table of Contents

- [Professional Focus](#-professional-focus)
- [Architecture and Privacy by Design](#-architecture-and-privacy-by-design)
- [IT Governance Toolkit](#-it-governance-toolkit)
- [Decision Lab v2 — Free Decision Calculators](#-decision-lab-v2--free-decision-calculators)
  - [AHP Decision Engine v2](#1-ahp-decision-engine-v2)
  - [TOPSIS Decision Engine v2](#2-topsis-decision-engine-v2)
  - [SAW Calculator Engine v2](#3-saw-calculator-engine-v2)
  - [Decision Tree Calculator v2](#4-decision-tree-calculator-v2)
  - [Bayesian Calculator Engine v2](#5-bayesian-calculator-engine-v2)
- [Design Principles](#-design-principles)
- [Technology Stack](#-technology-stack)
- [Roadmap](#-roadmap)
- [Connect](#-connect)

---

## 🎯 Professional Focus

My professional work connects four areas:

- **IT Governance and Compliance:** Translating governance requirements, risk management principles, and standards such as ISO 27001 into practical IT processes, policies, and operational controls.
- **Enterprise Architecture and Business Systems:** Designing maintainable applications, ERP solutions, HRIS workflows, and integrations that support real business operations.
- **Decision Support and Quantitative Analysis:** Building transparent calculators that help users evaluate alternatives, assess uncertainty, and understand the mathematical basis of a decision.
- **AI and Process Automation:** Exploring structured AI workflows, data analysis, and automation for business and technical operations.

The goal is not simply to produce software. It is to make technology more understandable, maintainable, secure, and useful for decision-makers.

## 🔐 Architecture and Privacy by Design

Privacy is an important design principle across this portfolio.

The calculators and utilities linked from the website are designed to perform their calculations and document generation in the user's browser wherever supported by the individual application.

The intended architecture emphasizes:

- **Client-side processing:** Calculations run locally in the browser where the application supports this design.
- **No mandatory account for browser-based tools:** The Decision Lab v2 calculators are intended to be usable without creating an account.
- **Transparent calculations:** Decision-method tools expose intermediate calculations and results so users can review the reasoning behind an outcome.
- **Portable reports:** Supported tools provide exports such as PDF, Word, Excel, or CSV.
- **Maintainable implementation:** The portfolio demonstrates practical software engineering with an emphasis on understandable, purpose-built solutions.

External libraries, fonts, or other dependencies may still be loaded by individual applications. Please review each application's implementation and dependencies when assessing privacy, security, or offline requirements.

---

## 🛠️ IT Governance Toolkit

The portfolio includes practical utilities for IT management, enterprise operations, and governance documentation.

### 1. Strategic and Financial Planning

Tools for evaluating technology investments, planning budgets, and comparing business alternatives.

- [ERP Business Case & ROI Calculator](https://edgarcia-id.github.io/erp-roi-calculator/) — Estimate ERP implementation ROI, payback period, and financial justification.
- [IT Asset Depreciation Calculator](https://edgarcia-id.github.io/it-asset-depreciation/) — Calculate monthly and annual depreciation for IT assets.
- [Vendor Evaluation Scorecard](https://edgarcia-id.github.io/vendor-evaluation-scorecard/) — Compare vendors using weighted business and technical criteria.
- [IT Work Plan & Realization Tracker](https://edgarcia-id.github.io/it-workplan-realization/) — Track work plans, actual realization, and KPI performance.

### 2. IT Operations and Risk Management

Tools for documenting incidents, managing changes, and evaluating operational risk.

- [SLA & Downtime Calculator](https://edgarcia-id.github.io/sla-downtime-calculator/) — Calculate permitted downtime for a specified service availability target.
- [IT Risk Assessment Matrix](https://edgarcia-id.github.io/simple-it-risk-assessment/) — Assess and prioritize IT risks using structured risk-assessment concepts.
- [IT Incident Post-Mortem & RCA Generator](https://edgarcia-id.github.io/it-incident-postmortem/) — Document incidents and conduct Root Cause Analysis using methods such as the Five Whys.
- [IT Change Request Generator](https://edgarcia-id.github.io/it-change-request-generator/) — Prepare structured change requests with risk assessment and rollback planning.
- [IT Daily Activity Logger](https://edgarcia-id.github.io/it-activity-logger/) — Record operational activities and generate supporting reports.

### 3. Compliance and Automation

Tools and resources for improving governance documentation and operational workflows.

- [Open-Source IT Policy Templates](https://edgarcia-id.github.io/it-policy-templates/) — Reusable IT policy and SOP templates for governance and compliance preparation.
- [UU PDP Readiness Checker](https://edgarcia-id.github.io/uupdp-readiness-checker/) — Assess organizational readiness against Indonesia's Personal Data Protection Law, UU No. 27 Tahun 2022.
- [AI Helpdesk Triage Simulator](https://edgarcia-id.github.io/ai-helpdesk-triage/) — Demonstrate structured prompt design and JSON-based ticket classification.
- [AI B2B Pitch Architect](https://edgarcia-id.github.io/ai-b2b-pitch-architect/) — Generate structured B2B sales messaging using defined frameworks and output schemas.

---

## 🎓 Decision Lab v2 — Free Decision Calculators

**Decision Lab v2** is a collection of browser-based decision-method calculators for students, lecturers, researchers, and professionals who need transparent quantitative decision support.

The suite covers five complementary approaches to decision analysis:

| Method | Primary purpose |
| --- | --- |
| AHP — Analytic Hierarchy Process | Derive criteria weights through pairwise comparisons and evaluate judgment consistency. |
| TOPSIS — Technique for Order Preference by Similarity to Ideal Solution | Rank alternatives by their relative distance from ideal and negative-ideal solutions. |
| SAW — Simple Additive Weighting | Score and rank alternatives using normalized criteria and weighted sums. |
| Decision Tree Analysis | Evaluate sequential decisions, uncertain outcomes, and expected monetary value. |
| Bayesian Analysis | Update beliefs using evidence and analyze probabilistic relationships between variables. |

The tools are intended to make the calculation process inspectable rather than presenting only a final ranking or score.

**Access the complete suite:** [Decision Lab v2 on GitHub Pages](https://edgarcia-id.github.io/#decision-lab-v2)

### 1. AHP Decision Engine v2

**Analytic Hierarchy Process calculator for multi-criteria decision analysis**

[Open AHP Decision Engine v2](https://edgarcia-id.github.io/ahp-decision-engine-v2/)

AHP Decision Engine v2 supports structured decision hierarchies and pairwise comparisons based on Saaty's 1–9 fundamental scale.

Key capabilities include:

- Multi-level decision hierarchies.
- Pairwise comparison matrices and eigenvector-based priority weights.
- Consistency Index and Consistency Ratio calculations, with suggestions for reviewing inconsistent judgments.
- Incomplete judgments using the Harker approach.
- Group decision-making using Aggregation of Individual Judgments (AIJ).
- Sensitivity analysis designed to support detailed examination of changes in priorities.
- PDF reports and Excel workbooks with live formulas.

**Useful for:** Vendor selection, technology evaluation, prioritization, academic research, and thesis projects using AHP.

### 2. TOPSIS Decision Engine v2

**Multi-criteria ranking calculator using ideal-solution distances**

[Open TOPSIS Decision Engine v2](https://edgarcia-id.github.io/topsis-decision-engine-v2/)

TOPSIS Decision Engine v2 helps users rank alternatives according to their relative closeness to an ideal solution and distance from a negative-ideal solution.

Key capabilities include:

- Manual, Entropy, CRITIC, or AHP-derived criterion weights.
- Import of weights from an AHP project.
- Four normalization methods.
- Step-by-step calculation tables.
- Closeness coefficient (C*) and positive/negative ideal distance analysis (D⁺ and D⁻).
- Charts, heatmaps, and radar visualizations.
- Weight sensitivity analysis with stability intervals and rank-reversal checks.
- PDF, Word, Excel with live formulas, and CSV exports, plus shareable links.

**Useful for:** Comparing suppliers, ranking research alternatives, technology selection, and evaluating multi-criteria problems.

### 3. SAW Calculator Engine v2

**Simple Additive Weighting calculator with extended evaluation options**

[Open SAW Calculator Engine v2](https://edgarcia-id.github.io/saw-calculator-engine-v2/)

SAW Calculator Engine v2 implements a weighted-sum approach to multi-criteria decision-making, with support for different criteria structures and weighting methods.

Key capabilities include:

- Benefit and cost criteria.
- Sub-criteria using crisp ranges or categorical labels.
- Multi-rater group assessments.
- Manual, Entropy, CRITIC, or AHP-derived weights.
- Three normalization methods.
- Weight sensitivity analysis.
- Side-by-side comparison with Weighted Product (WP) and TOPSIS.
- PDF, Word, Excel with live formulas, and CSV exports, plus shareable links.

**Useful for:** Weighted scoring models, research evaluations, alternative ranking, and comparing straightforward decision-scoring methods.

### 4. Decision Tree Calculator v2

**Decision analysis under uncertainty, with rollback and sensitivity analysis**

[Open Decision Tree Calculator v2](https://edgarcia-id.github.io/decision-tree-calculator-v2/)

Decision Tree Calculator v2 supports visual decision trees and payoff-table-based analysis for sequential decisions involving uncertain outcomes.

Key capabilities include:

- Decision trees and payoff tables with variables and formulas.
- Expected Monetary Value (EMV) rollback and optimal-policy identification.
- Decision criteria under uncertainty: Maximax, Maximin, Hurwicz, Laplace, and Minimax Regret.
- Risk profiles, utility analysis, and certainty equivalents.
- Tornado, spider, and two-way sensitivity analysis.
- Expected Value of Perfect Information (EVPI).
- Bayesian probability revision and Expected Value of Sample Information (EVSI).
- PDF, Word, and Excel exports with live rollback formulas.

**Useful for:** Business case analysis, investment alternatives, operational planning, risk evaluation, and decision-analysis coursework.

### 5. Bayesian Calculator Engine v2

**Bayesian network calculator for probabilistic reasoning and evidence-based analysis**

[Open Bayesian Calculator Engine v2](https://edgarcia-id.github.io/bayesian-calculator-engine-v2/)

Bayesian Calculator Engine v2 supports multi-state Bayesian networks and exact probabilistic inference, allowing users to explore how evidence changes the probability of possible outcomes.

Key capabilities include:

- Multi-state Bayesian network construction.
- Exact inference with hard and soft evidence.
- Most Probable Explanation (MPE).
- Evidence-conflict analysis.
- Value of Information and parameter sensitivity analysis.
- D-separation analysis.
- Decision analysis.
- Conditional Probability Table (CPT) learning from data using the Expectation-Maximization (EM) algorithm.
- GeNIe `.xdsl` and BIF import/export.
- PDF, Word, and Excel exports with live formulas.

**Useful for:** Probabilistic modeling, research, risk analysis, diagnostic reasoning, and studying Bayesian networks.

### Why Decision Lab v2?

Decision methods are often taught through formulas, spreadsheets, or specialized software. Decision Lab v2 aims to make these methods easier to explore by bringing the calculations, intermediate results, visualizations, and reporting tools together in a browser-based interface.

The suite is designed to support learning and analysis. Users should still validate their data, assumptions, model selection, and interpretations before using the results in formal research or consequential decisions.

---

## 🧭 Design Principles

The portfolio and its tools follow several practical principles:

1. **Transparency over black-box results:** Show intermediate calculations where supported.
2. **Practical accessibility:** Make useful tools available through a web browser without unnecessary setup.
3. **Reproducibility:** Provide report and data exports where supported, allowing users to document and review their analysis.
4. **Privacy-conscious design:** Prefer local processing for calculations when the application's architecture permits it.
5. **Methodological clarity:** Identify the decision method and its assumptions so users can interpret results appropriately.
6. **Maintainability:** Favor understandable implementations and focused functionality over unnecessary complexity.

---

## 💻 Technology Stack

The portfolio and the wider collection of projects use web technologies and data-analysis tools, including:

- HTML5 and semantic document structure.
- CSS3, responsive layouts, and Bootstrap.
- JavaScript for browser-side calculations and interactions.
- Charting and data-visualization libraries where appropriate.
- PDF, Word, Excel, and CSV reporting workflows, depending on the application.
- PHP, MySQL/MariaDB, and Python across other business applications and analytical projects.

The exact dependencies and architecture vary between repositories. Refer to each individual project's source code and documentation for implementation details.

---

## 🗺️ Roadmap

Areas for continued development include:

- Expanding educational resources for AHP, TOPSIS, SAW, decision trees, and Bayesian analysis.
- Improving methodological explanations and worked examples.
- Extending reporting and data-import/export workflows.
- Developing additional open-source tools for IT governance, business analysis, and quantitative decision support.
- Improving documentation, accessibility, and usability across the portfolio.

The roadmap may evolve as the tools are tested and refined.

---

## 🤝 Connect

For discussions about IT Governance, enterprise architecture, business systems, quantitative decision support, or custom software development, feel free to connect.

- **LinkedIn:** [Alfredo (Ed) Garcia](https://www.linkedin.com/in/alfredo-garcia-elbarta-tarigan/)
- **Consulting firm:** [Nusa Industri Teknologi (NusaIT)](https://nusait.com)
- **Website:** [edgarcia-id.github.io](https://edgarcia-id.github.io)
- **Contact:** [NusaIT Contact](https://nusait.com/contact)
- **GitHub:** [github.com/edgarcia-id](https://github.com/edgarcia-id)

---

*© 2026 Alfredo (Ed) Garcia. Built to make governance practical and decision-making more transparent.*
