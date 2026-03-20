# Banking-Management-System
A production‑inspired banking system built using advanced SQL. It supports secure transactions, fraud detection, multi‑account management, auditing, and data analytics.

🗄️ Database Architecture

8+ core tables: Customers, Accounts, Transactions, Beneficiaries, Branches, Cards, Loans, FraudAlerts
Fully normalized schema (3NF)
Foreign key constraints with cascading rules


⚙️ Core Features
1. Customer & Account Management

Add/update customer profiles
Create Savings, Current, FD accounts
Auto‑generated account numbers

2. Transaction Processing

Deposit, withdrawal, transfer
ACID‑compliant money transfer module
Transaction logs with timestamps

3. Fraud Detection

Trigger alerts for unusual withdrawals
Rapid‑transaction detection (within 1 min)
Balance violation protection

4. Stored Procedures

sp_deposit(amount, account_id)
sp_withdraw(amount, account_id)
sp_transfer(sender, receiver, amount)
sp_calculate_emi(loan_id)
sp_monthly_interest()

5. Analytical Queries

Highest balance customers
Daily/Monthly transaction volume
Branch‑wise performance
Dormant accounts report
