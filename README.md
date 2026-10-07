# Hi, I'm Zero

Developer since 2021. I build Discord bots, websites and web apps, and I host and maintain them myself on my own Linux server. I'm currently expanding my portfolio into FiveM development.

Portfolio: [zerodevv.nl](https://zerodevv.nl)

## What I work with

**Discord bots**
- Python: discord.py (cogs/modules), aiohttp, sqlite3 / aiosqlite
- JavaScript / Node.js: discord.js v14, better-sqlite3

**Web**
- Next.js (App Router), React, TypeScript, Tailwind CSS, Vite
- FastAPI, Express
- NextAuth (Discord login), Stripe

**Databases**
- SQLite
- MySQL / MariaDB (via Prisma)
- PostgreSQL (Supabase, including Row Level Security)

**Server & hosting**
- Linux VPS, pm2, nginx as reverse proxy, Cloudflare
- Security headers (CSP, HSTS)
- Backups before every change

**How I work**
- Secrets live in `.env` files, never in code
- Configuration is kept separate from code
- Smoke tests for my bots

## Projects

### LostMC Club Bot
Discord bot for the FiveM roleplay club *The Lost MC*, running live.
The entire Discord server is defined in config files (server-as-code): roles and channels are linked from config, and the setup script never deletes anything. The bot tracks club operations: roster, prospect process, church, ride-outs, strikes, and a treasury that keeps clean and dirty money separate. The treasury stays in sync with the in-game bank through a webhook channel, and mistakes are fixed with correction entries instead of rewriting history. Includes a `doctor` command that checks config and permissions, and smoke tests that run without Discord.
`Node.js` `discord.js v14` `SQLite`

### [LostMC Pages](https://github.com/Z3R0999x/lostmc-pages)
Static site with the privacy policy and terms of service for the club.

### [zerodevv.nl](https://zerodevv.nl)
My personal portfolio, bilingual (Dutch / English), served behind Cloudflare with CSP and HSTS headers.
`Next.js 16` `TypeScript` `Tailwind CSS 4`

### Taleforge (in development)
Web app for AI-driven text roleplay, built in milestones.
`Next.js 16` `TypeScript` `Supabase (RLS)` `Anthropic API` `Vitest`

### MEOS (in development)
FiveM learning project: a police information system with an NUI and a database.

## Client work

I also build custom projects for clients. That code is private and owned by the clients, so it is not published here.

- **Kinsja**: large modular community bot, website and a Discord Activity (Treehouse Quiz)
- **Romz**: community bot and website with Discord login
- **Ashley**: a set of seven bots running together under one pm2 config
- **Upfluence**: modular bot with a role hub built on Discord Components V2

## Currently learning: FiveM development

- CfxLua 5.4, client-side and server-side scripting, Qbox
- Current project: MEOS (in development)
- Planned: a multi-stage heist script with server-side security

## Contact

- Website: [zerodevv.nl](https://zerodevv.nl)
- Discord: `z3r0999.`
