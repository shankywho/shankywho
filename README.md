<h1 align="center">Hey <img src="https://raw.githubusercontent.com/SP-XD/SP-XD/refs/heads/main/images/Developer.gif" height="30" width="30"> I'm Shankar</h1>

<img src="https://i.pinimg.com/originals/42/b4/22/42b4229a9ec3145edaa895b2415dd720.gif" alt="Pixel-art developer desk banner" width="100%" />

<p align="center">Backend developer · B.Tech CSE at Amity University Gurugram (2028)</p>

## About

- I mostly write backend code in TypeScript, Go and Python, working on queues, databases and the APIs in front of them.
- I did backend internships at Axevron Digital Solutions (2026) and Atomic Media (2025).
- I contribute to [agent-orchestrator](https://github.com/OrchestratorInc/agent-orchestrator) (Go, TypeScript).
- I have 5 hackathon wins and 10 finalist places, and I've solved 500+ DSA problems in C++.

## Projects

**[Cognify](https://github.com/shankywho/COGNIFY)** · [live](https://cognify-one-ivory.vercel.app)<br>
A multi-tenant SaaS for AI workflows. You build a workflow as a DAG, and BullMQ runs it step by step. A failed run resumes from the step that failed. Search is hybrid: pgvector and Postgres full-text results merged with Reciprocal Rank Fusion. It took 100k-vector search from 420 ms to 4.2 ms.<br>
<sub>Node.js · TypeScript · PostgreSQL · pgvector · BullMQ · Redis · React</sub>

**[ROPUS](https://github.com/shankywho/ropus)**<br>
A payment risk engine. A Go service receives Razorpay webhooks and scores each payment with an XGBoost model (served via ONNX) plus fixed rules. It returns ALLOW, STEP UP, REVIEW or DECLINE. If the model is down, it falls back to rules only and stays within an 8 ms budget.<br>
<sub>Go · Python · FastAPI · XGBoost · ONNX · Docker</sub>

**[HawaCommand](https://github.com/shankywho/HawaCommand)**<br>
Air-quality monitoring for Delhi. It maps pollution at 500 m resolution, forecasts 72 h ahead, and dispatches anti-smog vehicles. I led a team of 4. The backend is FastAPI with WebSockets and uses Redis GEO for live vehicle tracking. It runs on AWS and has 135 tests.<br>
<sub>Python · FastAPI · LightGBM · Redis · AWS</sub>

**[HireLens](https://github.com/shankywho/HireLens)** · [live](https://hire-lenss.vercel.app/)<br>
Placed #2 of 648 projects at the Scrape-Verse International Hackathon 2026 (WeMakeDevs).

**[RetainGraph](https://github.com/shankywho/RetainGraph)** · [live](https://retain-graph.vercel.app)<br>
Builds a knowledge graph for each customer account from emails, call transcripts and support tickets, so customer success managers can query the full history. Built on Cognee.<br>
<sub>TypeScript · Prisma · Cognee</sub>

## Open source

Merged PRs in [OrchestratorInc/agent-orchestrator](https://github.com/OrchestratorInc/agent-orchestrator):
- [#5343](https://github.com/OrchestratorInc/agent-orchestrator/pull/5343) Added `/compact` chat compaction for Claude Code and ACP providers
- [#5641](https://github.com/OrchestratorInc/agent-orchestrator/pull/5641) Stopped sessions being terminated after a PR merge while the agent is still working
- [#5143](https://github.com/OrchestratorInc/agent-orchestrator/pull/5143) Switched to the last active session when the active one is deleted

## Tech

**Languages** <br><img src="https://skillicons.dev/icons?i=go,ts,js,py,cpp" alt="Go, TypeScript, JavaScript, Python, C++" />

**Backend & data** <br><img src="https://skillicons.dev/icons?i=nodejs,express,fastapi,postgres,mongodb,redis" alt="Node.js, Express, FastAPI, PostgreSQL, MongoDB, Redis" />

**Infra & frontend** <br><img src="https://skillicons.dev/icons?i=aws,docker,githubactions,prometheus,grafana,react,nextjs,tailwind" alt="AWS, Docker, GitHub Actions, Prometheus, Grafana, React, Next.js, Tailwind CSS" />

## Stats

<p align="center">
  <img src="https://www.gitskins.com/api/section/stats?username=shankywho&theme=github-dark&mode=dark" alt="shankywho's GitHub stats" width="49%" />
  <img src="https://streak-stats.demolab.com/?user=shankywho&theme=nightowl&hide_border=true&cache_seconds=86400" alt="shankywho's GitHub streak" width="49%" />
</p>

## Contact

[Website](https://shankarr.vercel.app) · [LinkedIn](https://www.linkedin.com/in/shankar70) · [Email](mailto:work.shankar70@gmail.com)

<p align="center"><sub>Template: <a href="https://www.gitskins.com/readme-generator?template=community-creative-dev-rt3x">creative dev</a> by <a href="https://www.gitskins.com/creators/himanshu201031">@himanshu201031</a> · <a href="https://www.gitskins.com/readme-generator">GitSkins</a></sub></p>
