<div align="center">

<!-- Animated header -->
<a href="https://github.com/itsthatmay">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=26&duration=3500&pause=900&color=58A6FF&center=true&vCenter=true&width=560&lines=Full-stack+developer;Building+products+end+to+end;Web+%C2%B7+Mobile+%C2%B7+Infrastructure" alt="Typing SVG" />
</a>

<p>
  <img src="https://komarev.com/ghpvc/?username=itsthatmay&label=Profile%20views&color=58A6FF&style=flat" alt="profile views" />
</p>

</div>

---

### `whoami`

Full-stack developer focused on shipping real, production-grade products — not just prototypes.
I work across the whole stack: type-safe **TypeScript/Next.js** front and back ends, **Flutter**
mobile apps, **PostgreSQL** schema design, and the boring-but-important parts — reverse proxies,
backups, process managers and deployment pipelines on bare-metal Linux servers.

- 🧱 I care about clean data models, sane migrations, and not waking up to a broken prod.
- 📦 Comfortable owning a feature from DB column → API → UI → release build.
- 🐧 Self-host and operate my own infra (Caddy/Nginx, PM2, systemd, automated `pg_dump` → object storage).
- 🌱 Currently going deeper on mobile release engineering and observability.

---

### 🛠️ Tech Stack

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)

**Frameworks & Libraries**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Fastify](https://img.shields.io/badge/Fastify-000000?style=for-the-badge&logo=fastify&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![NextAuth.js](https://img.shields.io/badge/NextAuth.js-000000?style=for-the-badge&logo=auth0&logoColor=white)

**Data & Infrastructure**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Caddy](https://img.shields.io/badge/Caddy-1F88C0?style=for-the-badge&logo=caddy&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![PM2](https://img.shields.io/badge/PM2-2B037A?style=for-the-badge&logo=pm2&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)

**Tooling**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

---

### 📊 GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=itsthatmay&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&theme=tokyonight&title_color=58A6FF&icon_color=58A6FF" alt="GitHub stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=itsthatmay&layout=compact&hide_border=true&theme=tokyonight&title_color=58A6FF&langs_count=8" alt="Top languages" />

<img height="165" src="https://streak-stats.demolab.com?user=itsthatmay&hide_border=true&theme=tokyonight&ring=58A6FF&fire=58A6FF&currStreakLabel=58A6FF" alt="GitHub streak" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=itsthatmay&hide_border=true&theme=tokyo-night&color=58A6FF&line=58A6FF&point=ffffff&area=true" alt="Activity graph" width="95%" />

</div>

> Most of my work lives in private repositories, so public contribution counts don't tell the
> whole story — happy to walk through code and architecture on request.

---

### 🚀 Selected Work

**📖 Edda — social storytelling platform** · *private*
A Wattpad-style platform where readers and writers publish serialized stories. Next.js (App Router) +
Prisma + PostgreSQL with NextAuth (JWT) auth, role/moderation system, a Flutter companion app talking
to a dedicated mobile JWT API, and a daily encrypted backup pipeline (`pg_dump` → object storage).
Deployed on a self-managed Linux VPS behind a reverse proxy with PM2-supervised processes.

**🎮 ItemMarket — gaming items marketplace** · *private*
A marketplace for trading in-game items. Next.js 15 storefront, Fastify API, Prisma/PostgreSQL,
Redis for caching/sessions, scheduled background jobs, and a production deployment fronted by Caddy
with automatic TLS.

*Want a closer look? Reach out — I'm glad to share a walkthrough.*

---

### 📫 Get in touch

[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:andspavzk@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/itsthatmay)
<!-- Add your LinkedIn / portfolio / Twitter below when ready:
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/YOUR-HANDLE)
[![Website](https://img.shields.io/badge/Portfolio-0F172A?style=for-the-badge&logo=vercel&logoColor=white)](https://your-domain.com)
-->

<div align="center">
  <sub>Clean code, sane migrations, boring deploys. That's the goal.</sub>
</div>
