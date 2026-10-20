<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=200&color=0:0f172a,50:2563eb,100:06b6d4&section=header&text=Kartikeya%20Mishra&fontSize=48&fontColor=ffffff&fontAlignY=38&desc=I%20build%20apps.%20I%20explore%20systems.%20I%20engineer%20for%20scale.&descSize=16&descAlignY=58" alt="Header" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=2800&pause=900&color=38BDF8&center=true&vCenter=true&width=850&lines=Full+Stack+Developer+%F0%9F%9A%80;Backend+%26+API+Engineering+%E2%9A%99%EF%B8%8F;Docker+%7C+CI%2FCD+%7C+Automation+%F0%9F%90%B3;System+Design+%26+Scalability+%F0%9F%8F%97%EF%B8%8F;Turning+ideas+into+working+software" alt="Typing roles" />

<p>
  <img src="https://komarev.com/ghpvc/?username=devKartikeya&label=PROFILE+VIEWS&color=0ea5e9&style=flat-square" alt="Profile views" />
  <img src="https://img.shields.io/github/followers/devKartikeya?label=FOLLOWERS&style=flat-square&color=2563eb" alt="Followers" />
  <img src="https://img.shields.io/github/stars/devKartikeya?affiliations=OWNER&label=STARS&style=flat-square&color=f59e0b" alt="Stars" />
</p>

<p>
  <a href="https://kartikeyamishra.vercel.app"><img src="https://img.shields.io/badge/Portfolio-0f172a?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>
  <a href="https://linkedin.com/in/kartikeya-mishra-8199973a9"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:kartikeya2122008@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

</div>

---

## 👋 About Me

I don't just want my apps to *work* — I want to know **how they talk, how data flows, how they fail, and how to make them reliable.**

Started with programming fundamentals → frontend → backend APIs → databases → auth → full-stack apps. Now going deeper into **containers, CI/CD, caching, queues and scalable architecture.**

> 🎯 **Goal:** Move beyond writing code to understanding the systems that make software reliable, maintainable and scalable.

```js
const kartikeya = {
  role: "Full Stack Developer → Backend / DevOps focused",
  currentlyBuilding: "WhyLong — URL shortener with queues, caching & rate limiting",
  currentlyLearning: ["AWS", "Kubernetes", "Terraform", "Observability"],
  stack: ["React", "Node.js", "Express", "MongoDB", "Redis", "RabbitMQ", "Docker"],
  philosophy: "Build → Break → Understand → Improve → Repeat",
  openTo: ["Internships", "Open-source", "Collabs", "Backend/Full-stack roles"],
};
```

---

## 🛠️ Tech Stack

<div align="center">

| | |
|:--|:--|
| **💻 Languages** | <img src="https://skillicons.dev/icons?i=js,ts,java,c,python,php" /> |
| **🎨 Frontend** | <img src="https://skillicons.dev/icons?i=html,css,react,tailwind,vite,nextjs" /> |
| **⚙️ Backend & DB** | <img src="https://skillicons.dev/icons?i=nodejs,express,laravel,mongodb,mysql" /> |
| **🐳 DevOps & Tools** | <img src="https://skillicons.dev/icons?i=docker,githubactions,linux,git,github,nginx" /> |
| **🧠 Exploring** | <img src="https://skillicons.dev/icons?i=redis,rabbitmq,kafka,cloudflare,aws,kubernetes" /> |

</div>

---

## ⚡ Engineering Focus

<table>
<tr>
<td width="50%" valign="top">

### 🌐 Full Stack
- React, responsive UI, component architecture
- REST APIs & app integration
- AuthN / AuthZ (JWT, cookies, bcrypt)
- Forms & validation (React Hook Form + Zod)

</td>
<td width="50%" valign="top">

### ⚙️ Backend
- Node.js, Express, PHP, Laravel
- SQL & NoSQL schema design
- Middleware, validation, error handling
- Caching, queues, WebSockets

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🐳 DevOps
- Dockerfiles, networking, volumes, Compose
- GitHub Actions CI/CD
- Linux & environment config
- Secrets management & deployment

</td>
<td width="50%" valign="top">

### 🏗️ System Design
- Caching & rate limiting
- Load balancing & horizontal scaling
- Async job processing & backpressure
- Resilience & failure handling

</td>
</tr>
</table>

---

## 🚀 Flagship Project — WhyLong

<div align="center">

### 🔗 More than shortening a URL — it's a backend engineering playground.

<a href="https://whylong.vercel.app"><img src="https://img.shields.io/badge/🌐_LIVE_DEMO-0f172a?style=for-the-badge" alt="Live" /></a>
<a href="https://github.com/devKartikeya/WhyLong"><img src="https://img.shields.io/badge/📦_SOURCE_CODE-2563eb?style=for-the-badge" alt="Source" /></a>

</div>

**Features:** short links & link management · customizable branded QR codes · click analytics · authenticated dashboards · responsive React + Tailwind UI

### 🧩 Architecture

```mermaid
flowchart LR
    U([User]) --> FE[React + Tailwind]
    FE --> LB{{Nginx / Load Balancer}}
    LB --> A1[Express API #1]
    LB --> A2[Express API #2]
    A1 & A2 --> R[(Redis Cache)]
    A1 & A2 --> DB[(MongoDB)]
    A1 & A2 -- publish jobs --> MQ[[RabbitMQ]]
    MQ --> W[Background Workers<br/>analytics • QR • cleanup]
    W --> DB
```

