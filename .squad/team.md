# Squad Team — eShop

> .NET Aspire reference e-commerce application: microservices (Catalog, Basket, Ordering, Identity, Webhooks), a Blazor web app, a .NET MAUI client, RabbitMQ events, PostgreSQL and Redis.

## Coordinator

| Name | Role | Notes |
|------|------|-------|
| Squad | Coordinator | Routes work to the active specialists using `.squad/routing.md`. |

## Members

| Name | Role | Charter | Status |
|------|------|---------|--------|
| Lead | Tech Lead | `.squad/agents/lead/charter.md` | ✅ Active |
| Backend | Backend Services Engineer | `.squad/agents/backend/charter.md` | ✅ Active |
| Frontend | Frontend Engineer | `.squad/agents/frontend/charter.md` | ✅ Active |
| Platform | Platform and DevOps Engineer | `.squad/agents/platform/charter.md` | ✅ Active |
| Tester | Quality Engineer | `.squad/agents/tester/charter.md` | ✅ Active |

## Built-in Support Agents

Mandatory support agents with a fixed lifecycle role. They are not Cast specialists and not routing destinations.

| Name | Charter | Note |
|------|---------|------|
| Scribe | `.squad/agents/scribe/charter.md` | Silently merges accepted durable decisions only, never session or orchestration logs. |
| Ralph | `.squad/agents/ralph/charter.md` | Monitors the work queue on request. |
| Rai | `.squad/agents/rai/charter.md` | Reviews for responsible-AI and content-safety concerns. |
| Fact Checker | `.squad/agents/fact-checker/charter.md` | Verifies claims and offers Devil's-Advocate review. |

## Coding Agent

| Name | Role | Status |
|------|------|--------|
| @copilot | Coding Agent | 🤖 Coding Agent |

<!-- copilot-auto-assign: false -->

## Assignment

Use `squad:{member}` labels for specialist assignment, with the exact active names above (for example `squad:backend`); routing follows `.squad/routing.md`. The bare `squad` label is a tracking marker, not specialist assignment. A name mention alone does not dispatch a native workflow; use the documented `/squad` commands with their prerequisites.
