# Assignment: Kanban Board Creation in Jira
Please complete this after lab 5

## Objective
The purpose of this assignment is to familiarize you with creating, configuring, and managing Kanban boards in Jira. You will build a Kanban board from a given use-case workflow.

## Background
A software development team is working on a project called "Project Phoenix". The team follows an agile development methodology and is transitioning from Scrum to Kanban. You need to create a Kanban board for them in Jira based on their project workflow.

## Use Case Workflow:
1. **Backlog:** All newly created issues start here. 
2. **Analysis:** The team analyzes the issue, identifying requirements and necessary tasks.
3. **In Progress:** Work on the issue begins.
4. **Code Review:** Developers review the completed work for quality and adherence to standards.
5. **Testing:** The QA team tests the issue for bugs or other problems.
6. **Done:** The issue is resolved, tested, and ready for deployment.

## Assignment:

1. Login to your Jira account and navigate to your project, "Project Phoenix".
2. Click on "Create Board" and select "Create a Kanban board".
3. Name your board "Phoenix Kanban" and ensure it's connected to your project.
4. Go to the "Columns" section in your board settings. Here you'll create new columns representing each state of your workflow.
5. Create the following columns corresponding to the workflow states: "Backlog", "Analysis", "In Progress", "Code Review", "Testing", "Done". Ensure that they are in this exact order.
6. Go to the "Workflow" section in your board settings. Map each column to the corresponding status. Note: You might need to edit the workflow scheme if the existing workflow statuses do not match your columns. You can do this by going to Project settings -> Workflows.
7. Once your workflow is set, create a few dummy issues/tasks in the project and transition them through the workflow stages to ensure everything is working correctly.
8. Customize your board by adding WIP (Work In Progress) limits to your columns. This is a critical part of Kanban that helps prevent overloading your team.
9. Lastly, experiment with filters and quick filters to manage what issues appear on the board.


