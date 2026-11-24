# Quóc Nam Tràn

**Fullstack developer with a frontend focus.** I build web applications with React, Angular and TypeScript, write the APIs behind them in Python/Django and Node.js, and deploy them on my own server.

Open to roles in Saxony, Berlin or remote within Germany.

[Portfolio](https://quocnamtran.com/en) · [LinkedIn](https://www.linkedin.com/in/tranqn/) · [Email](mailto:tran.qn@protonmail.com)

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
