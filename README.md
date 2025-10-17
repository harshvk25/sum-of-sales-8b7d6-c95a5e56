# sum-of-sales-8b7d6

## Description
Automatically generated web application.

**Brief**: Publish a single-page site that fetches data.csv from attachments, sums its sales column, sets the title to 'Sales Summary 2025-10-17-20', displays the total inside #total-sales, and loads Bootstrap 5 from jsdelivr.

## Features
- Responsive web application
- Deployed on GitHub Pages
- AI-generated code

## Evaluation Criteria
- js: document.title === 'Sales Summary 2025-10-17-20'
- js: !!document.querySelector('link[href*="bootstrap"]')
- js: Math.abs(parseFloat(document.querySelector('#total-sales').textContent) - 781.0) < 0.01

## Setup
This is a static web application. No setup required.

## License
MIT License
