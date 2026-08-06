# Horizon Truth Misinformation Detection Dataset Report

## 1. Dataset Information

**Project:** Horizon Truth

**Dataset Name:** Horizon Truth Misinformation Detection Dataset

**Version:** Version 1

**Status:** Development Phase

**Purpose:**

This dataset supports the development of an AI-based misinformation detection system. It is designed to identify and classify harmful misinformation content related to scams and health topics.

---

# 2. Dataset Motivation

Misinformation can create financial, health, and social risks. Version 1 focuses on two priority categories:

1. Scams
2. Health misinformation

These categories were selected because they have direct impacts on user safety.

---

# 3. Dataset Scope

## Category 1: Scams (Finya / ማጭበርበር)

### Subcategories

| Type | Description |
|---|---|
| Financial & Crypto | Fake investments and unrealistic profit claims |
| Job & Scholarship | Fake opportunities requiring payments |
| Impersonation | Fake accounts representing organizations |
| Prize & Lottery | False winning messages |
| SMS Phishing | Fake alerts requesting user action |


## Category 2: Health (Fayyaa / ጤና)

### Subcategories

| Type | Description |
|---|---|
| Miracle Cures | False claims about disease cures |
| Vaccine & Medicine Myths | False medical information |
| Emergency Rumors | Fake public health alerts |
| Nutrition Scams | Dangerous health advice |
| Child Health Myths | Harmful child health claims |

---

# 4. Labeling System

The dataset uses a four-class veracity classification system.

| Label | Meaning |
|---|---|
| 0 TRUE | Verified by two or more credible sources |
| 1 FALSE | Proven false or contradicted by evidence |
| 2 MISLEADING | Contains partial truth but creates a false impression |
| 3 UNVERIFIABLE | Evidence is insufficient |

---

# 5. Data Format

Current formats:

- CSV
- JSON



