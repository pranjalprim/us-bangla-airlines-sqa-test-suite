# ✈️ US-Bangla Airlines Reservation System — SQA Manual Test Suite

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Testing Type](https://img.shields.io/badge/Testing-Manual_SQA-blue.svg)]()
[![Status](https://img.shields.io/badge/Status-Completed-success.svg)]()

A comprehensive, end-to-end **Software Quality Assurance (SQA) Manual Test Suite** designed for the **US-Bangla Airlines Portal & Reservation System**. This project covers complete software testing deliverables including strategic planning, test scenario mapping, test case design, execution tracking, defect reporting, and execution metrics analysis.

---

## 📌 Project Summary

* **Target Application:** US-Bangla Airlines Web Portal & Reservation System
* **Modules Tested:** 
  * User Registration & Profile Creation (`Create a new profile`)
  * User Authentication (`LOGIN`)
  * Flight Booking Engine (`Book a flight`)
  * Real-time Tracking (`Flight Status`)
  * User Profile Management (`Update your profile`)
  * Help & Support Desk (`HELP`)
* **Test Design & Execution Tool:** Microsoft Excel / Google Sheets
* **Testing Methodology:** Black Box Testing, Functional, UI/UX, Navigation, Boundary Value Analysis (BVA), Equivalence Partitioning (EP), and Regression Testing.

---

## 📊 Key Execution Metrics

| Metric Category | Count / Details |
| :--- | :--- |
| **Total Test Cases Executed** | **87** |
| **Passed Test Cases** | **53** |
| **Failed Test Cases** | **29** |
| **Out of Scope** | **5** |
| **Pass Rate** | **60.9%** |
| **Total Bugs Logged** | Defect tracking included in Bug Report sheet |

---

## 📁 Workbook Architecture (`.xlsx`)

The test suite is organized into structured sheets within `US-Bangla_Airlines_ReservationSystem_Manual_Test_Suite_v1.0.xlsx`:

1. 📋 **`Test Plan_v1.0`**: Defines project scope, testing objectives, test environment, entry/exit criteria, risks, and execution timelines.
2. 🧠 **`Mind Maps_v1.0`**: Visual decomposition of application workflow and module coverage.
3. 🗺️ **`TestScenarios_v1.0`**: High-level test scenarios mapping business requirements to functional specs.
4. 📝 **`All_Test_Cases_v1.0`**: Detailed test cases including Test Case ID, Description, Pre-conditions, Steps, Test Data, Expected vs. Actual Result, Severity, Priority, and Status.
5. 🐞 **`Bug Report_v1.0`**: Comprehensive defect log detailing summary, steps to reproduce, expected vs. actual behavior, severity, priority, and bug lifecycle state.
6. 📈 **`Test Summary Report_v1.0`**: Executive dashboard summarizing overall pass/fail status and feature readiness.
7. 📊 **`Test Metrics_v1.0`**: Execution health analysis, coverage metrics, and defect density evaluation.

---

## 🛠️ Testing Coverage & Key Scenarios

* **Authentication & Authorization:** Positive and negative test cases for user registration, input validation, session management, and password recovery.
* **Flight Search & Booking Engine:** One-way and round-trip flight searches, date pickers, passenger selection, fare calculations, and booking confirmation flows.
* **Flight Status Tracking:** Verifying real-time flight schedule updates, route validation, and search accuracy.
* **Profile Management:** Account updates, contact details modification, and data validation rules.

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).
