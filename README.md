<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=200&color=0:5b8def,100:1e293b&text=Irfana%20Dwi%20Fangga&fontColor=ffffff&fontSize=48&fontAlignY=38&desc=Backend%20Developer&descSize=20&descAlignY=60&animation=fadeIn" alt="Irfana Dwi Fangga - Backend Developer"/>

<a href="https://github.com/irfanadwifangga">
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3000&pause=1000&color=5B8DEF&center=true&vCenter=true&width=640&lines=Building+APIs+and+backend+systems;Payments%2C+webhooks%2C+and+data+consistency;Turning+manual+workflows+into+internal+tools;Fullstack+when+the+product+requires+it" alt="Typing animation"/>
</a>

<br/>

<a href="https://irfana.web.id"><img src="https://img.shields.io/badge/Portfolio-irfana.web.id-5b8def?style=for-the-badge&logo=googlechrome&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/irfanadwifangga"><img src="https://img.shields.io/badge/LinkedIn-Connect-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:irvanadwifangga@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-ea4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>

<br/><br/>

<img src="https://img.shields.io/badge/Location-Indonesia-red?style=flat-square"/>
<img src="https://img.shields.io/badge/Status-Open%20to%20remote%20work-2ea44f?style=flat-square"/>
<img src="https://komarev.com/ghpvc/?username=irfanadwifangga&label=Profile%20views&color=5b8def&style=flat-square" alt="Profile views"/>

<br/><br/>

## 👋 About Me

I'm a **backend-focused developer** who builds web applications, APIs, and internal systems.<br/>
Most of my recent work means shipping complete products, so I go fullstack when needed,<br/>
but backend engineering is where I want to be.

**What I care about**

🔌 **API design**: clean contracts, predictable behavior<br/>
🗄️ **Database architecture**: schemas that survive real traffic<br/>
⚙️ **Backend services**: reliable, observable, maintainable<br/>
🔗 **System integration**: payments, messaging, third-party services<br/>
🤖 **Workflow automation**: replacing manual busywork with software

<br/>

## 🚧 Currently Building

<table align="center">
<tr>
<td width="50%" valign="top" align="center">

### 🏢 Internal Platforms & Business Systems

Private projects built with:

Node.js + Express backend services<br/>
Next.js applications<br/>
MongoDB + Mongoose data modeling<br/>
PostgreSQL databases<br/>
Authentication & authorization<br/>
External service integrations

</td>
<td width="50%" valign="top" align="center">

### 📚 Developer Documentation

Documentation platforms built with:

Astro<br/>
Markdown-based content<br/>
Modern frontend tooling

</td>
</tr>
</table>

<br/>

## 🧠 Engineering Focus

<table align="center">
<tr><th align="left">Problem</th><th align="left">Approach</th></tr>
<tr><td>💳 Reliable payments</td><td>Webhook verification, idempotency handling, safe transaction flow</td></tr>
<tr><td>🔄 Concurrent data updates</td><td>Database transactions and consistency checks</td></tr>
<tr><td>📡 Real-time communication</td><td>Event-based integration between services</td></tr>
<tr><td>🤖 Business automation</td><td>Internal tools that reduce manual workflows</td></tr>
</table>

<details>
<summary><b>💡 Example: how I think about a payment webhook</b></summary>

<br/>

```mermaid
sequenceDiagram
    autonumber
    participant PG as Payment Gateway
    participant API as Backend API
    participant DB as Database
    participant Q as Event / Notification

    PG->>API: POST /webhook (signed payload)
    API->>API: Verify signature
    API->>DB: Check idempotency key
    alt Already processed
        API-->>PG: 200 OK (no-op)
    else New event
        API->>DB: BEGIN transaction
        API->>DB: Update order + payment status
        API->>DB: COMMIT
        API->>Q: Emit "order.paid"
        API-->>PG: 200 OK
    end
```

</details>

<br/>

