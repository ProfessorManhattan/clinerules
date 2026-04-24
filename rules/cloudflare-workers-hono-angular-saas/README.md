# Cloudflare Workers + Hono + Angular SaaS

Comprehensive rules for building full-stack SaaS applications on Cloudflare Workers.

## Stack

- **Backend**: CF Workers + Hono v4.12+ (typed RPC, middleware factory)
- **Frontend**: Angular 21 (zoneless, signals, standalone) + PrimeNG
- **Database**: D1 + Drizzle v1 (batch API, type-safe)
- **Auth**: Clerk Core 3 (JWT, webhook sync, RBAC)
- **Payments**: Stripe (versioned releases, webhook dedup)
- **Jobs**: Inngest v4 (durable steps, AI inference offload)
- **Testing**: Playwright (6 breakpoints) + Vitest (TDD)
- **Security**: OWASP 2025, CSP with Trusted Types, Turnstile

## Source

Extracted from [megabytespace/claude-skills](https://github.com/megabytespace/claude-skills) — 14-category skill system with 94 reference docs for autonomous SaaS building.

## License

Rutgers
