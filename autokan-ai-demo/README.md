# Autokan AI — SalesBoard demo

An interactive demo of the Autokan AI sales CRM by [Bizwira Digital](https://bizwira.com).

**Open the demo:** https://9keen.github.io/project-showcase/autokan-ai-demo/

All companies, people, phone numbers and amounts are fictional. The demo tenant is
"Teras Niaga Sdn Bhd", an invented POS reseller with 12 made-up Malaysian SME customers.

## What you can try

- **Dashboard**: open pipeline, deals won, overdue follow-ups, open tickets, pipeline by stage
- **Pipeline**: drag cards between stages (Lead → Qualified → Proposal → Negotiation → Won / Lost)
- **Cases, Follow-ups, Customers, Delivery, Support**: sortable, searchable tables; create and edit cases, add and complete follow-ups, update delivery and ticket status
- **Team and Activity log**: per-person workload and a full audit trail of every change
- **Viewing as**: switch between sales manager, team lead and sales rep to see role-based visibility
- **AI morning briefing**: a WhatsApp-style daily briefing (simulated in the browser from the demo data)

## How it works

A single self-contained `index.html`: no build step, no server, no external data.
Changes are saved in your browser only; **Reset demo** restores the sample data.
Dates are generated relative to today (Malaysia time), so the demo always looks current.
