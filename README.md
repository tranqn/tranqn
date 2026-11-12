<!-- HEADER -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=220&section=header&text=Quoc%20Nam%20Tran&fontSize=48&fontAlignY=38&desc=Fullstack%20Web%20Developer&descAlignY=60&descSize=18" />
</div>

<h3 align="center">Agents build. I review with a trained eye.<br />Fullstack developer working agentically with Claude Code and Codex. Based in Germany 🇩🇪</h3>
<p align="center"><i>Open to web developer roles for 2026</i></p>

<p align="center">
  <a href="https://www.linkedin.com/in/tranqn/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white&style=flat-square" height="26" /></a>
  <a href="mailto:tran.qn@protonmail.com"><img src="https://img.shields.io/badge/Email-6D4AFF?logo=protonmail&logoColor=white&style=flat-square" height="26" /></a>
  <a href="https://quocnamtran.com"><img src="https://img.shields.io/badge/Portfolio-000000?logo=vercel&logoColor=white&style=flat-square" height="26" /></a>
</p>

<p align="center">
I like working agentically: Claude Code and Codex take on analysis, implementation and tests.<br />
I set the goal and sign off every change. Intensive hands-on projects, from REST APIs to an IoT platform, trained the eye for it.
</p>

---

### Tech stack

<div align="center">
  <img src="https://skillicons.dev/icons?i=ts,react,nextjs,nodejs,angular,js,python,django,html,css&perline=10" />
  <br />
  <img src="https://skillicons.dev/icons?i=tailwind,postgresql,mongodb,firebase,docker,githubactions,threejs,git,github,vitest,vscode,figma&perline=12" />
</div>

- **Frontend:** React · Next.js · Angular · TypeScript · Tailwind CSS
- **Backend:** Django REST Framework · Node.js · Python · REST APIs (token auth)
- **Databases:** PostgreSQL · MongoDB · Firebase
- **DevOps:** Docker · Docker Compose · GitHub Actions CI · Nginx / Caddy
- **Testing:** Vitest · Playwright · pytest · accessibility (axe) · Lighthouse CI
- **AI in apps:** Google Gemini API · Hugging Face Transformers · embedding-based recommendations
- **Agentic workflow:** Claude Code · Codex · Claude Skills · spec-driven development · cross-agent review

---

### How I work

I like working agentically. The agents are fast; whether the result holds up is decided in the review afterwards, and that part stays with me.

- **Specify.** Goal, acceptance criteria and limits are written down before an agent starts.
- **Delegate.** Claude Code and Codex work in parallel and review each other. I write my own **Claude Skills** for the repetitive parts.
- **Review.** I read every change, test it in the browser and on small screens, and check accessibility.
- **Sign off.** I decide what ships.

**Where I look first:** roles and permissions, time zones, duplicate data and deployment. That is where software tends to break, even when an agent reports that everything is green.

---

### Selected work

A few projects worth a look, with live demos and source linked:

**[StadtPuls](https://stadtpuls.quocnamtran.com)** &nbsp;·&nbsp; [view code on GitLab](https://gitlab.com/nam.qt/stadtpuls)
An IoT platform for municipal utilities. LoRaWAN readings from water meters and sensors are validated, de-duplicated and decoded in an isolated driver runtime, then land in a dashboard with a site tree, a map and consumption charts. Each tenant only sees its own assets. Backed by 253 automated tests, 9 browser tests against the production bundle and a 15-job GitLab pipeline.
`Node.js` `Moleculer` `RabbitMQ` `Vue 3` `PostgreSQL` `InfluxDB` `Keycloak`

**[Praxis UI Lab](https://praxis-ui-lab.quocnamtran.com)**
A day list for a medical practice, built with synthetic patient data. Appointments move by click or keyboard from "planned" to "completed" through a framework-free state machine, and the UI reports conflicting edits (409) and stale data (412) separately. Playwright checks the flows and accessibility with axe.
`Angular 22` `Signals` `TypeScript` `MSW` `Playwright`

**[Coderr](https://coderr.quocnamtran.com)** &nbsp;·&nbsp; [view code](https://github.com/tranqn/coderr)
A service marketplace API: businesses publish offers, customers order and review them. Orders store the agreed terms as an immutable snapshot, and 88 automated tests cover the core API flows. The frontend was a course template.
`Django REST` `PostgreSQL` `Docker` `Caddy`

**[Videoflix](https://videoflix.quocnamtran.com)** &nbsp;·&nbsp; [view code](https://github.com/tranqn/videoflix)
A Netflix-style video streaming platform. Upload a video and a Redis-queued worker transcodes it into three HLS quality levels in the background, while the whole API sits behind JWT auth carried in HttpOnly cookies. Deployed in Docker behind Caddy.
`Django REST` `Redis / RQ` `FFmpeg` `Docker` `Caddy`

**[Quizly](https://quizly.quocnamtran.com)** &nbsp;·&nbsp; [view code](https://github.com/tranqn/quizly)
Turns any YouTube video into a 10-question quiz. The backend pulls the audio, transcribes it with Whisper, and hands the transcript to Gemini to generate the questions, all behind the same cookie-based JWT auth as Videoflix.
`Django REST` `Whisper` `Gemini` `Docker`

**[Bookstore](https://bookstore.quocnamtran.com)** &nbsp;·&nbsp; [view code](https://github.com/tranqn/bookstore)
A bilingual bookstore rendered on the server, with a Three.js wall of covers you can pan through. Ask it for a book by mood and it answers in three tiers: Gemini first, then an embedding model running locally on the server, then a keyword search, so a query never comes back empty. Accessibility and performance budgets run on every push.
`Angular 21` `SSR` `TypeScript` `Three.js` `Gemini` `Docker`

More projects, including Pokédex Holo TCG and the Join Kanban board, are on [my portfolio](https://quocnamtran.com).

---

### A bit about me

I'm Nam, a fullstack developer based in Germany. What I enjoy is turning a rough idea into something people can actually use. My own site, [quocnamtran.com](https://quocnamtran.com), is a good example: I built it in Angular 20, in both German and English, with the SEO and structure done from scratch. Off the keyboard, I'm usually on a volleyball court.

**What I'm doing now:**
- Building fullstack projects agentically with Claude Code and Codex, and reviewing every change myself
- Running my own deployments on Google Cloud: a Compute Engine VM with Docker and Caddy handling TLS, hosting the Bookstore above
- Looking for my first developer role in 2026, where I can own features from idea to production

---

<p align="center">
  <a href="https://www.linkedin.com/in/tranqn/">LinkedIn</a> &nbsp;·&nbsp;
  <a href="mailto:tran.qn@protonmail.com">Email</a> &nbsp;·&nbsp;
  <a href="https://quocnamtran.com">Portfolio</a>
  <br />
  <sub>Open to new ideas and the right team. Let's talk.</sub>
</p>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=120&section=footer" />
</div>
