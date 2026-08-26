<div align="center">

# Project Alpha Tech

**The technical core — agent coordination, stack tools, shared libraries, and the systems that build systems.**

[Agent OS](packages/agent-os) · [Stack](packages/stack) · [Tools](packages/tools) · [Shared](packages/shared)

</div>

---

## What is this?

A **monorepo** containing everything we build and reuse:

| Package | What | Why |
|---|---|---|
| **agent-os** | Multi-agent coordination — structured delegation, verification gates, memory | How we build software at scale |
| **stack** | Next.js + Cloudflare + D1 boilerplate | What we wish existed when we started |
| **tools** | Dispatch engine, PDF generator, WhatsApp notifier, GPS clustering | The actual systems we've built |
| **shared** | UI components, hooks, utilities, types | Code we reuse across every project |

---

## The philosophy

**Every piece of code here is:**
- ✅ **Used in production** — not demos, not tutorials
- ✅ **Battle-tested** — runs real systems for real clients
- ✅ **Shared** — built once, used everywhere
- ✅ **Verified** — every agent claim backed by evidence

---

## Quick Start

```bash
# Clone
git clone git@github.com:projectalphatech/monorepo.git

# Install
pnpm install

# Run anything
pnpm dev --filter agent-os
pnpm dev --filter stack
pnpm build --filter tools
```

---

## Stack

```
Runtime:      Cloudflare Workers (edge)
Frontend:     Next.js 15 · React · TypeScript · Tailwind CSS
Backend:      D1 (SQLite) · Cloudflare APIs
Integrations: WhatsApp · Meta Ads · Google Search Console · Email
Tools:        Playwright · Figma · Git · GitHub Actions
Agents:       Researcher · Builder · Commercial · Orchestrator
```

---

## License

MIT © [Project Alpha Tech](https://projectalpha.tech)

---

## Ecosystem

All our open-source work:

- [agent-os](https://github.com/projectalphatech/agent-os) — multi-agent coordination
- [structured-delegation](https://github.com/projectalphatech/structured-delegation) — delegation patterns
- [arabic-edge-pdf](https://github.com/projectalphatech/arabic-edge-pdf) — Arabic PDF at edge
- [gps-cluster-engine](https://github.com/projectalphatech/gps-cluster-engine) — GPS clustering
- [nextjs-cloudflare-deploy](https://github.com/projectalphatech/nextjs-cloudflare-deploy) — deployment guide

---

## Contributing

This is our internal monorepo, but PRs with real improvements are welcome. Read the agent-os patterns first — they explain how we work.

</div>