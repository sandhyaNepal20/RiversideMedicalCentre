
# Riverside Medical Centre
## Requirements Analysis

### 1. Project Overview
Riverside Medical Centre currently uses spreadsheets and disconnected records to manage patient details, healthcare professionals and appointments. This can lead to duplicated information, inconsistent records and difficulties retrieving appointment histories.

The proposed system will use Python and SQLite to manage administrative information in a structured relational database.

### 2. Functional Requirements
FR1: Add, view, update and delete patient records.

FR2: Manage healthcare professional information.

FR3: Store details of medical services offered.

FR4: Create, view and update appointments.

FR5: Record appointment outcomes and follow-up details.

FR6: Search and filter appointment information.

FR7: Generate useful summaries using SQL queries.

### 3. Non-Functional Requirements
NFR1: Maintain data consistency using primary and foreign keys.

NFR2: Reduce duplicated information through normalisation.

NFR3: Handle invalid inputs and database errors.

NFR4: Use fictional patient information for testing.

NFR5: Provide a simple, usable Python interface.

### 4. Assumptions
A1: Each patient has a unique patient ID.

A2: Each healthcare professional has a unique staff ID.

A3: One patient can have multiple appointments.

A4: One healthcare professional can have multiple appointments.

A5: Each appointment involves one patient, one professional and one service.

A6: Each appointment can have at most one appointment outcome record.

A7: Appointment statuses include Scheduled, Completed and Cancelled.
