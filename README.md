<div align="center">

<!-- Typing animation -->
[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=700&size=28&pause=1000&color=6366F1&center=true&vCenter=true&width=700&lines=Hey+👋+I'm+Shivam+Thakur;MERN+%7C+Socket.io+%7C+AI+%26+Search+Systems;🚀+Building+real+products)](https://git.io/typing-svg)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=shivam22-source&color=6366f1&style=flat-square&label=Profile+Views)
[![GitHub followers](https://img.shields.io/github/followers/shivam22-source?style=flat-square&color=6366f1&label=Followers)](https://github.com/shivam22-source)

<br/><br/>

<a href="https://www.linkedin.com/in/shivam-thakur-715505251/">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
<a href="https://leetcode.com/u/Shivam1112/">
  <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black"/>
</a>
<a href="https://www.codechef.com/users/shi_vam_56">
  <img src="https://img.shields.io/badge/CodeChef-5B4638?style=for-the-badge&logo=codechef&logoColor=white"/>
</a>
<a href="https://www.instagram.com/_.shivam._.thakur.__/">
  <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"/>
</a>

</div>

---

## 🧑‍💻 About Me

```js
const shivam = {
  name:     "Shivam Thakur",
  location: "India 🇮🇳",
  stack:    ["React", "Node.js", "Express", "MongoDB", "Python", "FastAPI", "PostgreSQL"],
  extras:   ["Socket.io", "JWT Auth", "Gemini AI", "Cloudinary", "pgvector", "Hybrid Search (RRF)"],
  deploy:   ["Vercel", "Render", "MongoDB Atlas"],
  currently: "Building full-stack products with real users in mind",
  
};
```

---

## 🚀 Featured Projects

<div align="center">

| Project | What it does | Stack | Live |
|---------|-------------|-------|------|
| 🔍 **[WorkMesh](https://github.com/shivam22-source/WorkMesh)** | Permission-aware enterprise search & Q&A with verifiable citations (hybrid FTS + vector search, SQL-level ACLs) | FastAPI · PostgreSQL 16 · pgvector · Docker | [Run with Docker](https://github.com/shivam22-source/WorkMesh#readme) |
| ✈️ **[TripSync](https://github.com/shivam22-source/Trip-Sync)** | Group travel planner with realtime chat & expense splitting | MERN · Socket.io · Cloudinary | [Demo](https://trip-sync-smoky.vercel.app/) |
| 📒 **[Ledgerly](https://github.com/shivam22-source/Ledgerly)** | AI-powered finance ledger with Gemini insights | React · Node · MongoDB · Gemini | [Demo](https://ledgerly-navy.vercel.app/) |

</div>

---

## 🔍 Project Spotlight: WorkMesh

**Permission-aware enterprise knowledge search & Q&A with verifiable citations** — a single FastAPI service on PostgreSQL 16 + pgvector.

- **Hybrid search:** Postgres full-text (`tsvector`) + dense vectors (`all-MiniLM-L6-v2`, HNSW) fused with Reciprocal Rank Fusion
- **Pushdown access control:** document-level ACLs enforced *inside* SQL, so users never see content outside their groups (0 leaks across 500 adversarial queries)
- **Grounded answers:** citations linked to sources; declines to answer when evidence is missing or unauthorized
- **Production-minded:** signed JWT auth, audit logging, concurrency limiter with HTTP 503 backpressure, `/metrics` endpoint, 344 tests

| Result | Number |
|--------|--------|
| Recall@5 on harder 60-query eval (95% CI) | **74.2%** [62.5%, 84.2%] |
| Vector search latency after HNSW + ACL pushdown fix | ~3,920 ms → **~28 ms** |
| p95 latency at 15 concurrent users | **< 640 ms** |

> Measured on a synthetic 10,000-chunk corpus. The LLM answer step and the GitHub/Slack/Email connectors are intentionally mocked — the README documents exactly what is real vs. stubbed.

[📂 View repo](https://github.com/shivam22-source/WorkMesh)

---

## 🛠️ Tech Stack

<div align="center">

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socket.io&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Tailwind](https://img.shields.io/badge/Tailwind-38BDF8?style=for-the-badge&logo=tailwindcss&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=for-the-badge&logo=cloudinary&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

</div>

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=shivam22-source&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=6366f1&icon_color=6366f1&text_color=94a3b8" height="165"/>
&nbsp;&nbsp;
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=shivam22-source&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=6366f1&text_color=94a3b8" height="165"/>

</div>

<div align="center">

![GitHub Streak](https://streak-stats.demolab.com?user=shivam22-source&theme=tokyonight&hide_border=true&background=0D1117&ring=6366f1&fire=a855f7&currStreakLabel=6366f1)

</div>

---

## 🐍 Contribution Snake

<div align="center">

![Snake animation](https://raw.githubusercontent.com/shivam22-source/shivam22-source/output/github-contribution-grid-snake-dark.svg)

</div>



---

## 📈 Activity Graph

<div align="center">

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=shivam22-source&theme=tokyonight" height="165"/>
&nbsp;&nbsp;
<img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=shivam22-source&theme=tokyonight&utcOffset=5.5" height="165"/>

</div>
