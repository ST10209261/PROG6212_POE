PROG6212_POE
Contract Monthly Claim System (CMCS)

Overview 
The Contract Monthly Claim System is a streamlined solution designed to automate the claim submission, verification, and approval processes for academic institutions. This system enhances efficiency and transparency by providing dedicated views for Lecturers, Programme Coordinators, Academic Managers, and HR personnel.  

---

Features

1. Lecturer View
- **Claim Submission**: Lecturers can input hours worked, hourly rates, and additional notes to submit claims.  
- **Automation**:  
  - Auto-calculates the total payment based on hours worked and hourly rate.  
  - Validates data entry to prevent errors and inaccuracies.  
- Tools Used:  
  - **Frontend**: ASP.NET Core MVC, jQuery for real-time calculations and validation.  
  - **Backend**: Entity Framework for database interaction.  

---

2. Programme Coordinator and Academic Manager View**  
- Claim Management:  
  - Efficient verification and approval/rejection of submitted claims.  
  - Automated checks against predefined policies, including hours worked and rates.  
- Approval Workflow**:  
  - Streamlines the decision-making process with predefined criteria.  
Tools Used:  
  - ASP.NET Identity for authentication and role-based authorization.  
  - ASP.NET Web API for seamless front-end and back-end communication.  
  - FluentValidation library for automated approval workflows.  

---
3. HR View**  
- **Claim Processing**:  
  - Automatically generates invoices or reports for approved claims.  
  - Facilitates updates to lecturer data (e.g., contact information).  
- **Automation**:  
  - Summarizes approved claims into reports for payment processing.  
- **Tools Used**:  
  - ASP.NET Core Razor Pages for HR interfaces.  
  - Reporting Tools: Crystal Reports or SQL Server Reporting Services (SSRS).  



Technology Stack
- **Framework**: ASP.NET Core MVC  
- **Frontend**: HTML, CSS, Bootstrap, jQuery  
- **Backend**: C#, ASP.NET Web API, Entity Framework  
- **Database**: SQL Server  
- **Reporting**: Crystal Reports / SSRS  



Version Control
- The project is maintained in a GitHub repository with regular commits.  
- **Commit Frequency**: Minimum of 10 commits with clear and descriptive messages.  
- Examples of commit messages:  
  - "Added auto-calculation feature for lecturer claim submission."  
  - "Implemented role-based authentication using ASP.NET Identity."  


Project Deliverables

1. Enhanced Application 
- Complete functionality for all user roles.  
- Automated workflows for claims submission, verification, and approval.  

. PowerPoint Presentation
- Highlights the system’s features, functionality, and benefits.  
- Visually appealing and informative.
-
- 3. Version Control
- Repository with source code and documentation pushed to GitHub.  

4. Lecturer Feedback Document
- Summarizes feedback received from lecturers.  
- Details on how the recommendations were implemented in the system.  

---

Setup and Installation

Prerequisites 
- Visual Studio with ASP.NET Core development workload installed.  
- SQL Server for database setup.  

Steps to Run  
1. Clone the repository from GitHub.  
2. Open the solution in Visual Studio.  
3. Update `appsettings.json` with your database connection string.  
4. Run the migrations to set up the database:  
   ```bash  
   dotnet ef database update  
   ```  
5. Run the application:  
   ```bash  
   dotnet run  
   ```  
6. Access the application at `http://localhost:5000`.  



Future Enhancements 
- Add email notifications for claim approvals and rejections.  
- Implement advanced analytics for HR to monitor claim trends.  
- Introduce multi-language support for accessibility.  





