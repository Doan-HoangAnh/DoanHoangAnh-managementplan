# PROJECT MANAGEMENT REPORT

**Project:** Student Internship Management System  
**Student:** Doan Hoang Anh

**Student Code:**22080003 
**Project Management Tool:** GitHub Projects  

## 1. Introduction

Project management is the process of planning, organizing, assigning, monitoring, and controlling project activities to achieve a specific objective. Effective project management helps a development team understand what must be completed, who is responsible for each activity, and how the project is progressing.

In software development, project management also helps the team manage requirements, features, defects, deadlines, and project risks. Without a clear management process, tasks may be forgotten, delayed, or completed without meeting user requirements.

## 2. Project Management Methods

### 2.1 Agile

Agile is an iterative approach to software development. Instead of developing the entire system in one long process, the team divides the project into smaller parts and improves the product continuously.

Agile allows the team to respond to requirement changes, collect feedback, and deliver useful features more frequently.

### 2.2 Scrum

Scrum organizes work into short development periods called Sprints. A Sprint usually lasts 1-2 weeks. Important Scrum roles include the Product Owner, Scrum Master, and Development Team.

### 2.3 Kanban

Kanban is a visual project management method. Tasks are displayed as cards and organized into columns according to their current status.

A basic Kanban workflow includes:

- To Do
- In Progress
- Done

The team moves a task from one column to another when its status changes. This makes project progress easy to understand.

## 3. Project Management Tools

Common project management tools include Jira, Trello, and GitHub Projects.

### 3.1 Jira

Jira provides advanced functions for managing Agile software projects, Sprints, backlogs, bugs, and reports. However, its interface and configuration may be complicated for a small student project.

### 3.2 Trello

Trello provides a simple visual Kanban board. It is easy to use but is not directly connected to source code and GitHub Issues.

### 3.3 GitHub Projects

GitHub Projects can manage Issues, tasks, features, and project progress directly with a GitHub repository. It supports table, board, and roadmap views.

GitHub Projects was selected for this assignment because it:

- Integrates directly with GitHub Issues.
- Supports the Kanban method.
- Records project changes.
- Allows tasks to be assigned to team members.
- Supports labels, status fields, filters, and roadmaps.

## 4. Sample Project Overview

### 4.1 Project Name

Student Internship Management System

### 4.2 Project Objective

The objective of this project is to develop a web-based system that helps students find internship opportunities, submit weekly internship reports, and receive feedback from their supervisors.

### 4.3 Target Users

- Students
- Internship supervisors
- University administrators

### 4.4 Project Management Method

The project uses the Kanban method with the following statuses:

- To Do
- In Progress
- Done

## 5. Requirements Analysis

### 5.1 Functional Requirements

| ID | Functional Requirement |
|---|---|
| FR-01 | The system must allow students to browse available internship opportunities. |
| FR-02 | The system must allow students to submit weekly internship reports. |
| FR-03 | The system must allow supervisors to review and comment on submitted reports. |

### 5.2 Non-Functional Requirements

| ID | Non-Functional Requirement |
|---|---|
| NFR-01 | The website must display correctly on desktop and mobile devices. |
| NFR-02 | Main pages should load within 2 seconds under normal operating conditions. |

## 6. User Stories and Acceptance Criteria

### 6.1 User Story 1: Browse Internship Opportunities

**User Story**

As a student, I want to browse available internship opportunities so that I can find a suitable company.

**Acceptance Criteria**

- The system displays a list of available internship opportunities.
- Each opportunity shows the company name, position, location, and application deadline.
- The student can open an opportunity to view its details.

### 6.2 User Story 2: Submit Weekly Internship Report

**User Story**

As a student, I want to submit my weekly internship report so that my supervisor can monitor my progress.

**Acceptance Criteria**

- The student can select the reporting week.
- The student can enter completed activities and difficulties.
- The system saves the submitted report.
- A confirmation message is displayed after submission.

### 6.3 User Story 3: Review Internship Report

**User Story**

As a supervisor, I want to review and comment on student reports so that I can provide feedback and evaluate progress.

**Acceptance Criteria**