## ⭐ Featured Project

<table align="center">
<tr>
<td width="55%" valign="middle" align="center">

### yt-to-mp3

A **local-first** media conversion application built with Go and React.

🐹 Go backend<br/>
⚛️ Embedded React interface<br/>
🗃️ SQLite-based job processing<br/>
👷 Worker pool architecture<br/>
📶 Real-time progress updates<br/>
📦 Cross-platform builds

<a href="https://github.com/irfanadwifangga/yt-to-mp3">View repository →</a>

</td>
<td width="45%" valign="middle" align="center">

<a href="https://github.com/irfanadwifangga/yt-to-mp3">
<picture>
<source media="(prefers-color-scheme: dark)" srcset="https://github-stats-extended.vercel.app/api/pin?username=irfanadwifangga&repo=yt-to-mp3&theme=dark_github_repocard&hide_border=true">
<img src="https://github-stats-extended.vercel.app/api/pin?username=irfanadwifangga&repo=yt-to-mp3&theme=light_github_repocard&hide_border=true" alt="yt-to-mp3 repo card"/>
</picture>
</a>

</td>
</tr>
</table>

<br/>

## 🛠️ Tech Stack

**Backend**<br/>
<img src="https://skillicons.dev/icons?i=nodejs,express,go,py,django" alt="Backend"/>

**Frontend**<br/>
<img src="https://skillicons.dev/icons?i=typescript,nextjs,react,astro,tailwind" alt="Frontend"/>

**Database**<br/>
<img src="https://skillicons.dev/icons?i=mongodb,postgres,redis,supabase,sqlite" alt="Database"/>

**Testing & CI/CD**<br/>
<img src="https://skillicons.dev/icons?i=vitest,githubactions" alt="Testing and CI/CD"/>

**Tools**<br/>
<img src="https://skillicons.dev/icons?i=docker,git,github,aws,vercel" alt="Tools"/>

<br/>

## 📊 GitHub Stats

<a href="https://github.com/irfanadwifangga">
<picture>
<source media="(prefers-color-scheme: dark)" srcset="https://github-stats-extended.vercel.app/api?username=irfanadwifangga&show_icons=true&include_all_commits=true&rank_icon=github&theme=dark_github&hide_border=true&show=prs_merged_percentage,prs_reviewed">
<img height="190" src="https://github-stats-extended.vercel.app/api?username=irfanadwifangga&show_icons=true&include_all_commits=true&rank_icon=github&theme=light_github&hide_border=true&show=prs_merged_percentage,prs_reviewed" alt="GitHub stats"/>
</picture>
</a>
<a href="https://github.com/irfanadwifangga">
<picture>
<source media="(prefers-color-scheme: dark)" srcset="https://github-stats-extended.vercel.app/api/top-langs?username=irfanadwifangga&layout=compact&langs_count=8&theme=dark_github&hide_border=true">
<img height="190" src="https://github-stats-extended.vercel.app/api/top-langs?username=irfanadwifangga&layout=compact&langs_count=8&theme=light_github&hide_border=true" alt="Top languages"/>
</picture>
</a>

<br/><br/>

<picture>
<source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com/?user=irfanadwifangga&theme=dark&hide_border=true">
<img width="60%" src="https://streak-stats.demolab.com/?user=irfanadwifangga&theme=default&hide_border=true" alt="Contribution streak"/>
</picture>

<br/>

## 🤝 Let's Work Together

I'm open to **remote backend and fullstack opportunities**.<br/>
If you have an API to design, a system to integrate, or a workflow worth automating, let's talk.

<a href="mailto:irvanadwifangga@gmail.com"><img src="https://img.shields.io/badge/Say%20hello-irvanadwifangga%40gmail.com-5b8def?style=for-the-badge&logo=gmail&logoColor=white"/></a>

<br/>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=100&color=0:5b8def,100:1e293b&section=footer" alt=""/>

</div>
