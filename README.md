# FUTURE_CS_03

# API Security Risk Analysis – ReqRes.in

**Internship:** Future Interns Cyber Security Internship 2026 — Task 3  
**Prepared by:** Shivakumar S  

## Overview

This repository contains the results of an API Security Risk Analysis performed on the ReqRes.in mock API as part of Cybersecurity Task 03 (Future Interns).

The objective of this assessment was to identify insecure patterns aligned with the OWASP API Security Top 10 and document findings in a structured security report.

---

## Contents

*  Report – API Security Risk Analysis (PDF)
*  Screenshots – Postman request/response evidence
*  Postman Collection 

---

## Target

* Base URL: https://reqres.in/api
* Type: Public mock REST API (used for testing and learning)

---

## Scope

The assessment was limited to publicly accessible endpoints of the ReqRes API.

Tested areas include:

* Authentication endpoints (`/api/login`, `/api/register`)
* User endpoints (`/api/users`, `/api/users/{id}`)
* Edge cases (input validation, pagination, payload injection)

No denial-of-service or destructive testing was performed.

---

## Tools Used

* **Postman** – API testing and request collection
* **Burp Suite Community Edition** – HTTP interception and header analysis

---

## Methodology

The testing methodology was based on the **OWASP API Security Top 10 (2023)**.

The process included:

1. Endpoint discovery and manual testing
2. Authentication and authorization testing
3. Input validation and edge case testing
4. HTTP method and header analysis
5. Mapping findings to OWASP categories

All testing was conducted manually using crafted requests and observed responses.

---

## Key Findings

The following OWASP API Security risks were identified:

* API1: Broken Object Level Authorization (BOLA)
* API2: Broken Authentication
* API3: Broken Object Property Level Authorization (Mass Assignment)
* API5: Broken Function Level Authorization
* API6: Unrestricted Access to Sensitive Business Flows
* API8: Security Misconfiguration
* API9: Improper Inventory Management
* API10: Unsafe Consumption of APIs (Partial)

> Note: ReqRes.in is a mock API. Findings represent insecure patterns and are not exploitable in a real-world context.

---

## Disclaimer

This assessment was conducted for educational purposes only on a publicly available mock API. No real systems were targeted, and no harmful actions were performed.

---

## Tags

#APISecurity #OWASP #CyberSecurity #Postman #BurpSuite
