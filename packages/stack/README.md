# Stack

Next.js 15 + Cloudflare Workers + D1 boilerplate.

## What's included

- Next.js 15 with App Router
- Cloudflare Workers via `@opennextjs/cloudflare`
- D1 database with Drizzle ORM
- next-intl for i18n (EN/AR)
- Tailwind CSS v4
- Authentication via Auth.js
- TypeScript strict mode

## Structure

```
stack/
├── src/
│   ├── app/           # Next.js pages and layouts
│   ├── components/    # Shared UI components
│   ├── lib/           # Utilities, hooks, types
│   └── db/            # Database schema and migrations
├── wrangler.jsonc     # Cloudflare Workers config
├── next.config.ts     # Next.js config
├── drizzle.config.ts  # Drizzle ORM config
└── package.json
```

## Quick Start

```bash
# Install
pnpm install

# Run locally
pnpm dev

# Deploy to Cloudflare
pnpm deploy
```

## References

Based on the production setup powering [Sharm Trips](https://sharm-trips.adhamelsharkawy996.workers.dev) and [Project Alpha Tech](https://projectalpha.tech).
