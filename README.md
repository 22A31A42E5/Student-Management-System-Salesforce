# Student Management System – Automating Admissions and Fee Tracking in Education

## Problem Statement
Educational institutions often rely on manual methods such as spreadsheets or paper records to manage student data, course enrollments, and fee payments.  
This leads to:
- Data duplication and inconsistency  
- Difficulty tracking payments and balances  
- Limited visibility for administrators and finance teams  
- Delays in student registration and communication  

The absence of a centralized, automated system causes inefficiencies in managing student records, calculating fees, and generating reports.  

---

## Proposed Salesforce Solution
The **Salesforce Student Management System (EduCRM)** provides a unified CRM platform for automating student registration, course enrollment, payment tracking, and reporting.  

### Core Components:
- **Student Registration:** Capture student details (name, email, phone, course enrolled).  
- **Course Management:** Define courses with duration, fee, and capacity details.  
- **Payment Tracking:** Record payments with date, amount, and mode of payment.  
- **Automated Fee Updates:** Apex trigger updates total fees paid per student when a payment is recorded.  
- **Email Notifications:** Automated welcome email to new students using Salesforce Flow.  
- **Reports & Dashboards:** Real-time insights on:
  - Total fees collected  
  - Pending payments  
  - Course-wise enrollment distribution  
  - Monthly collection trends  

---

## Key Features & Automations
- **Apex Trigger:** Updates student’s total fees paid automatically.  
- **Flows:** Sends confirmation emails upon new student creation.  
- **Validation Rules:** Prevent invalid or excessive fee entries.  
- **Approval Process:** Handles refund requests requiring admin approval.  
- **Security & Roles:** Custom profiles for Admin, Counselor, Accountant, and Principal.  
- **Experience Cloud Portal:** Allows students to log in and view fee status.  

---

## Reports & Dashboards
- **Reports Created:**
  - Fees Collected per Month  
  - Course-Wise Enrollment Summary  
  
- **Dashboards:**
  - Total Students Enrolled  
  - Total Fees Collected  
  - Course-Wise Distribution  

---

## Key Benefits
- **Automation:** Eliminates manual calculations and repetitive HR tasks.  
- **Transparency:** Students and admins have real-time visibility into records.  
- **Data Accuracy:** Reduces errors in payments and enrollment tracking.  
- **Efficiency:** Saves time for finance and administration teams.  
- **Analytics:** Helps management make informed academic and financial decisions.  

---

## DEMO VIDEO LINK
🎥 [Click to View Demo](https://drive.google.com/file/d/1BifjF7ldNUKOQWi-AFR7tGL-MzICW1N5/view?usp=drivesdk)

---

**Author:** Patneedi Naga Venkata Sri Sailaja  
**Platform:** Salesforce Developer Org  
**Project Type:** CRM Application
