# **Procurement Management System (Odoo 17)**
🚀 **An end-to-end Procurement Management System built with Odoo 17** 🚀  

This project is part of the **BJIT Academy Youth Skill Development Training Program (Batch: Nov’24 ~ Feb’25)** and aims to streamline **supplier registration, RFP (Request for Purchase) management, and RFQ (Request for Quotation) processing** in a structured and efficient manner.

---

## **🔹 Key Features**
### ✅ **Supplier Management**
- **Email OTP Verification**: Secure email-based verification for suppliers.
- **Supplier Registration**: A structured registration form with company, financial, and certification details.
- **Two-Step Approval Process**: Reviewer and Approver-based verification for supplier registration.
- **Automated Vendor Creation**: Approved suppliers are automatically registered as vendors.

### ✅ **RFP & RFQ Management**
- **RFP Creation & Publishing**: Reviewers can create and publish RFPs.
- **Quotation Submission**: Suppliers can submit quotations directly via the portal.
- **Automated RFQ Generation**: Upon quotation submission, an RFQ is generated.
- **Quotation Review & Approval**: Reviewers can score and recommend suppliers based on delivery terms, pricing, and warranty.

### ✅ **Report Generation**
- **Detailed RFP Reports**: Generate **QWeb-based HTML reports** and **Excel reports**.
- **Supplier-Based Filtering**: Generate reports for specific suppliers over a defined date range.
- **Auto-validation**: Ensures correct input and prevents inconsistencies.

### ✅ **Interactive Dashboard (OWL)**
- **Supplier-Wise RFQ Statistics**: View approved RFQs and total procurement amounts.
- **Product Breakdown Analytics**: Displays product-wise procurement trends.
- **Date Range Filtering**: Users can select periods such as "This Week", "Last Month", etc.
- **Graph & Pivot Views**: Visual insights through **charts and tables**.

### ✅ **Technical Implementation**
- **Built on Odoo 17**: Fully integrated with the latest Odoo ERP system.
- **OWL (Odoo Web Library) for Dashboard**: Provides a dynamic and interactive frontend.
- **Secure Role-Based Access**: Suppliers, Reviewers, and Approvers have controlled permissions.
- **Dockerized Deployment**: The system is fully containerized with **Nginx as a reverse proxy**.

---

## **🔹 User Roles & Permissions**
| **Role**    | **Permissions** |
|------------|---------------|
| **Supplier** | Register, view RFPs, submit quotations |
| **Reviewer** | Create RFPs, review suppliers & quotations, recommend approvals |
| **Approver** | Approve/reject supplier registration, publish RFPs, finalize vendor selection |

---

## **🔹 Project Deliverables**
- 📌 **Full Odoo 17 Implementation**  
- 📌 **Dockerized Application with Nginx Configuration**  
- 📌 **Comprehensive Technical Documentation**  
- 📌 **Role-Based Security & Workflow Automation**  

This project follows **Odoo 17 best practices** and **strict coding guidelines** to ensure reliability and scalability.

---

## **🔹 Installation Guide**
To set up the project locally:
```bash
git clone https://github.com/Shahriar707/Procurement-Management-System-with-Odoo-17.git
cd Procurement-Management-System-with-Odoo-17

You will find the nginx and dockerized version of this project in the following URL:

https://github.com/Shahriar707/Dockerized-Procurement-Management-System-with-Odoo-17
