<div align="center">

# Glib Miklushys

**Full-stack engineer** · Canada  
I design and ship production systems — Django products with real billing and users, TypeScript clients, and the marketing sites that sit in front of them.

[gm-webdev.com](https://gm-webdev.com) · [GitHub](https://github.com/glibmiklushys)

</div>

---

## Now

- Building **DasHub** — a talent and company platform: jobs, campaigns, certifications, messaging, and subscriptions on Django + PostgreSQL.
- Taking selected website work through [GM Web Dev](https://gm-webdev.com) — local businesses that need a fast, conversion-focused site, not a template.

## Selected work

| Project | Role | What it actually is |
| --- | --- | --- |
| **[Tiny Realms](https://github.com/glibmiklushys/Tinyrealms)** · [play](https://glibmiklushys.github.io/Tinyrealms/) | Solo | 2D RTS on a **deterministic, command-driven sim** (TypeScript + Pixi.js). Fixed 30 Hz tick, seedable RNG, AI that emits the same `Command` type a player does. Built so lockstep multiplayer is a network swap, not a rewrite. |
| **[Raftsight](https://github.com/glibmiklushys/raftsight)** · [watch](https://glibmiklushys.github.io/raftsight/) | Solo | Raft consensus you can step: leader election, log matching, majority commit, partitions, crashes. Simulated time so the tests are deterministic. |
| **[Casksight](https://github.com/glibmiklushys/casksight)** · [watch](https://glibmiklushys.github.io/casksight/) | Solo | Bitcask log you can watch: put/overwrite/delete, index hints, then compact the wasted records. |
| **[Lumen](https://github.com/glibmiklushys/lumenlang)** | Solo | Small functional language: lexer → Hindley–Milner inference → bytecode stack VM. Polymorphic `id`, recursive `fib`, REPL with `:type`. |
| **[GrainQL](https://github.com/glibmiklushys/grainql)** | Solo | In-memory SQL engine: parser, catalog, planner, volcano executor. Joins, `GROUP BY`, aggregates, `ORDER BY`. |
| **[KeelDB](https://github.com/glibmiklushys/keeldb)** | Solo | Bitcask-style KV in C++20: append-only log, CRC records, crash replay, compaction. |
| **[Prow](https://github.com/glibmiklushys/prow)** | Solo | HTTP/1.1 static server in C11: sockets, thread pool, path-traversal checks. |
| **[Weft](https://github.com/glibmiklushys/weft)** | Solo | C++20 work-stealing runtime: workers steal tasks, `wait()` helps so recursive spawn cannot deadlock. |
| **DasHub / BePro** | Founder / engineer | Talent + company platform: jobs, campaigns, certifications, messaging, analytics, subscriptions. Django + PostgreSQL. Private product. |
| **Client sites** | Engineer | Conversion-focused marketing sites for local businesses (Kitchener–Waterloo trades). Quote funnels, mobile-first. |
| **[GM Web Dev](https://gm-webdev.com)** | Owner | Intake and positioning for web work. |

## How I work

I care about systems that stay correct after they ship: clear domain models, migrations you can trust, payments that don’t leak state, and UIs that a stranger can use without a tour.

Typical shape of a project I own end-to-end:

```
product spec → data model → Django apps → payments / auth
                              ↓
                     TypeScript / HTML client
                              ↓
                     deploy, measure, iterate
```

## Stack

**Backend** — Python, Django, PostgreSQL, Redis, Gunicorn, Docker  
**Systems** — C, C++20, TypeScript VMs and query engines  
**Frontend** — TypeScript, JavaScript, HTML/CSS, Vite, Pixi.js  
**Product** — subscriptions, checkout, admin/ops, analytics, SEO-ready sites  
**Ops** — Git, Linux, Nginx, CI-friendly deploys

```python
# the kind of problem I like
# one source of truth, explicit commands, no hidden side effects
state' = tick(state, commands)
```

## Contact

- Web: [gm-webdev.com](https://gm-webdev.com)
- GitHub: [glibmiklushys](https://github.com/glibmiklushys)
- Location: Canada (Kitchener–Waterloo)

If you want a product built properly — or a site that is supposed to get the phone to ring — write through the site.
