Prebook-Web-App-QA-Testing-Report
This repository contains a manual QA testing report for the Prebook web application, accessible at https://prebook.createstir.com. The primary objective was to identify usability and functional issues that could affect the user experience and platform reliability. 
# Prebook Web App – QA Testing Report

This repository contains the manual QA testing report for the `prebook.createstir.com` web application. The report highlights several usability, validation, and interaction issues discovered during testing.

Website Tested
[https://prebook.createstir.com](https://prebook.createstir.com)

Project Overview
The goal of this QA effort was to assess the user experience, responsiveness, and form behavior on the Prebook platform. Key functional issues were identified and documented with descriptions and evidence.

Major Issues Found
- ❌ After canceling the payment popup, the entire page becomes unresponsive except the navbar.
- ❌ Submitting a form with only spaces in the name field does not trigger validation errors.
- ❌ UI components become partially non-functional after specific actions.

Testing Details
- **Type:** Manual Testing
- **Tools Used:** Browser (Chrome/Firefox), Screenshots
- **Platform:** Desktop

Files Included
- `OOOLLOO.pdf`: Full testing report with screenshots, error descriptions, and reproduction steps.

Suggestions
- Implement stricter input validation on form fields.
- Fix JavaScript/UI bugs related to modal behavior and DOM freezing.
- Improve overall user experience by adding error messages and graceful fallbacks.

Author
**Goutam Dhingra**

Date of Testing
June 2025
