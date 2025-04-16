# Technical Disclosure Elements

## DE-004 – System Purpose Declaration

**Category:** Technical Documentation
**Source Article:** Annex IV, Section 1
**Legal Text:**
> A general description of the AI system including its intended purpose and the persons developing, deploying or using the system shall be provided.
**Technical Translation:**
Document system purpose, end-users, and stakeholder roles in a structured format.
**Disclosure Format:** `system_overview.md`
**Evidence Type:** Text document
**Mandatory:** Yes
**Risk Level Applicability:** High-risk only
**Reusability:** Generic
**Review Frequency:** Each major version
**Crosswalk Tags:** ISO 42001.4.1, OECD.AI.1.1

---

## DE-005 – Risk Control Process Overview

**Category:** Risk Management
**Source Article:** Article 9
**Legal Text:**
> High-risk AI systems shall be developed and implemented on the basis of a risk management system.
**Technical Translation:**
Define a documented risk workflow, including detection triggers, mitigation strategies, and responsible roles.
**Disclosure Format:** `risk_control_flowchart.svg`
**Evidence Type:** Process map or flowchart
**Mandatory:** Yes
**Risk Level Applicability:** High-risk only
**Reusability:** Generic
**Review Frequency:** Each system update
**Crosswalk Tags:** ISO 31000, NIST RMF

---

## DE-006 – Human Oversight Log

**Category:** Human Oversight
**Source Article:** Article 14
**Legal Text:**
> High-risk AI systems shall be designed and developed in such a way that natural persons can effectively oversee the AI system.
**Technical Translation:**
Maintain audit logs of human interventions or override actions triggered during AI operation.
**Disclosure Format:** `oversight_log.csv`
**Evidence Type:** CSV log file
**Mandatory:** Yes
**Risk Level Applicability:** High-risk only
**Reusability:** Domain-specific
**Review Frequency:** Continuous logging
**Crosswalk Tags:** ISO 42001.7.4.2, OECD.AI.2.2

---
