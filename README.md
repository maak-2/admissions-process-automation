🎓 Admissions Process Automation Solution
📌 Project Overview
This project demonstrates an end-to-end admissions process automation solution built using Microsoft Power Platform and Microsoft 365 technologies.
The solution was designed to streamline the student admissions process by reducing manual administration, improving operational visibility, standardising applicant communications, and introducing governance through SLA monitoring.
This project was developed as part of an interview case study for a Higher Education institution and showcases practical application of Power Automate, SharePoint, Forms and Outlook within a business process improvement context.
 
🎯 Business Challenge
The existing admissions process relied heavily on manual activities:
•	Applications arrived via email.
•	Supporting documents were submitted separately.
•	Completeness checks were performed manually.
•	Academic reviews were routed manually.
•	Offer and rejection emails were drafted individually.
•	Tracking application progress was inconsistent.
These challenges created:
•	Delays in processing
•	Increased administrative workload
•	Limited visibility of application status
•	Risk of missed applications
•	Inconsistent applicant communication
 
🏗 Solution Architecture
Microsoft 365 Components Used
Component	Purpose
Microsoft Forms	Applicant data capture
Power Automate	Workflow orchestration
SharePoint List	Application tracking and case management
SharePoint Document Library	Document storage
Outlook	Notifications and approval actions
Scheduled Power Automate Flow	SLA monitoring and escalation
 
🔄 End-to-End Workflow
Application Intake
1.	Applicant submits an application using Microsoft Forms.
2.	Power Automate retrieves application details.
3.	A SharePoint application record is automatically created.
4.	A dedicated document folder is generated for the applicant.
Document Validation
5.	The workflow validates whether all required documents have been submitted.
If documents are incomplete:
•	Applicant receives a missing documents notification.
•	Application status is updated to "Incomplete".
•	Case remains visible for follow-up.
If documents are complete:
•	Application progresses automatically to academic review.
Academic Review
6.	Reviewer receives an approval request email.
7.	Reviewer selects:
•	Approve
•	Reject
Applicant Communication
8.	Applicant automatically receives the appropriate outcome notification.
•	Offer notification
•	Rejection notification
Case Management
9.	SharePoint tracking records are automatically updated throughout the process.
 
📈 SLA Monitoring & Governance
A separate monitoring flow was created to provide governance and service management.
The SLA flow:
•	Runs on a scheduled basis.
•	Checks for applications awaiting action.
•	Identifies overdue cases.
•	Sends escalation notifications to the admissions team.
This helps ensure applications are reviewed within agreed service levels and reduces the risk of missed or delayed applications.
 
✨ Key Features
•	Automated admissions intake
•	SharePoint case management
•	Academic approval workflow
•	Automated applicant communications
•	Document validation
•	SLA monitoring and escalation
•	Workflow status tracking
•	Microsoft 365 integration
 
📊 Business Benefits
Operational Efficiency
•	Reduced manual administration
•	Faster application processing
•	Reduced email handling
Improved Visibility
•	Centralised application tracking
•	Real-time status updates
•	Improved operational oversight
Better Applicant Experience
•	Faster responses
•	Consistent communication
•	Clear application status
Governance & Compliance
•	SLA monitoring
•	Escalation process
•	Improved accountability
 
📸 Solution Screenshots
Screenshots demonstrating:
•	Workflow automation
•	Approval emails
•	SharePoint application tracking
•	Applicant communications
•	SLA monitoring
are included within the repository.
 
 
👤 Author
K.A
MSc Data Science & Business Analytics
Power Platform | Data Analytics | Process Improvement | Business Analysis

