Automated Employee Expense Management System
Objective
The Automated Employee Expense Management System is designed to streamline the process of managing reimbursable employee expenses. It provides an intuitive interface for voucher entry, approval workflows, 
case management, and reporting, ensuring efficiency and transparency.

Functional Requirements
1. Voucher Entry
Purpose: Allow employees to enter expense vouchers for reimbursable expenses.
Features:
Voucher header with summary details.
Multiple line items for detailed expense information e.g., date, name, type(Transport, Food, Accomadation, Miscellaneous), description and amount.
2. Multi-Level Workflow
Purpose: Facilitate an automated approval process.
Features:
Workflow routing based on the employee's department and designation.
Dynamic approval levels based on voucher amount and supervisors' approval limits.
3. Case Management
Purpose: Enable tracking and management of each voucher's lifecycle.
Features:
A new process instance (case) for every voucher.
Manager Inbox for pending approvals.
Employee tracking for submission progress.
4. Draft Vouchers
Purpose: Provide flexibility to save incomplete vouchers.
Features:
Ability to save vouchers as drafts.
Option to complete and submit drafts later.
5. Rejection Flow
Purpose: Handle rejected vouchers effectively.
Features:
Managers can reject vouchers with reasons.
Employees can edit and resubmit rejected vouchers with additional details.
6. Accounts View
Purpose: Facilitate final processing of approved vouchers.
Features:
Accounts team can view approved vouchers for all employees.
Pie chart representation for all accepted vouchers according to there name.

Tech Stack
Frontend: HTML, CSS, Bootstrap, JavaScript

Features
User-friendly interface for voucher entry.
Robust multi-level approval workflow.
Real-time tracking and notifications.
Detailed reporting and analytics.
Secure and role-based access control.
Installation and Setup

Clone the repository:
git clone https://github.com/Poonam-2704/expense-management.git

Navigate to the project directory:
cd expense-management

Install dependencies:
npm install 

Start the application:
npm start 

Screenshots
Home Page
![Screenshot 2025-01-24 193528](https://github.com/user-attachments/assets/ddd6634e-1ed7-4fe7-8205-35e855564bf9)

![Screenshot 2025-01-24 193558](https://github.com/user-attachments/assets/45c4d2b6-cc62-4ab1-8268-9ffcccfa57bd)

![Screenshot 2025-01-24 193620](https://github.com/user-attachments/assets/5f1938c0-b242-41ee-8435-2ee78523cbe3)

Voucher Entry
![Screenshot 2025-01-24 193643](https://github.com/user-attachments/assets/114d2120-b2fb-432b-af9f-9532690f700e)

Case Management
![Screenshot 2025-01-24 193724](https://github.com/user-attachments/assets/6230b407-0e00-4bea-bdc8-32252cb4f2a5)

Draft Voucher
![Screenshot 2025-01-24 193735](https://github.com/user-attachments/assets/0b4685c8-ec15-4d46-96c4-930c3d28734d)

Rejection Flow
![Screenshot 2025-01-24 193755](https://github.com/user-attachments/assets/7f98a055-9125-4265-9768-771e1dcf7a2c)

Account View/Profile
![Screenshot 2025-01-24 193818](https://github.com/user-attachments/assets/656e669d-fa90-41e6-b0b8-ec9396a3e45a)



Contributing
Contributions are welcome! Please follow these steps:

Fork the repository.
Create a new branch for your feature or bugfix:
git checkout -b feature-name
Commit your changes:
git commit -m "Add feature-name"
Push to your fork:
git push origin feature-name
Create a pull request.

Contact
For questions or feedback, please contact Poonam-2704 via GitHub.
