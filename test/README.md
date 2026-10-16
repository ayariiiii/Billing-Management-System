# StoreOps Pro - 5 Distribution Centers Ticket & Maintenance Management System

An interactive, responsive management system designed for multi-location distribution center operations, equipment maintenance tracking, and vendor service invoicing.

## Features

### 1. Dedicated 5 Distribution Center Pages + Master Consolidated Dashboard
Switch seamlessly between:
- **DC 1**: DC-SLG - **DC Silang** (*Silang, Cavite*)
- **DC 2**: DC-CAL - **DC Calamba** (*Calamba, Laguna*)
- **DC 3**: DC-SAR - **DC Sariaya** (*Sariaya, Quezon*)
- **DC 4**: DC-MAR - **DC Marilao** (*Marilao, Bulacan*)
- **DC 5**: DC-MEX - **DC Mexico** (*Mexico, Pampanga*)
- **Executive Master View**: All 5 Distribution Centers combined for cross-enterprise KPI tracking and aggregation.
- **DC Customizer**: Edit DC Codes, Names, and Branch locations dynamically via the settings modal.

### 2. All 23 Required Fields Included
Every single record tracks the exact 23 required fields:
1. `STATUS` (Pending, In Progress, Resolved, Closed, On Hold)
2. `PO` (Purchase Order Number - **Optional**)
3. `Ticket number` (Identifier, e.g. TKT-1001)
4. `SI. Number` (Sales/Service Invoice Number - **Optional**)
5. `VENDOR` (Service Vendor / Contractor)
6. `STORE CODE` (e.g. DC-SLG, DC-CAL, DC-SAR, DC-MAR, DC-MEX)
7. `STORE NAME` (e.g. DC Silang, DC Calamba, DC Sariaya, DC Marilao, DC Mexico)
8. `BRANCH` (Branch Location)
9. `DATE ISSUED` (Issuance Date)
10. `ISSUE` (Short Issue Summary / Title)
11. `ACTION TAKEN` (Corrective and repair action performed)
12. `MOBILIZATION` (Transportation / mobilization cost in ₱)
13. `SERVICE CHARGE` (Labor / diagnostic service charge in ₱)
14. `AMOUNT` (Parts & hardware replacement amount in ₱)
15. `TOTAL AMOUNT` (**Auto-calculated**: `MOBILIZATION` + `SERVICE CHARGE` + `AMOUNT` in ₱)
16. `DESCRIPTION` (Detailed description of the issue)
17. `INSTALLED DATE` (Equipment installation date)
18. `WARRANTY` (Warranty status: Active, Expired, Extended, Not Covered)
19. `REMARKS` (Technician and managerial notes)
20. `DATE RECEIVED` (Equipment turnover / date received)
21. `LEVEL OF ISSUE` (Priority badge: Critical, High, Medium, Low)
22. `CATEGORY ISSUE` (POS / Hardware, HVAC / Cooling, Electrical, Network / IT, Plumbing / Facility, Security / CCTV)
23. `MONTH` (Reporting Month: January - December)

### 3. Key Functionalities
- **Ticket Modification & Editing**: Modify ticket parameters using the dedicated Edit button on the ticket form, directly from the table, or from the official Work Order sheet.
- **Optional PO & SI**: Both PO and SI fields are optional. Leave blank without validation errors.
- **Philippine Peso Currency (₱)**: All financial calculations and summaries format in Philippine Peso (`₱`).
- **Real-Time Financial Auto-Calculation**: Computes `TOTAL AMOUNT = MOBILIZATION + SERVICE CHARGE + AMOUNT` as numbers are entered into the modal.
- **DC Auto-Fill**: Creating a ticket while on a DC's tab automatically pre-fills its DC Code, Name, and Branch.
- **Column Visibility Manager**: Toggle any of the 23 columns on/off, or switch between pre-configured views (All Columns, Essential, Financial Focus).
- **Search & Filters**: Multi-faceted filtering by Month, Status, Priority Level, and Category, alongside instant text search (`/` hotkey).
- **Official Printable Work Order Sheet**: Generate and print professional service order invoices with signatures and fee breakdowns in ₱.
- **Import & Export (CSV)**: Export the complete 23-column dataset to CSV or import spreadsheet data directly into the system.
- **Zero-Dependency Local Persistence**: Automatically saves updates in browser `localStorage`. Works instantly without needing server installations!

## How to Run

### Option 1: Double Click
Double click `launch.bat` or open `index.html` directly in any web browser (Google Chrome, Microsoft Edge, Brave, Firefox).

### Option 2: Browser
Open `file:///c:/Users/ATP/Desktop/test/index.html` in your browser.
