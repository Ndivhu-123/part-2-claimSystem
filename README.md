Certainly. Here's a professional README for **Part 2** of your POE submission:

---

## README — Part 2: Functional Web Application Implementation

Part 2 of the Contract Monthly Claim System (CMCS) focuses on transforming the initial prototype into a fully functional .NET Core MVC web application. The goal is to implement key features that support claim submission, verification, document upload, and real-time tracking across different user roles.

Lecturers are able to submit claims through a clean and intuitive form that captures hours worked, hourly rate, and additional notes. The form includes a clearly visible submit button to ensure ease of use. A document upload feature is integrated into the form, allowing lecturers to attach supporting files in common formats such as PDF, DOCX, and XLSX. Uploaded files are securely stored and linked to the corresponding claim.

Programme Coordinators and Academic Managers are provided with separate views that display pending claims in a structured table format. Each claim includes essential details for verification, along with Approve and Reject buttons. Once an action is taken, the claim status updates immediately and reflects in the lecturer’s tracking view.

A real-time tracking system is implemented to display the current status of each claim. Status labels such as "Pending", "Approved by Coordinator", "Rejected by Coordinator", and "Final Approved" are used to ensure transparency throughout the approval workflow.

To maintain system reliability, unit tests are written to validate core functionalities, and error handling mechanisms are implemented to catch exceptions and display meaningful messages to users. Version control is maintained through regular commits to GitHub, with clear and descriptive messages documenting each update.

This part demonstrates the ability to build a robust, user-focused web application that supports administrative efficiency and transparent claim management.
