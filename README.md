# Horizon Truth - Misinformation Detection Dataset

## Overview

This repository contains the dataset development resources for the **Horizon Truth Misinformation Detection System**.

Horizon Truth is an AI-supported platform designed to help identify and understand harmful misinformation by combining automated analysis, verification approaches, and community-driven reporting. The project focuses on improving information reliability and digital safety, especially in local contexts. 

## Dataset Status

**Current Version:** Version 1 (Development Phase)

**Status:** Under development

This dataset is currently private and is not ready for public release. The repository is used for:
- Dataset collection
- Data cleaning
- Annotation management
- Version tracking
- Model development preparation

Future versions will expand coverage, categories, and labeling capabilities.

---

# Version 1 Scope

Version 1 focuses on two high-impact misinformation categories:

| Category | Local Name | Purpose |
|---|---|---|
| Scams | ማጭበርበር (Finya) | Protect users from financial fraud and deception |
| Health | ጤና (Fayyaa) | Reduce harmful health misinformation |

---

# Veracity Labels

The dataset uses a 4-class verification system:

| Label | Class | Definition |
|---|---|---|
| 0 | TRUE | Verified by two or more credible sources |
| 1 | FALSE | Fabricated or contradicted by reliable evidence |
| 2 | MISLEADING | Partially true but missing context or presented deceptively |
| 3 | UNVERIFIABLE | Not enough evidence to confirm or deny |

---