### 🔬 What it demonstrates

| Area | Implementation |
|:--|:--|
| **API layer** | Node.js, Express, REST |
| **Data** | MongoDB + Mongoose |
| **Auth** | JWT & cookie-based flows |
| **Performance** | Redis caching → fewer repeated DB reads |
| **Security** | Rate limiting & request protection |
| **Async work** | RabbitMQ background jobs |
| **Reliability** | Backpressure & resource management |
| **Infra** | Docker, CI/CD, load balancing, horizontal scaling |

`React` `TailwindCSS` `Node.js` `Express` `MongoDB` `Redis` `RabbitMQ` `Docker` `GitHub Actions`

---

## 🧰 More Projects

| Project | What it is | Stack | Links |
|:--|:--|:--|:--|
| 💰 **Xpense Tracker** | Full-stack finance app — income/expense tracking, charts, ledger, admin controls, password reset, PDF/Excel export | MongoDB · Express · React · Node | [Live](https://expense-tracker-mern-project-seven.vercel.app) · [Code](https://github.com/devKartikeya/expense-tracker-mern-project) |
| 🌍 **Heritage Junction** | Travel platform — destinations, packages, itineraries & booking workflows | Laravel · PHP · React · Inertia · MySQL | [Code](https://github.com/devKartikeya/Heritage-Junction) |
| ⚙️ **Node.js CI/CD Pipeline** | Hands-on automation — GitHub Actions, Docker builds, secrets & env config | Node.js · Docker · GitHub Actions | [Code](https://github.com/devKartikeya/Nodejs-GitHub-Actions-CI-CD-Pipeline) |
| 🎨 **Developer Portfolio** | Glassmorphism UI with GSAP + ScrollTrigger animations, EmailJS contact form | React · Tailwind · GSAP · Vite | [Live](https://kartikeyamishra.vercel.app) · [Code](https://github.com/devKartikeya/Kartikeya-Mishra) |

---

## 🧠 How I Think About Engineering

<details>
<summary><b>Click to expand — the "why" behind each tool</b></summary>
<br>

| Question | What I want to understand |
|:--|:--|
| SQL or NoSQL? | Relationships, consistency, query patterns, trade-offs |
| Why Docker? | Reproducible environments, consistent deployments |
| Why Redis? | When caching helps — and how invalidation affects correctness |
| Why a message queue? | Decoupling workloads, async processing |
| Why rate limiting? | Protecting resources from abusive traffic |
| Why a load balancer? | Spreading requests across app instances |
| Why CI/CD? | Repeatable delivery, less manual work |
| Why monitoring? | Detecting failures, understanding system behavior |

> The interesting part isn't learning a tool — it's knowing **when to use it, what it costs, and which problem it solves.**

</details>

---

## 🗺️ Journey & Roadmap

```mermaid
flowchart LR
    A[Fundamentals<br/>Java • C • Git] --> B[Web Dev<br/>HTML • CSS • JS • React]
    B --> C[Backend<br/>Node • Express • Laravel]
    C --> D[Data & APIs<br/>Mongo • MySQL • Auth]
    D --> E[DevOps<br/>Docker • Linux • CI/CD]
    E --> F[System Design<br/>Cache • Queues • Scale]
    F --> G[Next: Cloud<br/>AWS • K8s • Terraform]
    style G stroke-dasharray: 5 5
```

- [x] Build & deploy full-stack applications
- [x] Work with SQL and NoSQL databases
- [x] Implement authentication & protected APIs
- [x] Docker + GitHub Actions practice projects
- [x] Docker Compose & production container workflows
- [x] System design & scalability fundamentals
- [ ] Cloud infrastructure with **AWS**
- [ ] **Kubernetes** & **Terraform**
- [ ] Deeper Redis, messaging & distributed systems
- [ ] Monitoring, logging & observability
- [ ] Contribute to open-source

---

## 📊 GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=devKartikeya&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github" alt="Stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=devKartikeya&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages" />

<img width="75%" src="https://streak-stats.demolab.com?user=devKartikeya&theme=tokyonight&hide_border=true" alt="Streak" />

<img width="963" height="314" alt="image" src="https://github.com/user-attachments/assets/92b368b3-8f75-47c8-9b4c-5953bebfd0de" />
</div>

---

## 🧭 Principles

| | |
|:--|:--|
| 🔍 **Understand first** | Learn the problem before picking a solution |
| 🔨 **Build to learn** | Turn concepts into working projects |
| 📚 **Fundamentals > hype** | Know the trade-offs behind tools |
| 🤖 **Automate wisely** | Remove repetitive, error-prone work |
| 🧹 **Design for change** | Readable, maintainable code |
| 🐞 **Learn from failure** | Fix the cause, not the symptom |

---

## 🤝 Let's Connect

Open to **internships, collaborations and open-source** — if you're building something interesting around backend, DevOps or full-stack, say hi!

<div align="center">

<a href="https://github.com/devKartikeya"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
<a href="https://linkedin.com/in/kartikeya-mishra-8199973a9"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:kartikeya2122008@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>

**Build → Break → Understand → Improve → Repeat** 🔁

<img src="https://capsule-render.vercel.app/api?type=waving&height=120&color=0:0f172a,50:2563eb,100:06b6d4&section=footer" alt="Footer" />

</div>
