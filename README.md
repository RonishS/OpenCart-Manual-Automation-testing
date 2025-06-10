# 🚛 OpenCart Manual Testing Project (v4.0)

[![Test Coverage](https://img.shields.io/badge/Tests-50%2B-blue)]()
[![Bugs Logged](https://img.shields.io/badge/Bugs-19-orange)]()
[![Status](https://img.shields.io/badge/Status-Complete-success)]()

---

## 🧠 Overview  
**Comprehensive manual QA** for OpenCart v4.0, focused on:  
- **Guest checkout flow** verification  
- **Cart edge cases** (e.g. adding 999 items)  
- **Search & UI workflows**
- Agile approach
> _Payment processing excluded due to environment constraints._

---

## 📂 Project Artifacts

| **Artifact**               | **Description**                                               | **File**           |
|----------------------------|---------------------------------------------------------------|--------------------|
| **Test Plan**              | Scope: guest checkout, cart edge cases, search validation     | `TestPlan.pdf`      |
| **Test Cases**             | 50+ detailed cases: login, cart, products, wishlist workflows | `TestCases.pdf`   |
| **Bug Reports + Screenshots** | 19 prioritized defects logged in Azure DevOps             | `issues.pdf'    |

---

## 🚀 Key Activities

### 1. Planning & Setup  
- Used a **risk‑based approach** (Critical / High / Medium)  
- Structured in 3 sprints:  
  - **Sprint 1**: Test data prep (500-product JSON), environment config  
  - **Sprint 2**: Manual test execution  
  - **Sprint 3**: Defect logging & validation  

### 2. Test Execution  
- Battery-tested boundary inputs:  
  - **Max cart size** (999 items)  
  - **Special chars** in registration forms  
- Ensured core flows: guest checkout → order confirmation  

### 3. Defect Tracking  
- Logged **19 bugs** with full reproduction steps, environment, and severity  
- **Example Critical Bug**:  
  > **Cart:** No validation on unselected product variants  

---
Reporting link : https://dev.azure.com/OpenCart-Testingronishshrestha20610613/OpenCart%20Testing/_backlogs/backlog/OpenCart%20Testing%20Team/Issues

