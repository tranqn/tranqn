<!-- HEADER -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=220&section=header&text=Qu%C3%B3c%20Nam%20Tr%C3%A0n&fontSize=48&fontAlignY=38&desc=Fullstack%20Developer%20%C2%B7%20Frontend%20Focus&descAlignY=60&descSize=18" />
</div>

<h3 align="center">Fullstack developer with a frontend focus. Based in Saxony, Germany 🇩🇪</h3>
<p align="center"><i>Open to roles in Saxony, Berlin or remote within Germany</i></p>

<p align="center">
  <a href="https://www.linkedin.com/in/tranqn/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white&style=flat-square" height="26" /></a>
  <a href="mailto:tran.qn@protonmail.com"><img src="https://img.shields.io/badge/Email-6D4AFF?logo=protonmail&logoColor=white&style=flat-square" height="26" /></a>
  <a href="https://quocnamtran.com/en"><img src="https://img.shields.io/badge/Portfolio-0F5E8C?logo=googlechrome&logoColor=white&style=flat-square" height="26" /></a>
</p>

<p align="center">
I build web applications with React, Angular and TypeScript,<br />
write the APIs behind them in Python/Django and Node.js, and deploy them on my own server.
</p>

---

### Tech stack

<div align="center">
  <img src="https://skillicons.dev/icons?i=ts,js,react,nextjs,angular,vue,html,css,tailwind,threejs&perline=10" />
  <br />
  <img src="https://skillicons.dev/icons?i=nodejs,python,django,postgres,redis,firebase,docker,githubactions,gitlab,vitest,git&perline=11" />
</div>

---

### Selected work

**[Zyklus](https://github.com/tranqn/zyklus)** · React · TypeScript · Hono · PWA
A mobile-first training app I built solo, from plan generator and nutrition tracking to the Hono API with accounts. It works offline and syncs between devices: conflicts are resolved per entry (newest change per field and per item, tombstones so deletions survive), and every device computes the same result from the same two inputs.
[Merge logic](https://github.com/tranqn/zyklus/blob/9582fd6fe3aed4cb97be0aa7efd02ce35084d0a0/src/sync/merge.ts) · [Merge tests](https://github.com/tranqn/zyklus/blob/9582fd6fe3aed4cb97be0aa7efd02ce35084d0a0/src/domain/__tests__/merge.test.ts#L7) · [Walkthrough](https://quocnamtran.com/media/projects/zyklus.mp4) · [Live app](https://mci.quocnamtran.com) (account required)

**[Praxis UI Lab](https://quocnamtran.com/en/projects/praxis-ui-lab)** · Angular · Signals · Playwright
A day list for a medical practice with synthetic data, fully usable by keyboard and command palette. The UI treats a conflict (`409`) and stale data (`412`) differently: both roll back visibly and are announced to screen readers, a `412` reloads the real server state, and a `409` keeps the entered reason so the second attempt needs no retyping.
[Case study](https://quocnamtran.com/en/projects/praxis-ui-lab) · [Trigger 409/412 in the demo](https://praxis-ui-lab.quocnamtran.com/einstellungen) · [Walkthrough](https://quocnamtran.com/media/projects/praxis-ui-lab.mp4)

**[Coderr](https://github.com/tranqn/coderr)** · Django REST · PostgreSQL · Docker
A Fiverr-style marketplace: I wrote the complete Django REST API and replaced the course frontend with my own. Orders store the agreed offer terms as an immutable snapshot, and the production stack (PostgreSQL, Gunicorn, Caddy) is sized for a small shared server, so the chat polls over HTTP instead of holding WebSockets open.
[Snapshot test](https://github.com/tranqn/coderr/blob/1823dfe6d0bf063cb7deacd15fe146f600b6c1c4/backend/order_app/tests.py#L75) · [Polling test](https://github.com/tranqn/coderr/blob/1823dfe6d0bf063cb7deacd15fe146f600b6c1c4/backend/message_app/tests.py#L48) · [Live demo](https://coderr.quocnamtran.com)

**[StadtPuls](https://quocnamtran.com/en/projects/stadtpuls)** · Node.js · Moleculer · Vue 3 · PostgreSQL · InfluxDB
An IoT platform for municipal utilities, built solo. LoRaWAN readings arrive over RabbitMQ, are validated, de-duplicated and decoded in an isolated driver runtime, stored in PostgreSQL (master data) and InfluxDB (readings), and shown in a tenant-scoped Vue dashboard; measurement time and arrival time stay separate, so late or duplicate uplinks never distort a time series.
[Walkthrough](https://quocnamtran.com/media/projects/stadtpuls.mp4) · [Code on GitLab](https://gitlab.com/nam.qt/stadtpuls) · [ADR: two data stores](https://gitlab.com/nam.qt/stadtpuls/-/blob/e5d8298fd2910c574e7d0f9374be7aeea062c11f/docs/adr/03-two-datastores.md) · [Test: measurement vs. arrival time](https://gitlab.com/nam.qt/stadtpuls/-/blob/e5d8298fd2910c574e7d0f9374be7aeea062c11f/packages/core/time.spec.ts)

More on GitHub: [Bookstore](https://github.com/tranqn/bookstore) (Angular SSR, accessibility checks in CI), [Pokédex Holo TCG](https://github.com/tranqn/pokedex-holo-tcg) (Next.js, Three.js, PWA), [Join](https://github.com/tranqn/join) (team project, Angular, Firebase).

---

### How I work

I write down the expected behaviour and acceptance criteria first, then let Claude Code and Codex implement and review each other within that scope. I approve the plan before any code exists and sign off only after checking the scenarios that matter myself, as in this [Praxis UI Lab example](https://quocnamtran.com/en#arbeitsweise).

---

<p align="center">
  <a href="https://www.linkedin.com/in/tranqn/">LinkedIn</a> &nbsp;·&nbsp;
  <a href="mailto:tran.qn@protonmail.com">Email</a> &nbsp;·&nbsp;
  <a href="https://quocnamtran.com/en">Portfolio</a>
  <br />
  <sub>Open to new ideas and the right team. Let's talk.</sub>
</p>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=120&section=footer" />
</div>
