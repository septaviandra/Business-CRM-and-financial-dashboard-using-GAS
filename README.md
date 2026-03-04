<img width="56" height="56" alt="image" src="https://github.com/user-attachments/assets/55a03e0f-f74c-485e-a828-40af154e16b1" />Business CRM Dashboard (Google Apps Script)

This project is a custom CRM and financial dashboard system built using Google Apps Script and Google Sheets.

The goal of the system is to transform Google Sheets into a lightweight business management platform that supports multi-user access, financial tracking, and operational workflows.

⚠️ Note:
This repository contains documentation only for portfolio purposes.
The source code is kept private.

Project Overview

The system provides an internal web-based dashboard for managing:
Customers
Transactions
Expenses
Inventory
Delivery Orders
Financial reports

It is deployed as a Google Apps Script Web App, allowing teams to access the system through a browser.

Key Features
Authentication System
Secure login
Session validation
Role-based access control
User roles supported:
    Admin
    Sales
    Finance
   Warehouse
Financial Dashboard

The dashboard displays:
 Total Revenue
 Total Expenses
 Net Profit
 Monthly financial summary
 Recent transactions

To improve performance, the dashboard uses:
 Batched API calls
 Google Apps Script CacheService
 Optimized sheet queries

Customer Management

The system includes a simple CRM module:
Add customers
Update customer information
Track company data
Maintain a customer database

ransaction Management
Features include:
Record income transactions
Link transactions to customers
Void transactions
Paginated transaction history

Expense Tracking
Expense module supports:
Expense recording
Approval workflow
Expense deletion

Automatic dashboard refresh
Inventory System
Inventory features:
Item management
SKU tracking
Stock quantity tracking
Minimum stock levels

Stock adjustments (IN / OUT)
Delivery Orders
Delivery management system includes:
Create delivery orders
Assign items and quantities
Track delivery status
Update warehouse stock

Audit Logging
The system automatically records:
User actions
Data changes
System events

This helps maintain internal accountability.
System Architecture
Frontend
HTML + JavaScript
Backend
Google Apps Script
Database
Google Sheets

Architecture flow:

User Interface
↓
Apps Script Web App
↓
Business Logic Layer
↓
Google Sheets Data Storage

 Performance Optimization

To ensure the dashboard loads quickly, the system implements:

Server-side caching

Batched data requests

Paginated data queries

Optimized sheet access patterns

These improvements significantly reduce loading time for large datasets.

🧑‍💻 Author

Septavianus
Automation & Data Systems Developer

Specializing in:

Google Apps Script automation

Google Sheets business systems

Internal dashboards

Workflow automation

📄 Note

The full source code is not publicly available.

This repository is intended to demonstrate:

system architecture

feature set

technical approach

for portfolio purposes.
