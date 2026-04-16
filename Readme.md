# API Security Risk Analysis Report

## Cyber Security Internship | Future Interns 2026

---

## Overview

This project presents a read-only API security analysis of a public demo API, conducted as part of the Future Interns Cyber Security Internship 2026.

The assessment was strictly non-intrusive, focusing on identifying common API security risks without any exploitation or harmful actions.

---

## Scope

- **Target:** JSONPlaceholder API (https://jsonplaceholder.typicode.com)
- **Environment:** Public demo REST API
- **Methodology:** Passive / Read-only browser-based testing

---

## Tools

- **Browser (Chrome)** —> Accessed and tested all API endpoints directly
- **Browser DevTools** —> Inspected API responses and headers
- **JSONPlaceholder** —> Public demo API designed for security testing

---

## Key Findings

- No authentication required to access user data —> **High Risk**
- Sensitive personal data exposed in API responses —> **High Risk**
- Any user's data accessible by guessing ID number —> **High Risk**
- No rate limiting on API requests —> **Medium Risk**
- Bulk data returned instead of filtered results —> **Medium Risk**

---

## Risk Summary

- **Overall Risk:** High
- **High Risk Issues:** 3
- **Medium Risk Issues:** 2
- **Total Findings:** 5

---

## Repository Structure

- `README.md` — Project summary
- `API_Security_Risk_Report.pdf` — Detailed report
- `screenshots/` — Supporting evidence from endpoint testing

---

## Ethics & Compliance

- Tested public-facing demo API only
- Read-only browser-based testing
- No exploitation or attacks performed
- API is specifically designed for security testing and education

---

## Internship Context

- **Program:** Future Interns Cyber Security Internship
- **Track:** Cyber Security (CS)
- **Task:** API Security Risk Analysis
- **Repository:** FUTURE_CS_03

---

**LinkedIn:** https://tz.linkedin.com/in/faridi-hant-60b06b344
**Organization:** https://www.linkedin.com/company/future-interns/

---

> **Note:** This assessment was conducted in accordance with ethical security testing standards.
