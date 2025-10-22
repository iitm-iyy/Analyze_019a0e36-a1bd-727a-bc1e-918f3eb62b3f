# Analyze_019a0e36-a1bd-727a-bc1e-918f3eb62b3f

You are given two attachments: execute.py and data.xlsx.

- Commit execute.py after fixing the non-trivial error in it.
- Ensure it runs on Python 3.11+ with Pandas 2.3.
- Convert data.xlsx to data.csv and commit it.
- Add a GitHub Actions push workflow at .github/workflows/ci.yml that:
  - Runs ruff and shows its results in the CI log
  - Runs: python execute.py > result.json
  - Publishes result.json via GitHub Pages
- Do not commit result.json; it must be generated in CI.

## Overview
This repository contains a static web application built for the specified task.

## Setup
No build step required. The app is served via GitHub Pages.

## Usage
Open [https://iitm-iyy.github.io/Analyze_019a0e36-a1bd-727a-bc1e-918f3eb62b3f/](https://iitm-iyy.github.io/Analyze_019a0e36-a1bd-727a-bc1e-918f3eb62b3f/) in your browser.

## Code Explanation
- `index.html`: The main application file, generated to meet task requirements.
  - Loads required libraries via CDN.
  - Implements the task as per the provided brief.

## License
MIT
