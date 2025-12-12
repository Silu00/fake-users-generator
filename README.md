# 🎭 Fake Users Data Generator

[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen?style=for-the-badge&logo=railway)](https://task-6-faker-production.up.railway.app/)
![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![Faker](https://img.shields.io/badge/Library-Faker-orange)

A powerful web-based tool aimed at developers and testers who need to generate realistic synthetic data on the fly. This application allows users to create, preview, and download massive datasets for testing purposes without writing a single line of code.

## Live Application
**Access the tool here:** [https://task-6-faker-production.up.railway.app/](https://task-6-faker-production.up.railway.app/)

*(Hosted on Railway)*

## Project Overview

Testing applications with "Lorem Ipsum" or generic data often fails to reveal real-world edge cases. This project solves that problem by providing a user-friendly interface to generate **context-aware** fake data (names, addresses, emails, phone numbers).

**Key Use Cases:**
* **Database Seeding:** Quickly populate SQL/NoSQL databases with thousands of records.
* **QA & Testing:** Generate edge-case data (e.g., long names, special characters in addresses).
* **Data Anonymization:** Create replacement datasets that maintain the statistical properties of real data.

## Features

* **Web Interface:** No installation required; generate data directly in the browser.
* **Realistic Data:** Powered by the `Faker` library to generate plausible identities.
* **Customizable Parameters:**
    * **Locale Support:** Generate data specific to different regions (e.g., `pl_PL`, `en_US`).
    * **Error Injection:** Simulate "dirty" data (typos, swapped characters) to test system robustness.
    * **Seed Control:** Ensure reproducibility of generated data.

## Tech Stack

* **Language:** Python 3.x
* **Core Logic:** Faker Library
* **Web Framework:** Flask 
* **Deployment:** Railway
