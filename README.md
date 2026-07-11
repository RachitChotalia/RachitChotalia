<div align="center">

# Hi, I'm Rachit 👋

Final-year IT student @ Dwarkadas J. Sanghvi College of Engineering, Mumbai — building backend systems and looking for my first full-time SDE role.

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/rachit-chotalia)
[![LeetCode](https://img.shields.io/badge/-LeetCode-FFA116?style=flat&logo=leetcode&logoColor=white)](https://leetcode.com/u/chotaliarachit)
[![Email](https://img.shields.io/badge/-Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:chotaliarachit@gmail.com)

</div>

---

### About me

I like building things that stay up under load — APIs that don't fall over, caches that actually save you the DB hit, systems where the data stays consistent even when three things happen at once. Most of what I build ends up being backend-heavy: Java/Spring Boot on the server, React on the front when I need one, Postgres and Redis doing the real work underneath.

I spent a couple of months at Fincept writing Python connectors that pull real financial data into a fairly large open-source terminal project — that's where I actually got comfortable with production code that other people depend on, not just code that runs on my laptop.

Outside of engineering, I run design/creative direction for a few student orgs (TEDx DJSCE, the E-Cell), which mostly means I've gotten decent at making things look like they were built on purpose.

**Currently:** interviewing for SDE roles, and picking up whatever backend/systems topics fill the gaps — concurrency, caching strategies, and just writing cleaner APIs.

### Experience

**Python Intern — Fincept** *(Feb – Mar 2026, Remote)*
- Built and shipped Python connectors for financial data sources (FDIC, PxWeb, Bank of Japan) feeding real-time ingestion pipelines in the 25k+ star Fincept Terminal
- Built an LLM-powered tool that reads third-party API docs and generates working Python wrapper modules, cutting the time to onboard a new data source
- Cleaned up the DB interaction layer and ingestion workflows, closing out a class of data-consistency bugs

### Projects

**[Linklet](https://linklet-taupe.vercel.app/)** — `Java · Spring Boot · PostgreSQL · Redis`
A URL shortener that's really an excuse to do caching and load-testing properly. Layered MVC (controller/service/repo), Redis caching in front of Postgres cut query load by 32% under concurrent load, held up to 500 concurrent requests with zero dropped connections.

**[Finvista](https://fin-vista-nine.vercel.app/)** — `React · Node.js · MongoDB · Gemini API`
Full-stack retirement planning app with an AI layer for personalized suggestions. Redesigned the dashboard flow to cut manual planning steps by 25% in usability testing with 8 users.

**SpendWise** — `Java · Spring Boot · React · PostgreSQL · Redis`
An expense tracker built around a proper double-entry ledger in Postgres, because I wanted the numbers to actually reconcile. Uses Java virtual threads and Redis idempotency keys to keep concurrent transactions race-free, and tuned connection pooling/batch writes to cut commit latency vs. a naive JDBC setup.

### Skills

`Java` `Python` `C++` `JavaScript` — `Spring Boot` `React` `Node.js` `Express` `FastAPI` — `PostgreSQL` `MongoDB` `Redis` — `Git` `Docker` `AWS` `Postman`

### A few wins along the way

Second Prize, Nirmaan 2026 (DJ InIT.AI) · Finalist, NSE National Financial Quiz · Winner, Biz Quiz (IIC DJSCE) · Design Head, TEDx DJSCE

---

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=RachitChotalia&show_icons=true&theme=gruvbox&hide_border=true&bg_color=1d2021&title_color=fabd2f&text_color=ebdbb2&icon_color=fabd2f" height="165" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=RachitChotalia&layout=compact&theme=gruvbox&hide_border=true&bg_color=1d2021&title_color=fabd2f&text_color=ebdbb2&langs_count=8" height="165" />

<img src="https://github-readme-streak-stats.herokuapp.com?user=RachitChotalia&theme=gruvbox&hide_border=true&background=1d2021&currStreakLabel=fabd2f" height="165" />

</div>
