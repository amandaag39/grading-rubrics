# Feedback Templates – Todo List: Spreadsheet

Use these pre-written feedback snippets to save time and give consistent, student-friendly comments. Feel free to personalize as needed.

## Full Credit (All Requirements Met)

> Great job! You included both required tables (`tasks` and `users`) with all necessary columns. Your schema shows a strong understanding of database structure and relationships. Keep up the great work!

> This is a well-organized and complete submission. Your use of standard naming conventions and inclusion of timestamps reflects a solid understanding of how relational databases work.

---

## Minor Issues (Still Acceptable)

> Nice work overall! Just a heads up: the column name `title` is totally fine here, but conventionally it might be called `description` or `content`. No points off, just something to consider for clarity.

> Everything looks good! One small suggestion: while your `user` column in the `tasks` table gets the point across, it's best practice to name foreign keys as `user_id`. That helps clarify the relationship between tables.

> Strong submission! You included extra fields like `username` or `due_date`, which aren't required but are totally valid. Nice thinking about future scalability!

---

## Needs Revision

> I can see the effort you put in — thank you! One key thing to revise: statuses like “Not Started,” “In Progress,” etc. should be **values** inside a single `status` column in the `tasks` table, not separate tables. Try restructuring with one `tasks` table that includes a `status` column instead.

> You're on the right track, but the `users` table is missing. For this assignment, it's important to show how tasks are tied to users via a `user_id` field. Please add a `users` table with at least `id`, `email`, and `password`.

> Looks like your submission is close, but a few of the required fields (like `created_at`, `updated_at`, or `user_id`) are missing from the `tasks` table. These fields help support the app’s core functionality — try adding those in and resubmitting.

---

## Encouraging Resubmission

Don't forget to have them resubmit if they didn't acheive full points. Include something along the lines of these messages at the end of your comment:

> I appreciate the thought and effort here! With a few small structural changes (see above), your schema will be in great shape. Please revise and resubmit — I’d be happy to take another look.

> You're almost there! This exercise is meant to help you build strong mental models for database structure. Please revise and resubmit. Let me know if you'd like to talk through any parts of it — happy to help!

---

_Last updated: August 2025_
