<div align="center">

# Irfana Dwi Fangga

Fullstack Developer, backend-first — Next.js · TypeScript · Prisma · Django · Spring Boot · Go

Bandar Lampung, Indonesia · Open to remote roles

<a href="https://irfana.web.id" target="_blank"><img src="https://img.shields.io/badge/irfana.web.id-Portfolio-5b8def?style=for-the-badge&logoColor=white" alt="Portfolio — irfana.web.id" /></a>

<a href="https://www.linkedin.com/in/irfanadwifangga" target="_blank"><img src="https://skillicons.dev/icons?i=linkedin" alt="LinkedIn" /></a>
<a href="mailto:irvanadwifangga@gmail.com" target="_blank"><img src="https://skillicons.dev/icons?i=gmail" alt="Gmail" /></a>

</div>

<br>

<div align="center">

I build the parts of a product most people never see — payment flows that can't double-charge, real-time bridges that can't drop a message, APIs that hold up under concurrent writes.

**Currently** — Freelance Fullstack Developer @ **Seria**, building a full digital ecosystem for a Minecraft server community (web, admin CMS, payment-integrated webstore, and a custom Java plugin bridging the game server in real time via RCON), and @ **GM Workspace**, an internal management platform for a YouTube content team (automated payroll, tiered bonus engine, Google Drive integration).

**Side project** — a local-first desktop audio converter in Go: a single binary serving an embedded React SPA, a SQLite-backed job queue with a bounded worker pool, live progress over SSE, and cross-platform releases via GoReleaser.

**Previously** — Backend Developer Intern @ PT. Rizq Sanjaya Teknologi, building the internal dashboard and REST API for **RSTPOS**, a multi-branch Point of Sale system (Django REST Framework + Next.js).

**Best Presentation** — Expo 2025, Politeknik Negeri Lampung, for a campus building-reservation system (Next.js, Redis/Upstash, Supabase Postgres).

**In progress** — BNSP competency certification, *Pemrogram Muda (Associate Programmer)* scheme.

</div>

<br>

<div align="center">

### Case studies

The actual problems and how they were solved — concurrency, idempotency, and protocol work. Full write-ups at **[irfana.web.id](https://irfana.web.id)**.

| | |
| --- | --- |
| **Payments that can't double-charge** | Signature verification, webhook idempotency, and ordering the entitlement grant after the state transition commits |
| **A real-time bridge to a game server** | A Java RCON client written against the packet protocol directly, rather than pulling in a heavier framework |
| **Inventory that survives concurrent branches** | `select_for_update()` inside an atomic transaction, with negative-quantity rejection before the write |
| **A payroll engine that can't pay twice** | Guarded `pending → paid` transitions, decoupled from asynchronous view-count syncing |
| **A checkout that can't be gamed from the client** | Eligibility rules moved server-side into one module shared by the storefront and checkout, so a cached cart can't carry a price the account isn't entitled to |

</div>

<br>

<table align="center">
  <tr>
    <td align="center"><b>Languages</b></td>
    <td align="center"><img src="https://skillicons.dev/icons?i=js,ts,py,java,php" alt="JavaScript, TypeScript, Python, Java, PHP" /></td>
  </tr>
  <tr>
    <td align="center"><b>Frontend</b></td>
    <td align="center"><img src="https://skillicons.dev/icons?i=nextjs,react,tailwind" alt="Next.js, React, Tailwind CSS" /></td>
  </tr>
  <tr>
    <td align="center"><b>Backend</b></td>
    <td align="center"><img src="https://skillicons.dev/icons?i=nodejs,django,spring,go,prisma" alt="Node.js, Django, Spring Boot, Go, Prisma" /></td>
  </tr>
  <tr>
    <td align="center"><b>Database</b></td>
    <td align="center"><img src="https://skillicons.dev/icons?i=postgres,supabase,redis,sqlite" alt="PostgreSQL, Supabase, Redis, SQLite" /></td>
  </tr>
  <tr>
    <td align="center"><b>Tools</b></td>
    <td align="center"><img src="https://skillicons.dev/icons?i=docker,git,github,vercel,aws,postman" alt="Docker, Git, GitHub, Vercel, AWS, Postman" /></td>
  </tr>
</table>

<br>

<div align="center">
  <img width="55%" src="https://streak-stats.demolab.com/?user=irfanadwifangga&theme=dark&hide_border=true" alt="GitHub streak" />
</div>
