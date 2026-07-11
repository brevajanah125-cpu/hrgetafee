# HRGetafe: Human Resources Information System for Getafe LGU

**Proposed Project Title:** HRGetafe: Human Resources Information System for Getafe LGU

**Researchers:**
- Leader: Chay B. Cutarra
- Members: Daryl Joyce M. Emah, Rose C. Breva

**Date Submitted:** June 3, 2026

## Project Overview

HRGetafe is a comprehensive Human Resources Information System designed to manage human resource operations of the Getafe Local Government Unit. The system focuses on managing HR operations such as employee record management, attendance monitoring, leave applications, payroll processing, and report generation.

### Sustainable Development Goals
- SDG 8 - Decent Work and Economic Growth
- SDG 16 - Peace, Justice, and Strong Institutions
- SDG 9 - Industry, Innovation, and Infrastructure

## Key Features

✅ Employee Records Management  
✅ Attendance Tracking (Biometric Import)  
✅ Leave Application & Management  
✅ Payroll Processing  
✅ Report Generation  
✅ Role-Based Access Control (Admin, HR Staff, Employee)  
✅ Data Security & Integrity  
✅ User Authentication & Session Management  

## Quick Start

```bash
npm install
cp .env.example .env
mysql -u root -p < config/db-schema.sql
npm run dev
```

Server will start on `http://localhost:3000`

## Documentation

See `PROJECT_SPECIFICATIONS.md` and `IMPLEMENTATION_GUIDE.md` for detailed information.
