<!-- HEADER -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=220&section=header&text=Quoc%20Nam%20Tran&fontSize=48&fontAlignY=38&desc=Fullstack%20Web%20Developer&descAlignY=60&descSize=18" />
</div>

<h3 align="center">Fullstack developer building with React, Angular, TypeScript and Django. Based in Germany 🇩🇪</h3>
<p align="center"><i>Open to web developer roles for 2026</i></p>

<p align="center">
  <a href="https://www.linkedin.com/in/tranqn/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white&style=flat-square" height="26" /></a>
  <a href="mailto:tran.qn@protonmail.com"><img src="https://img.shields.io/badge/Email-6D4AFF?logo=protonmail&logoColor=white&style=flat-square" height="26" /></a>
  <a href="https://quocnamtran.com"><img src="https://img.shields.io/badge/Portfolio-000000?logo=vercel&logoColor=white&style=flat-square" height="26" /></a>
</p>

<p align="center">
I build web apps end to end: frontend, backend, and the AI features in between.<br />
Modern TypeScript stack, real tests, and a focus on shipping things that solve the problem.
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
- **AI workflow:** Claude Code · Claude Skills · spec-driven development

---

### How I work

AI is part of my daily toolchain, not a gimmick. What matters is using it well.

- **Claude Code** runs in my terminal every day for refactoring, writing tests, and tracking down bugs across a whole codebase.
- I write my own **Claude Skills** to automate the repetitive parts: project setup, commit messages, review checklists.
- I work **spec-first**. I write down what "done" means and the acceptance criteria before any code, so the AI has something real to build against and I can check the result.
- I read every line the AI writes. I review it, test it, and catch the mistakes before they reach a pull request.

The goal is simple: ship more, and ship it correct. You can see the habit in my repos: typed code, clean structure, and real tests instead of "works on my machine."

---

### Selected work

A few projects worth a look, with live demos and source linked:

**[Videoflix](https://videoflix.quocnamtran.com)** &nbsp;·&nbsp; [view code](https://github.com/tranqn/videoflix)
A Netflix-style video streaming platform. Upload a video and a Redis-queued worker transcodes it into three HLS quality levels in the background, while the whole API sits behind JWT auth carried in HttpOnly cookies. Deployed in Docker behind Caddy.
`Django REST` `Redis / RQ` `FFmpeg` `Docker` `Caddy`

**[Quizly](https://quizly.quocnamtran.com)** &nbsp;·&nbsp; [view code](https://github.com/tranqn/quizly)
Turns any YouTube video into a 10-question quiz. The backend pulls the audio, transcribes it with Whisper, and hands the transcript to Gemini to generate the questions, all behind the same cookie-based JWT auth as Videoflix.
`Django REST` `Whisper` `Gemini` `Docker`

**[Bookstore](https://bookstore.quocnamtran.com)** &nbsp;·&nbsp; [view code](https://github.com/tranqn/bookstore)
A bilingual bookstore rendered on the server, with a Three.js wall of covers you can pan through. Ask it for a book by mood and it answers in three tiers: Gemini first, then an embedding model running locally on the server, then a keyword search, so a query never comes back empty. Accessibility and performance budgets run on every push.
`Angular 21` `SSR` `TypeScript` `Three.js` `Gemini` `Docker`

**[Pokédex Holo TCG](https://pokedex.quocnamtran.com)** &nbsp;·&nbsp; [view code](https://github.com/tranqn/pokedex-holo-tcg)
All 1025 Pokémon shown as holographic trading cards you can open and tilt in 3D. A fast, installable web app in English and German, with automated tests.
`Next.js` `React` `TypeScript` `Three.js` `Tailwind`

**[Join, a Kanban task manager](https://join.quocnamtran.com)** &nbsp;·&nbsp; [view code](https://github.com/tranqn/join)
A drag-and-drop board for managing tasks and contacts, synced through Firebase with owner-scoped Firestore rules. Team project where I built and owned the entire frontend.
`Angular` `TypeScript` `Firebase` `Firestore`

---

### A bit about me

I'm Nam, a fullstack developer based in Germany. What I enjoy is turning a rough idea into something people can actually use. My own site, [quocnamtran.com](https://quocnamtran.com), is a good example: I built it in Angular 20, in both German and English, with the SEO and structure done from scratch. Off the keyboard, I'm usually on a volleyball court.

**What I'm doing now:**
- Building fullstack projects with real backends and in-app AI, all linked above
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
