# On-boarding Tracker

## Problem Statement

New hires move through tasks owned by three different teams — IT, HR and  
Facilities — with no single place that shows what is done, what is pending,  
and what has slipped. Today that coordination happens over email and memory,  
so overdue tasks (a laptop not provisioned, a badge not issued) surface only  
when the new hire shows up without what they need. I am typing something 

## Solution

A shared onboarding tracker where HR builds each new hire's checklist from a
role-based template, IT, HR and Facilities staff work through their own
assigned tasks, and the system sends reminders — and escalates — when a task
runs overdue, so nothing is missed on day one.

## Actors

- **HR Coordinator** — adds new hires, builds their checklist from a
role-based template (and customizes it), assigns tasks across IT, HR and
Facilities, monitors overall progress, and receives escalations for overdue
items.
- **IT Staff** — completes the IT tasks assigned to them for each new hire
(equipment, accounts, access).
- **Facilities Staff** — completes the facilities tasks assigned to them for
each new hire (workspace, badge, parking).
- **Hiring Manager** — views their own new hire's onboarding progress.

## Features

- F1 [Onboarding Checklists](features/F1-onboarding-checklists.md)
- F2 [Task Completion](features/F2-task-completion.md)
- F3 [Reminders &amp; Escalation](features/F3-reminders-escalation.md)

## Product-wide

See [Product-wide](product-wide.md) for sign-in and notification rules that
apply across all three features.

## Out of Scope

- Importing or syncing new-hire records from an external HR system (HRIS) —
new hires are entered manually. *assumed*
- Payroll processing or benefits enrollment.
- A mobile app.

## Open Questions

&lt;!-- none open at this time --&gt;