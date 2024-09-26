
Project Management System
Overview
The Project Management System is a full-stack web application developed using Spring Boot for the backend and SQL for the database. The system provides a platform for users to create and manage projects with teams, assign tasks, and track their progress. It is designed for teams of all sizes, offering different subscription plans with varying features.

Features
General Features
Project Creation: Users can create projects and assign them to groups of team members.
Task Management: Each project has tasks that can be marked as:
To Be Done
In Progress
Done
User Roles:
Team Lead: Has administrative control over the team, can assign tasks, and invite members via email.
Team Members: Can update the status of tasks assigned to them.
Team Management
Invite Members: The team lead can invite members via email to join a project.
Task Assignment: Team leads can assign tasks to different team members based on their roles and responsibilities.

Subscription Plans
The system offers two types of subscription plans:

1. Free Plan:
Project Limit: Can create up to 3 projects.
No Chat Functionality: Team members cannot communicate within the platform.

3. Paid Plan:
Unlimited Projects: Users can create an unlimited number of projects.
Chat Functionality: Each project has a dedicated chat feature where team members can communicate about the project.
Pricing Plans

Plan	Features
Free Plan	- Up to 3 projects
- No chat functionality
Paid Plan	- Unlimited projects
- Project-specific chat functionality
  
Technologies Used
Spring Boot: Backend framework for building the RESTful APIs.
SQL: Used for storing data related to users, projects, tasks, and subscriptions.
Java Mail API: For sending email invitations to new team members.
Spring Security & JWT: For user authentication and authorization.

![image](https://github.com/user-attachments/assets/533b0dcf-1c4e-4f78-84b3-721083eb0196)
![image](https://github.com/user-attachments/assets/c8279c9e-5a21-4a90-a00a-cc80f24b7e9f)
![image](https://github.com/user-attachments/assets/782b6fec-77ae-47f3-becc-05df421b0ad3)
