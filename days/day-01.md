# Day 1 — Automation Foundations
Date: 2026-03-23
Duration: 10–20m reading + 20–40m hands-on

1) Concept (ten-minute summary)
- What should and should not be automated: focus on high-value, repeatable, and risk-exposing areas; avoid brittle UI-only tests for low-value assertions; automate business-critical flows, API-level checks, and data validation.

2) Documentation link
- Setting a Foundation for Successful Test Automation — https://testautomationu.applitools.com/setting-a-foundation-for-successful-test-automation/

3) Real-world use case
- Automate nightly smoke and deploy-gate API checks for checkout and payment flows; keep UI tests for end-to-end sanity and rely on API tests for business rules.

4) Coding task (20–40m)
- Create a one-page note (README.md) capturing what to automate vs not. Implement a tiny script (Python) that reads a JSON list of app features and flags which should be automated based on tags (repeatable, high-risk, UI-only, flaky).

5) Automation task (20–40m)
- Write 3 example test ideas (API + UI) for a checkout flow; for the API test, sketch request/response schema and one negative case.

6) Review questions
- 1) What criteria justify automating a UI test vs an API test?
- 2) How does test flakiness affect test-suite ROI?
- 3) What are three signs your automation effort is becoming brittle?

7) Commit guidance
- Commit message: "day-01: automation foundations — what to automate (note + script)"
