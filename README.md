This project is a Web application that generates random, fake user information using SQL Stored Procedures for data generation logic and Python for the web interface. There is link to an app: https://task-6-faker-production.up.railway.app/

Application allows users to generate batches of fake user data (names, addresses, phone numbers, etc.) based on a selected locale and a seed value. The core logic for generating data is implemented exclusively within the database using Stored Procedures to ensure performance and separation of concerns.

App ensures reproducibility: using the same seed and locale will always produce the exact same sequence of data.

Features:
* Locale Support: Generate data specific to regions (e.g., en_US, de_DE, pl_PL).
  * Single extensible database design using a [names] table with a [locale] column.
* Deterministic Generation: Identical seeds produce identical results (dependent on locale, batch index, and position).
* High Performance:
  * Logic resides in SQL Stored Procedures.
  * Optimized for generating batches (10 to 1000000 records).
* Rich User Data:
  * Full Name (with optional titles, middle names).
  * Localized Address.
  * Phone Numbers and Emails.
  * Physical Attributes (Height, Weight, Eye Color, Skin Tone).
  * Geographic Coordinates (Uniformly distributed on a sphere).