- The supervisor can view submitted reports.
- The supervisor can enter feedback.
- The supervisor can mark a report as reviewed.
- The student can view the supervisor's feedback.

## 7. Kanban Board Plan

| Issue | Status | Reason |
|---|---|---|
| US-01 Browse internship opportunities | Done | The requirement and interface design have been completed. |
| US-02 Submit weekly internship report | In Progress | The report submission function is being developed. |
| US-03 Review internship report | To Do | Development has not started. |

The board contains at least one Issue in the In Progress column, as required by the tutorial.

## 8. Evaluation of the Med-AI Project Board Sample

The provided Med-AI project board is a project management dashboard that combines summary statistics, a Kanban board, risk notifications, and a Gantt timeline.

The sample contains:

- 34 total tasks.
- 18 tasks in To Do.
- 8 tasks in progress.
- 2 tasks under review.
- 6 completed tasks.
- 39% overall project progress.
- 26 scheduled tasks.
- 8 unscheduled tasks.
- Warnings about missing deadlines and delay risks.

### 8.1 Advantages

1. **Clear project overview**

The dashboard displays total tasks, tasks in progress, completed tasks, and overall progress. This allows users to understand the project status quickly.

2. **Effective Kanban visualization**

The tasks are divided into four clear stages: To Do, In Progress, Under Review, and Completed.

3. **Task progress tracking**

Tasks in progress display completion percentages and progress bars. This provides more information than a basic task status.

4. **Gantt timeline**

The timeline shows the planned duration of different tasks and supports daily, weekly, and monthly views.

5. **Risk notifications**

The assistant identifies tasks without deadlines and tasks that may be delayed. This helps the project manager take action before problems become serious.


### 8.2 Disadvantages

1. **Some tasks do not have schedules**

The sample shows 8 unscheduled tasks. Missing start dates and deadlines make it difficult to manage the complete project timeline.

2. **The overall progress calculation is unclear**

The dashboard shows 39% overall progress, but it does not explain how this value is calculated from completed and partially completed tasks.

3. **The Gantt chart is crowded**

The timeline contains many tasks. Some task names are shortened, and horizontal scrolling is required to view the complete schedule.

4. **Assignees are not clearly visible**

The Kanban cards shown in the sample do not clearly display the person responsible for each task.

5. **Task dependencies are not visible**

The Gantt chart displays task periods but does not clearly show which tasks depend on other tasks.

## 9. Comparison with GitHub Projects

| Criterion | Med-AI Sample | GitHub Projects |
|---|---|---|
| Project overview | Detailed custom dashboard | Customizable table, board, roadmap, and charts |
| Kanban board | Four project stages | Customizable status columns |
| Gantt planning | Detailed timeline | Roadmap with date fields |
| Task integration | Custom task system | Direct integration with Issues and Pull Requests |
| Source code integration | Not shown | Directly connected to repositories |
| Progress calculation | Available but not clearly explained | Can be managed using fields and charts |
| Collaboration | Not clearly demonstrated | Supports assignees, comments, labels, and project access |

The Med-AI sample provides a visually detailed dashboard, while GitHub Projects is more suitable for connecting project management activities with source code, Issues, and repository history.

## 10. Conclusion

Project management is important for defining requirements, organizing tasks, assigning responsibilities, and monitoring project progress. Agile and Kanban provide flexible methods for managing software development activities.

For the Student Internship Management System, GitHub Projects was selected because it integrates project tasks with GitHub Issues and provides a clear Kanban board. The sample project includes three Functional Requirements, two Non-Functional Requirements, three User Stories, and Acceptance Criteria.

The Med-AI sample has useful features such as summary statistics, risk warnings, progress indicators, and a Gantt chart. However, improvements are needed in scheduling completeness, task responsibility, dependency visualization, and terminology consistency.

## References

1. Session 02: PM Tools and Requirements.
2. Tutorial 02: PM Tools and Requirements.
3. GitHub Projects Documentation: https://docs.github.com/en/issues/planning-and-tracking-with-projects
4. Med-AI Project Board Sample: https://medai-project-board.vercel.app
