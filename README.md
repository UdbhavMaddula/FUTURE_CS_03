# API Security Risk Analysis Report

## Overview

This repository contains the deliverables for **Future Interns Cyber Security Internship – Task 3**.

The objective of this project was to perform a **read-only API Security Risk Analysis** on the public **JSONPlaceholder API** using **Postman**. The assessment focused on identifying common API security weaknesses, analyzing exposed data, reviewing authentication mechanisms, inspecting request and response headers, and evaluating potential business risks.

## Tools Used

* Postman
* JSONPlaceholder API
* Browser Developer Tools
* GitHub
* Microsoft Word / PDF

## Scope

The assessment was conducted using ethical and non-intrusive testing methods. Only publicly accessible endpoints were analyzed.

Tested Endpoints:

* GET /users
* GET /users/1
* GET /posts
* GET /comments
* POST /users

## Methodology

1. Reviewed API documentation.
2. Tested endpoints using Postman.
3. Inspected request and response headers.
4. Analyzed authentication requirements.
5. Examined exposed data fields.
6. Identified potential security risks.
7. Classified risks by severity.
8. Provided remediation recommendations.

## Key Findings

* Unauthenticated access to API resources.
* Excessive data exposure in responses.
* Predictable resource identifiers.
* No visible rate-limiting controls.
* Lack of authorization validation.
* Information disclosure through API responses.

## Risk Summary

| Risk                        | Severity |
| --------------------------- | -------- |
| Unauthenticated Access      | High     |
| Excessive Data Exposure     | Medium   |
| Predictable Resource IDs    | Medium   |
| Missing Rate Limiting       | Medium   |
| Weak Authorization Controls | Medium   |
| Information Disclosure      | Low      |

## Evidence

Screenshots of API requests and responses are available in the **Screenshots/** directory.

## Business Impact

If similar weaknesses exist in a production environment, they may lead to:

* Unauthorized access to sensitive data
* Account enumeration
* Data leakage
* Increased attack surface
* Regulatory compliance issues
* Reputational damage

## Recommendations

* Implement strong authentication mechanisms.
* Enforce authorization checks on every request.
* Apply rate-limiting controls.
* Follow the principle of least privilege.
* Minimize sensitive information in responses.
* Monitor and log API activity.

## Conclusion

This project provided hands-on experience in API security assessment using industry-standard tools and methodologies. The findings demonstrate common API security risks and highlight the importance of implementing secure authentication, authorization, monitoring, and data protection controls in modern applications.

---

**Internship:** Future Interns Cyber Security Internship
**Task:** API Security Risk Analysis
**Author:** Maanas Sri Udbhav Maddula
