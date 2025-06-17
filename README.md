# SQL_Code_Challenge
Hands-on DBMS learning project with some sample employee records and multiple SQL queries.

# CareerHub – The Job Board

## 📄 Project Description

**CareerHub** is a sample SQL database project that simulates a job board system. It connects **Companies**, **Jobs**, **Applicants**, and **Applications** through relational schema design and enables comprehensive querying for recruitment, analytics, and HR purposes.

This project demonstrates the use of:
- SQL DDL and DML operations
- Relational integrity with foreign key constraints
- Realistic datasets with over 20 companies, 40+ job listings, and 40+ applicants
- SQL queries to handle common HR scenarios

## 🛠️ Technologies Used
- Microsoft SQL Server
- Visual Studio (for running SQL queries)
- GitHub (for version control and documentation)

---

## 📂 Database Schema Overview

### Tables
1. **Companies**
   - Stores company name and location
2. **Jobs**
   - Job details linked to Companies
3. **Applicants**
   - Contains applicant profile and experience data
4. **Applications**
   - Tracks which applicant applied to which job

### Relationships
- `Jobs.CompanyID` → `Companies.CompanyID`
- `Applications.JobID` → `Jobs.JobID`
- `Applications.ApplicantID` → `Applicants.ApplicantID`

---

🧠 Learning Outcomes
Design normalized databases with proper keys

Practice SQL querying with JOIN, GROUP BY, HAVING, SUBQUERY, LEFT JOIN

Understand job board data handling and applicant tracking logic

---

📧 Contact
Author: Yohini K
📩 Email: yohinikandavel11@gmail.com
🔗 LinkedIn


