# Awansoft Power BI Dashboard – Expense Claims & Receipts

This project is a professional, plug-and-play Power BI dashboard designed for Awansoft, based on the Expense Claims and Expense Receipts modules in Acumatica ERP. It was developed during my internship at Awansoft Technology in July 2025.

## 🔍 Overview

- Built using Microsoft Power BI with Acumatica OData as the data source
- Designed to be adaptable across environments via clean Generic Inquiries (GIs) and modular dataflows
- Includes complete handover package: XMLs, PBIX, and Setup Guide

## 🧰 Tech Stack

- **Power BI Desktop**
- **Acumatica ERP (2025 local demo instance)**
- **OData v4 feeds**
- **Power BI Gen2 Dataflows**
- **Custom Measures, Tooltips, Bookmark Navigation**

## 📁 Contents

| File | Description |
|------|-------------|
| `Awansoft_ExpenseDashboard_DEV.pbix` | Power BI report file with all visuals, measures, slicers, and formatting |
| `ExpenseClaimsPBI.xml` | Generic Inquiry definition for Expense Claims module |
| `ExpenseReceiptsPBI.xml` | Generic Inquiry definition for Expense Receipts module |
| `SetupGuide.pdf` | Comprehensive guide for recreating the dashboard using your own Acumatica instance |

## 🔌 Plug-and-Play Ready

To use this dashboard in your own Acumatica environment:
1. Import the two Generic Inquiry XML files into your Acumatica instance.
2. Enable OData access.
3. Set up Power BI Dataflows or connect directly via OData.
4. Open the `.pbix` file and change the data source URL to your Acumatica OData endpoint.

All steps are detailed in the included `SetupGuide.pdf`.

## 🧑‍💼 Developed by

**Mehul Gupta**  
Intern, Awansoft Technology  
Year 12 | Garden International School  
A-Level Computer Science, Math, Music  
