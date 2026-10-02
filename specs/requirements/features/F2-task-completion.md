# Task Completion

## Purpose

Let IT Staff, Facilities Staff and the HR Coordinator see the tasks assigned
to them for each new hire and mark their own tasks complete, and let the
Hiring Manager see their new hire's overall progress.

Needs: F1.

## User Stories

- F2.1 As an IT Staff member, I see a queue of every IT task across new hires, soonest due date first.
- F2.2 As a Facilities Staff member, I see a queue of every Facilities task across new hires, soonest due date first.
- F2.3 As an IT Staff member or a Facilities Staff member, I mark a task in my queue complete.
- F2.4 As an HR Coordinator, I see a queue of every HR task across new hires, soonest due date first, and mark my own tasks complete.
- F2.5 As a Hiring Manager, I see the full checklist and the status of every task for my new hire.

## Decisions

- Each department's queue (IT, HR, Facilities) lists tasks across every new hire it owns, sorted soonest due date first.
- Marking a task complete is a single action; no note or evidence is captured.
- The Hiring Manager sees the same task-level checklist detail as HR, read-only, limited to their own new hire.

