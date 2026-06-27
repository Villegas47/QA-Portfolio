# QA Portfolio — Alexander Villegas

Manual QA testing portfolio documenting bug reports and test findings across multiple user scenarios.

---

## Project 1: Saucedemo.com — E-Commerce Web App Testing

**Site Tested:** https://www.saucedemo.com  
**Testing Type:** Manual — Functional, UI/Visual, Content  
**Date Tested:** April 2026  
**Users Tested:** standard_user, locked_out_user, problem_user  

### Summary
Performed manual QA testing across multiple user accounts on a practice e-commerce web application. Identified and documented 10 bugs spanning content errors, functional failures, and a critical checkout blocker.

### Bug Breakdown
| Severity | Count |
|----------|-------|
| Critical | 1 |
| High | 4 |
| Medium | 4 |
| Low | 1 |
| **Total** | **10** |

### Files
- `BUG_REPORT.xlsx` — Full bug report including bug ID, location, steps to reproduce, expected vs actual results, severity, status, and notes

### Tools Used
- Manual testing
- Google Sheets
- GitHub

---

## Project 2: DummyJSON REST API — API Testing

**Base URL:** https://dummyjson.com  
**Testing Type:** Manual API Testing  
**Tool Used:** Postman  
**Date Tested:** April 2026  

### Summary
Performed manual API testing across 7 endpoints covering GET, POST, PUT, and DELETE request methods. Validated status codes, response bodies, and documented expected vs actual behavior.

### Test Results
| Result | Count |
|--------|-------|
| Passed | 7 |
| Failed | 0 |
| **Total** | **7** |

### Files
- `API_TEST_REPORT.xlsx` — Full API test report including method, endpoint, request body, expected vs actual status, response time, and notes

---

## Project 3: SauceDemo — UI Test Automation

**Site Tested:** https://www.saucedemo.com
**Testing Type:** Automated — UI / End-to-End
**Tools Used:** Playwright, Python, pytest
**Date:** June 2026

**Repo:** [github.com/Villegas47/saucedemo-automation](https://github.com/Villegas47/saucedemo-automation)

### Summary

Converted my manual SauceDemo test cases (Project 1) into an automated UI test suite — demonstrating the transition from manual QA to test automation. Seven automated tests cover login, cart, checkout, and product-sorting flows, each ending in an explicit assertion and using stable `data-test` selectors.

### Coverage

| # | Test | Verifies |
|---|------|----------|
| 1–3 | Login | Valid, invalid, and locked-out scenarios |
| 4–5 | Cart | Adding and removing items updates the cart badge |
| 6 | Checkout (E2E) | Full purchase reaches order confirmation |
| 7 | Sorting | Product list reorders correctly |

### Files

- Full suite in the linked repo, with a README and passing-test output

---

## Certifications

- **Postman API Test Automation Badge** — Issued April 19, 2026
  Verified by Parchment Digital Badges
  [View Verified Badge](https://badges.parchment.com/public/assertions/dUvYJ4idTRCFs1q41WcgNQ?utm_source=url_copy&identity__email=Alexandervillegas64%40yahoo.com)

*More projects coming soon.*
