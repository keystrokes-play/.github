# keystrokes.play

> Practice touch typing with real, famous open-source code.

Type SQL queries, Python functions, Go routines, and Rust snippets from projects
like Redis, CPython, and the Go standard library — character by character.

## Why keystrokes.play?

Most typing practice tools use random words or generic sentences. keystrokes.play uses
**real production code** from famous open-source projects. You practise the exact
patterns you type every day at work: function signatures, SQL schemas, control flow.

## Repositories

| Repo | Description | Phase |
|------|-------------|-------|
| [app](../app) | Main Next.js 14 typing portal | 0 |
| [typing-engine](../typing-engine) | Core npm package — WPM, replay, chapter splitter | 1 |
| [api](../api) | Platform API — Fastify + Postgres + WebSocket | 1 |
| [auth-service](../auth-service) | JWT, OAuth (GitHub/Google), enterprise SAML SSO | 1 |
| [billing-service](../billing-service) | Stripe subscriptions and plan enforcement | 2 |
| [analytics-service](../analytics-service) | WPM trends, keystrokes heatmaps | 2 |
| [enterprise-portal](../enterprise-portal) | Team management, SSO config, audit log | 3 |
| [marketing-site](../marketing-site) | Landing page, pricing, blog | 0 |
| [docs](../docs) | Mintlify documentation site | 1 |
| [ui-kit](../ui-kit) | Shared React component library + Storybook | 2 |
| [sdk](../sdk) | Public JS/TS client for the platform API | 1 |
| [ci-templates](../ci-templates) | Reusable GitHub Actions workflows | 1 |
| [infra](../infra) | Terraform + Pulumi infrastructure as code | 2 |
| [monitoring](../monitoring) | Grafana dashboards, Prometheus alerts | 2 |

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Web app | Next.js 14, TypeScript, Tailwind CSS, Framer Motion |
| API | Fastify 4, Drizzle ORM, PostgreSQL, Redis |
| Auth | JWT, OAuth 2.0 (PKCE), SAML 2.0 |
| Packages | tsup, Vitest, Changesets |
| Infra | Terraform, AWS App Runner, Cloudflare |
| Payments | Stripe |

## Phase Map

```
Phase 0 — Launch    .github  app  marketing-site  roadmap
Phase 1 — Growth    typing-engine  api  auth-service  docs  sdk  ci-templates
Phase 2 — Monetise  billing-service  analytics-service  ui-kit  infra  monitoring
Phase 3 — Enterprise  enterprise-portal  white-label  compliance  lms-integrations
Phase 4 — Future    browser-extension  mobile  on-prem-deploy
```

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md). All contributions welcome — especially
new code snippets! Use the [Snippet Request](.github/ISSUE_TEMPLATE/snippet_request.yml)
issue template.

## Community

- [GitHub Discussions](https://github.com/keystrokes-play/app/discussions) — Q&A and ideas
- [Roadmap](https://github.com/keystrokes-play/roadmap/issues) — public product roadmap
- [Discord](#) — coming soon

## Licence

MIT — see [LICENSE](LICENSE)
