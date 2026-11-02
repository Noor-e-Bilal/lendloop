# LendLoop

Borrow what you need. Lend what you don't.

LendLoop is a neighborhood tool-lending board where neighbors list tools, request them for a date range, and approve or return loans. n8n handles request notifications and daily overdue reminders, with signed webhooks and idempotent write-backs.

## Status

Design phase. Implementation and setup instructions will land here as the build progresses.

- [Design document](docs/superpowers/specs/2026-11-02-lendloop-design.md)

## Stack

- Next.js (App Router) and TypeScript
- Clerk for authentication
- Convex for data and server-side authorization
- n8n via Docker Compose for workflow automation

## Planned deliverables

- Public, read-only tool list with no owner details
- Authenticated listing, borrowing, approval, and return flows
- Admin and user roles enforced in Convex functions
- Two signed n8n workflows plus an error workflow
- Local Docker setup, architecture notes, and a production write-up
