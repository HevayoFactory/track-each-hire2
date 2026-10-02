# Onboarding Checklists

## Purpose

Let the HR Coordinator add a new hire and build their onboarding checklist
from a role-based template, customized as needed, with tasks assigned across
IT, HR and Facilities.

## User Stories

- F1.1 As an HR Coordinator, I create a role-based checklist template listing the standard IT, HR and Facilities tasks for that role, each with a due-date offset from the start date (e.g. "day -3", "day 1").
- F1.2 As an HR Coordinator, I edit or retire an existing checklist template.
- F1.3 As an HR Coordinator, I add a new hire with their name, role and start date.
- F1.4 As an HR Coordinator, I build a new hire's checklist from the template matching their role, with each task's due date computed from the start date.
- F1.5 As an HR Coordinator, I add, remove or edit tasks on a specific hire's checklist after it is created from the template.
- F1.6 As an HR Coordinator, I see every new hire and the overall progress of their checklist.

## Decisions

- Checklist templates are role-based, and a hire's checklist can be customized after it is built from one.
- A task belongs to a department queue — IT, HR or Facilities — not a named individual; any staff member on that team can pick it up (see F2).
- Only the HR Coordinator creates and maintains templates; they are not editable by IT, Facilities or Hiring Managers.
- Each template task carries a due-date offset from the hire's start date; building a checklist from a template turns those offsets into real due dates.

## Out of Scope

- Assigning a task to a named individual instead of a department queue.

