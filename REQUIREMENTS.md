# Requirements

## Scenario

You are building the frontend interface for a Client Project Tracker used by a digital agency.

Your goal is to create a clean, responsive UI that allows users to manage client projects.

No backend implementation is required. You will use the provided test_data.json as your data source.

---

## Project Model

Each project contains:

- ID
- Client Name
- Project Name
- Description
- Status
- Priority
- Start Date
- Due Date

---

## Required Features

### 1. Project List

Display all projects in a clean and organized layout.

Each project should show:

- Client Name
- Project Name
- Status
- Priority
- Due Date

---

### 2. Create Project

Allow users to create a new project.

---

### 3. Edit Project

Allow users to update existing project details.

---

### 4. Delete Project

Allow users to remove a project.

---

### 5. Form Validation

Implement validation for:

- Client Name (required)
- Project Name (required)
- Status (required and valid)
- Priority (required and valid)
- Start Date and Due Date (Due Date cannot be earlier than Start Date)

---

### 6. UI States

Handle:

- Loading state
- Empty state (no projects)
- Error state

---

## Technical Requirements

- You may use any frontend framework (React, Vue, Angular, Next.js, etc.)
- State management is up to you
- Styling approach is your choice

---

## Bonus (Optional)

- Search projects
- Filter by Status
- Filter by Priority
- Sorting
- Dashboard summary (counts of projects by status)
- Responsive mobile design
- Unit tests
