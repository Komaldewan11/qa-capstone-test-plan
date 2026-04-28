# Capstone_Part1_Planning-Foundation
**QA Capstone Project — Part 1: Planning & Foundation**
A comprehensive QA project covering test strategy, manual testing, and web automation for the nopCommerce e-commerce platform. This capstone establishes a full testing foundation across web and API environments.

**Project Overview**

Item	                      Details
Application under test	    nopCommerce (e-commerce platform)
Testing types	              Manual, Functional, API, Web Automation
Automation tools	          Cypress (web), Postman (API)
Bug tracking	              Jira
API testing target	        Fake Store API (used as substitute for nopCommerce API)

**What's Inside**
1. Environment Setup

Configured nopCommerce locally for web testing
Set up Cypress for end-to-end web automation
Integrated Fake Store API for API testing (nopCommerce token authorization not available)

2. Test Plan & QA Strategy

A detailed test plan covering:
* Test objectives, scope, and out-of-scope items
* Risk analysis and mitigation strategies
* Functional, performance, and security testing approach
* Test environment definitions and timeline

3. Manual Test Cases

* Written against user stories for core e-commerce flows
* Covers: user registration, login, product search, cart, and checkout
* Defects documented and reported in Jira with evidence

4. Web Automation (Cypress)
End-to-end tests for major user flows:

User login and registration
Product search and filtering
Add to cart and checkout flow
Cross-browser compatibility checks
API testing is integrated within Cypress
Accessibility and performance checks using Cypress plugins

5. API Testing

* Tested against Fake Store API as nopCommerce API substitute
* Covered: GET products, POST orders, authentication flows
* Validated status codes, response bodies, and error handling


**Tech Stack**
Cypress — Web UI and API automation
JavaScript — Test scripting language
Postman — API test design and exploration
Jira — Defect tracking and test management
nopCommerce — Application under test (web)
Fake Store API — API testing target

**How to Run the Tests**

Prerequisites
node -v   
npm -v

Install dependencies
npm install

Open Cypress (interactive mode)
npx cypress open

Run all tests (headless)
npx cypress run

Run a specific spec
npx cypress run --spec "cypress/e2e/login.cy.js"

**Deliverables**
 Test plan document (scope, risk analysis, timelines)
 Manual test cases for web flows
 Jira defect reports
 Cypress automation scripts for major user flows
 API test coverage using Fake Store API
 Preliminary QA strategy documentation

**Key Learnings**
* Structured a QA strategy from scratch for a real e-commerce platform
* Balanced manual and automated testing across multiple test types
* Adapted testing approach when API credentials were unavailable (used Fake Store API as a practical substitute)
* Documented findings professionally for stakeholder review
