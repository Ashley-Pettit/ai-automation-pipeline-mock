# AI & Automation Pipeline (mock)

A working mock of a council's AI and automation request pipeline. Every request starts Unassigned. Assigning a BA or coach moves it to business review automatically, where they understand the problem, coach on existing tools including Copilot, book AI champion training where appropriate, or draft a business case for Dev triage. Dev triage sends work to a lightweight Copilot Studio build or to consideration of an enterprise bespoke app.

**Everything here is invented.** The council, requests, people and dollar figures are made up for demonstration.

## Try it

Open the live page: https://ashley-pettit.github.io/ai-automation-pipeline-mock/

- **Executive** is the summary of the whole pipeline.
- **Opportunities** lists requests by stage, with list, board and map views. Open a ticket to assign it, mark a meeting, coaching or AI champion training as booked, draft a business case, or move it to its next stage. **Assigned to me** shows your own tickets, and "Viewing as" switches person.
- **Benefit register** tracks what delivered work has returned.

## Saving

Decisions save in your own browser only, so nobody else sees your changes. Use **Import and export > Reset demo data** to start again.

The page is one self-contained file, `index.html`.
