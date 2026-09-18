# XPM Client Portal concept

A two-screen concept for the XPM Client Portal, built to XPM Design System v1.0.0 for an Upwork
application on 2026-09-18.

Five working screens, all in one file:

- `#home`: the client dashboard.
- `#performance`: spend, leads and cost per lead by channel, for the quarter or the last 30 days.
- `#projects`: projects filtered by status, with milestones for the selected project.
- `#approvals`: approve an item or send it back with a note. Home, the counts and the project status update to match.
- `#reports`: each report downloads as a CSV file.

Decisions are kept in this browser only. "Reset demo" in the footer starts over.

The client, the people and the numbers are sample data. The page passes XPM's
`check_xpm_design.py` and was reviewed against its anti-slop checklist.

To view it locally, run `python3 -m http.server 8794` and open http://localhost:8794.
