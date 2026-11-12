# Meet the Squad

**Naming mode:** Descriptive

| Name | Role | Specialty | How to talk |
|------|------|-----------|-------------|
| Lead | Lead | Scope and coordination | Label `squad:lead` |
| Docs | Docs | Basic versus full defaults explanations | Label `squad:docs` |
| Observability | Observability | OpenTelemetry, optional OTLP export, Development-only health endpoints | Label `squad:observability` |
| QA | QA | Source accuracy and acceptance checks | Label `squad:qa` |

## How to Work With Your Squad

Assign a specialist with a `squad:{member}` label (color `9B8FCC`) using the exact names above; the bare `squad` label is only a tracking marker. Routing lives in `.squad/routing.md`. Iterate with documented `/squad` commands.

## What Happened Here

The repo is a .NET eShop reference app. The brief asked for a documentation team for `src/eShop.ServiceDefaults` and `README.md`, so the team is Lead, Docs, Observability, and QA. Routing only; no application changes.

_Cast on 2026-11-12._
