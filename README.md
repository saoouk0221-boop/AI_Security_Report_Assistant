# AI Security Report Assistant

![Generate Security Report](https://github.com/saoouk0221-boop/AI_Security_Report_Assistant/actions/workflows/generate-report.yml/badge.svg)

Python tool for generating security reports from vulnerability scan results.

## Latest Report

[View latest security report](reports/Security_Report.md)

## Project Goal

This project reads a port scan or vulnerability scan result from a text file and automatically generates a Markdown security report.

The goal is to practice:

- Python file processing
- Markdown report generation
- Git version control
- GitHub repository workflow
- GitHub Actions automation

## Project Structure

```txt
AI_Security_Report_Assistant/
├── .github/
│   └── workflows/
│       └── generate-report.yml
├── reports/
│   └── Security_Report.md
├── samples/
│   └── sample_scan.txt
├── templates/
├── .env
├── .gitignore
├── main.py
├── README.md
└── requirements.txt
```

## How It Works

```txt
samples/sample_scan.txt
        ↓
main.py
        ↓
reports/Security_Report.md
        ↓
GitHub Actions automation
```

## Local Usage

Run the report generator locally:

```bash
python main.py
```

If `python` does not work on Windows, use:

```bash
py main.py
```

The generated report will be saved to:

```txt
reports/Security_Report.md
```

## GitHub Actions Automation

This repository uses GitHub Actions to automatically generate the security report when changes are pushed to the `main` branch.

Workflow file:

```txt
.github/workflows/generate-report.yml
```

## Current Version

Version: v1.0

Current features:

- Read sample scan result from `samples/sample_scan.txt`
- Generate Markdown report
- Save report to `reports/Security_Report.md`
- Run automation with GitHub Actions