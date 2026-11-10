# Meet the Squad

**Naming mode:** Descriptive

## The team

| Name | Role | Specialty | How to talk |
|------|------|-----------|-------------|
| Lead | Tech Lead | Architecture, triage, cross-service review | Label `squad:lead` |
| Backend | Backend Services Engineer | Catalog, Basket, Ordering, Identity, Webhooks APIs, EF Core, RabbitMQ events | Label `squad:backend` |
| Frontend | Frontend Engineer | Blazor web app, MAUI client, Blazor Hybrid | Label `squad:frontend` |
| Platform | Platform and DevOps Engineer | Aspire AppHost, ServiceDefaults, GitHub Actions, dependencies | Label `squad:platform` |
| Tester | Quality Engineer | Unit, functional and Playwright tests | Label `squad:tester` |

## How to work with your squad

- Create a label named `squad:{member}` (color `9B8FCC`) using an exact name above, such as `squad:backend`, and apply it to an issue to assign that specialist. Routing follows `.squad/routing.md`.
- The bare `squad` label is a tracking marker, not specialist assignment.
- A name mention alone does not dispatch a native workflow; use the documented `/squad` commands (`/squad research`, `/squad triage`, `/squad plan`, `/squad activate`) with their prerequisites.

## What happened here

The repository is the .NET Aspire eShop reference application: C# on .NET 10 with an Aspire AppHost (`src/eShop.AppHost`) orchestrating Catalog, Basket, Ordering, Identity and Webhooks services, background processors, a Blazor WebApp, a MAUI ClientApp, PostgreSQL, Redis and RabbitMQ. Tests live in `tests/` (MSTest) and `e2e/` (Playwright); CI runs in GitHub Actions. That shape suggested a Lead, two domain specialists (backend, frontend), a platform engineer and a quality engineer.

_Cast on 2026-11-10._
