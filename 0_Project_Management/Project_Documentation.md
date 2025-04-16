# EU AI Act Disclosure Mapping – Project Documentation

This document provides a chronological and structured overview of all steps taken so far in building the technical disclosure mapping for the EU AI Act.

---

## ✅ Project Objective

Translate regulatory requirements of the EU AI Act into **technical**, **framework-agnostic**, and **objective** disclosure elements that are:
- Understandable to developers and auditors
- Applicable across compliance frameworks (ISO, NIST, etc.)
- Structured for automation, reuse, and toolchain integration

---

## 📁 Repository Structure Overview

| Folder | Description |
|--------|-------------|
| `0_Project_Management/` | Project plan, timeline, and stakeholder overview |
| `1_Regulatory_Input/`   | Source articles and legal extractions (e.g., Art. 10, Annex IV) |
| `2_Requirement_Extraction/` | Mappings from legal text to technical terminology |
| `3_Disclosure_Model/`   | Formalized disclosure elements (in .md, .json) |
| `4_Templates_and_Tools/` | Checklists, templates, and conformity tools |
| `5_Communication/`      | Executive summaries, slides, outreach docs |
| `6_References_and_Links/` | External resources, academic sources, book citations |

---

## 🧱 Key Steps Completed

### 1. **Clarified Objective**
- Restated the intent of the mapping project.
- Identified guiding principles: objectivity, technical orientation, cross-framework utility.

### 2. **Defined Legal Categories**
- Mapped core regulatory focus areas:
  - Technical Documentation
  - Risk Management
  - Transparency
  - Data Governance
  - Human Oversight
  - Testing & Validation
  - Classification & Conformity

### 3. **Created Legal-to-Technical Mapping Format**
- Introduced the mapping logic: from Article → Legal Clause → Technical Interpretation → Disclosure File

### 4. **Defined Metadata Schema**
- Created a machine-readable metadata schema for each disclosure element
- Fields: ID, name, legal source, technical translation, file format, applicability, etc.

### 5. **Created First Disclosure Elements**
- 3 fully defined disclosure elements:
  - DE-001: System Purpose Declaration
  - DE-002: Risk Control Process Overview
  - DE-003: Human Oversight Log
- Formats exported in `.json` and `.md`

### 6. **Created Reference File**
- Added academic books and external online resources
- Structured source list in `Reference_Links.md`

---

## 📍 Where to Place This File

Save this file as:

```
0_Project_Management/Project_Documentation.md
```

This location ensures it is the first thing reviewed by contributors or auditors of the project.

