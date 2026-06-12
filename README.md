# HIDS Testing — Home Inspection and Development System

Quality Assurance project for the **HIDS (Home Inspection and Development System)** — a web and mobile application for managing home inspection workflows, defect recording, report generation, and multi-role collaboration between inspectors, customers, contractors, and admins.

## Overview

This repository contains all QA artifacts produced during the testing lifecycle of the HIDS project, including Test Plan, Test Script, Test Case Summary, UAT Plan & Script, and Defect Report.

## Repository Structure

```
HIDS-Testing/
├── TEST-Plan/          # Test Plan and Test Script documentation
├── UAT-Inspectors/     # UAT Plan and UAT Script for inspector role
├── HIDS Test.xlsx      # Full QA documentation (Test Plan, Test Script,
│                       # Test Case Summary, UAT, Defect Report, Summary Reports)
└── README.md
```

## Testing Scope

| Type | Details |
|---|---|
| Manual Testing | Functional testing across 15 core functions (FN-HIDS-01 to FN-HIDS-15) |
| UAT | Validated with end users covering inspector, customer, contractor, and admin roles |
| PDF Report Testing | Verified report generation, preview, pagination, and PDF export functionality |

## Core Functions Tested

- Login & Role-Based Access Control
- Dashboard & Status Tracking
- Customer Review & Rating
- Project Scheduling & Work Queue
- Defect Recording & Photo Management
- Inspection Summary Report
- PDF Report Preview & Export
- Report Sharing & Link Management
- Re-inspection (Re-test) Workflow
- Push Notifications
- Contractor Functions
- Admin & Master Data Management
- Daily Construction Report
- Multi-Language Support (TH / EN)

## Testing Summary

- 15 core functions covered across the full inspection workflow
- Test cases cover functional, UI, boundary, and business logic scenarios
- UAT conducted with real end users across inspector and customer roles
- Full documentation: Test Plan, Test Script, Test Case Summary, UAT Plan & Script, Defect Report

## Tools & Technologies

- **Google Sheets / Excel** — Test documentation
- **GitHub** — Version control and artifact storage
- **Figma** — UI reference for test case design

## Author

**Narenthon Saetio** — QA Tester  
Burapha University, Faculty of Informatics
