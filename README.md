# GUARDIAN AI

## Artificial Intelligence for Digital Scam Detection and Prevention
<img width="400" alt="vera" src="https://github.com/user-attachments/assets/239c8c50-5f92-4452-84e5-c662fdafa3c3" />

GUARDIAN AI is a cybersecurity and artificial intelligence project focused on detecting, analyzing, and preventing digital scams through automated evidence analysis.

The platform combines machine learning, document inspection, website intelligence, and fraud detection techniques to identify suspicious digital content and estimate the likelihood that a message, website, document, or interaction is malicious.

The project is being developed as a research initiative focused on applying artificial intelligence to social protection, cybersecurity awareness, and digital fraud prevention.

---

# Motivation

Digital scams have become increasingly sophisticated and accessible to attackers. Every day, millions of people are exposed to:

* Phishing emails
* Fraudulent websites
* Fake invoices
* Social engineering attacks
* SMS scams (Smishing)
* Messaging application scams
* Cryptocurrency fraud
* Identity theft attempts

Many victims lack the technical knowledge required to identify these threats before damage occurs.

GUARDIAN AI aims to bridge this gap by providing an intelligent assistant capable of evaluating multiple risk indicators and presenting understandable security recommendations.

---

# Research Question

Can artificial intelligence combined with cybersecurity intelligence improve the identification of digital scams while remaining accessible to non-technical users?

---

# Objectives

## Main Objective

Develop an intelligent platform capable of identifying potential digital scams through automated analysis of messages, documents, websites, and online interactions.

## Secondary Objectives

* Detect phishing attempts.
* Analyze suspicious URLs.
* Evaluate website trustworthiness.
* Inspect PDF and office documents.
* Correlate evidence from multiple sources.
* Reduce false positives.
* Provide explainable risk assessments.
* Assist users in making safer decisions online.

---

# Core Features

## Message Analysis

Analyze:

* Emails
* SMS messages
* Chat conversations
* Social media messages
* Customer support communications

Detection indicators include:

* Urgency language
* Credential requests
* Financial manipulation attempts
* Social engineering patterns
* Suspicious sender characteristics

Example output:

```text
Scam Probability: 87%

Indicators:
✓ Urgency tactics detected
✓ Credential request detected
✓ Suspicious sender pattern
✓ Financial pressure language
```

---

## Link Analysis

Evaluate URLs and websites through:

* SSL/TLS certificate validation
* Domain reputation analysis
* Domain age verification
* DNS inspection
* Redirect chain analysis
* Typosquatting detection
* Brand impersonation detection

Example:

```text
Risk Level: High

Reasons:
- Domain registered recently
- Similar to a known banking website
- Multiple redirects detected
```

---

## Document Analysis

Supported files:

* PDF
* DOCX
* XLSX
* ZIP archives

Security checks:

* Embedded URLs
* Suspicious macros
* Obfuscated content
* Executable payload indicators
* Potential exploit vectors

---

## Evidence Correlation Engine

Unlike traditional scanners that rely on a single indicator, GUARDIAN AI combines multiple sources of evidence.

| Evidence                | Risk Level |
| ----------------------- | ---------- |
| Suspicious language     | Medium     |
| Newly registered domain | Medium     |
| Certificate anomalies   | High       |
| Credential request      | High       |

The system correlates all observations to generate a final confidence score.

---

## Explainable AI

A key objective of GUARDIAN AI is transparency.

Rather than simply classifying content as malicious or benign, the platform explains:

* Why a decision was made.
* Which indicators were detected.
* Which evidence contributed to the risk score.
* How confident the system is in its assessment.

---

# Architecture

```text
                    ┌─────────────────┐
                    │ User Input      │
                    └────────┬────────┘
                             │
                             ▼
                 ┌─────────────────────┐
                 │ Data Processing     │
                 └────────┬────────────┘
                          │

        ┌─────────────────┼─────────────────┐

        ▼                 ▼                 ▼

 Message Engine    Link Engine     Document Engine

        ▼                 ▼                 ▼

          ┌────────────────────────────┐
          │ Evidence Correlation Layer │
          └─────────────┬──────────────┘
                        ▼

              Machine Learning Engine

                        ▼

                 Risk Assessment

                        ▼

                   User Report
```

---

# Technology Stack

## Backend

* Python
* Flask
* PostgreSQL
* Docker

## Frontend

* HTML
* CSS
* JavaScript

## Artificial Intelligence

Potential models:

* XGBoost
* LightGBM
* Random Forest
* Ensemble Learning
* Transformer-based architectures

## Cybersecurity Components

* URL Intelligence
* Certificate Validation
* DNS Analysis
* Threat Intelligence
* Heuristic Detection
* Reputation Systems

---

# Future Components

Planned features include:

* Browser Extension
* Email Plugin
* SMS Protection Module
* Mobile Application
* Community Reporting System
* Real-Time Threat Intelligence
* Explainable AI Dashboard
* Multi-Language Support

---

# Social Impact

GUARDIAN AI aims to contribute to:

* Digital inclusion
* Cybersecurity education
* Fraud prevention
* Online safety awareness
* Protection of vulnerable populations

Potential beneficiaries include:

* Students
* Elderly users
* Small businesses
* Educational institutions
* Public organizations

---

# Research Status

This project is currently under active research and development.

The repository will remain private during the research and evaluation phases and may be released publicly after scientific publication and project presentation.

---

# License

License to be defined upon completion of the research phase.

---

## Motto

> Trust, but verify.
>
> Intelligence for safer digital interactions.
