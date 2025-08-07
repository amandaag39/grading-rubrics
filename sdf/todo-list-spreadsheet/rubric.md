# Todo List: Spreadsheet – Grading Rubric

**Assignment Link:**  
[Lesson: Database Architecture – Todo List](https://firstdraft.com/runs/92/lessons/543-database-architecture-todo-list)

**Reference App for Review:**  

- Target: [Task Tracking App](https://ujs-practice-1.matchthetarget.com/)
- Login: `alice@example.com`  
- Password: `appdev`

**Previous Passing Student Example:**

- [Grace Do's Spreadsheet](https://docs.google.com/spreadsheets/d/1hzBe_jCtTyk7GC6svfO8_8YRak7QkRREJ_6bGciyd2g/edit?gid=0#gid=0)

## Student Instructions Summary

- Identify the tables used in the app.
- Create a spreadsheet listing each table and its columns.
- Follow proper naming conventions and relational structure.

## Required Tables & Columns

### 1. Tasks Table (Required Columns)

- `id`
- `content` or `description` (something to that effect works)
- `status`
- `created_at`
- `updated_at`
- `user_id` (foreign key to users)

### 2. Users Table (Required Columns)

- `id`
- `email`
- `password`

## Grading Criteria

| Criteria | Points | Notes |
|---------|--------|-------|
| Includes exactly **2 main tables**: `tasks` and `users` | ✔️ | Extra tables allowed only if justified |
| **Tasks table** includes all 6 required columns | ✔️ | Field names can vary slightly if intent is clear |
| **Users table** includes all 3 required columns | ✔️ | Additional fields (e.g. timestamps) are acceptable |
| Schema reflects **relational structure** (`user_id` as FK in `tasks`) | ✔️ | Omission of this is a major error |

---

## Optional (Nice-to-Have)

These are not required but demonstrate deeper understanding:

- Timestamps in `users` table (`created_at`, `updated_at`)

## Scoring Suggestion

- **Full Points (2/2)**: All required tables and fields present, relational structure clear (shows relationship between user and tasks), follows naming conventions.
- **Partial Credit (1/2)**: Minor column naming issues, missing some columns, but core structure is intact.
- **No Credit (0/2)**: Missing required tables or fields, or schema structure is fundamentally incorrect.
