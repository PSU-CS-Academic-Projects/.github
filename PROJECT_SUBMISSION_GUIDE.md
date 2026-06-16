# PSU-CS-Academic-Projects
# Project Submission Guide
## Purpose
This guide defines the standards for repositories submitted to PSU-CS-Academic-Projects.
The objective is to maintain consistency across projects while making them easy for future students to understand, explore, and learn from.
---
# Repository Naming
Repositories should use a clear and descriptive project name.
## Good Examples
* `Student-Attendance-System`
* `Library-Management-System`
* `Campus-Navigation-App`
* `Online-Enrollment-System`
* `Cuyonon-ASR`
## Avoid
* `project`
* `system`
* `thesis`
* `finalproject`
* `group1`
---
# Required README
Every repository must contain a `README.md` file.
The README should include the following sections. **Please use the exact Markdown headings provided so that the organization's automation script can parse your project successfully.**
## Project Title
Name of the project (Use a top-level `#` heading).
## Project Information
### Subject
Examples:
* Web Systems and Technologies
* System Integration Architecture
### Academic Year
Example:
2025-2026
### Project Category
Examples:
* Web Development
* Mobile Development
* Artificial Intelligence
* Machine Learning
* Cybersecurity
* Game Development
### Members (Required for Parsing)
List all project members as a bulleted list under the exact `### Members` heading.
```markdown
### Members
* John Doe
* Jane Smith
```
### Instructor
Name of the instructor.
---
## Project Description
Provide a brief explanation of the project and its purpose.
---
## Features
List the major features of the system.
Example:
* User Authentication
* Dashboard Analytics
* Report Generation
* Data Export
---
## Technologies Used
Examples:
* PHP
* MySQL
* Bootstrap
* JavaScript
* React
* Flutter
* Python
---
## Installation Guide
Provide clear setup instructions.
Example:
1. Clone the repository.
2. Import the database.
3. Configure environment settings.
4. Run the application.
---
## Screenshots (Required for Parsing)
Include screenshots of important system pages under the exact `### Screenshots` heading. Use standard Markdown image syntax.
```markdown
### Screenshots
![Login Page](screenshots/login.png)
![Dashboard](screenshots/dashboard.png)
```
Recommended screenshots:
* Login Page
* Dashboard
* Main Features
* Reports
* Mobile Interface (if applicable)
---
## Live Demo
Provide a deployment link if available.
---
## Video Demonstration (Required for Parsing)
Provide a direct video demonstration link if available under the exact `### Video Demonstration` heading.
```markdown
### Video Demonstration
https://youtube.com/watch?v=your-video-link
```
---
## Future Improvements
List possible future enhancements.
---
# GitHub Topics
All repositories should include GitHub topics so they can be filtered properly on the showcase website.
## Subject Topics (Required)
Choose at least one:
* `wst`
* `sia`
## Category Topics
Choose one or more:
* `web-development`, `mobile-development`, `desktop-application`, `ai`, `machine-learning`, `cybersecurity`, `game-development`, `iot`, `research-project`
## Technology Topics
Examples:
* `php`, `mysql`, `laravel`, `react`, `nextjs`, `flutter`, `firebase`, `java`, `python`, `csharp`, `unity`, `godot`
---
# Repository Submission Checklist
Before submitting a repository, verify the following:
- [ ] Repository name follows standards
- [ ] Repository visibility is set to **Public**
- [ ] `README.md` completed with exact headings (`### Members`, `### Screenshots`)
- [ ] Project description provided
- [ ] Features listed
- [ ] Installation guide included
- [ ] Screenshots included
- [ ] Members listed as bullet points
- [ ] Subject listed
- [ ] Academic year listed
- [ ] GitHub topics added (`wst` or `sia`)
Repositories meeting these requirements may be featured in the PSU-CS-Academic-Projects showcase website.
---
# Showcase Website Integration
Repositories that follow these standards can be automatically displayed on the [PSU-CS-Academic-Projects website](https://psu-cs-academic-projects.github.io).
The website's automation script will retrieve:
* Repository Name & Description
* GitHub Topics (Subject, Category, Technologies)
* Screenshots (from `### Screenshots`)
* Members (from `### Members`)
* Video Demonstration Link (from `### Video Demonstration`)
directly from GitHub to provide a beautifully formatted, searchable project archive for future students.
