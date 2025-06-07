# Backend API Automation - SecuritEase QE Tech Assessment

Hi there

This project is focused on API test automation using Playwright with TypeScript.  
It was created as part of the SecuritEase Quality Engineering Technical Assessment.

The tests are written against the public REST API available at:  
https://restcountries.com/v3.1/all

## What This Project Does

1. Schema Validation  
   It checks that each country object in the API response includes name, region, and languages.

2. Country Count Check  
   It confirms that the API returns at least 195 countries.

3. South Africa Language Check  
   It looks for South African Sign Language in the list of South Africa's official languages.  
   If it is not found, the test logs a warning.

## Tools and Technologies

- TypeScript  
- Playwright  
- Node.js

## How to Run the Tests

Step 1: Install dependencies  
Make sure Node.js is installed.  
Open your terminal in the project folder and run:

Step 2: Run the tests  
After the installation completes, run:
