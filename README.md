<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=26&pause=1000&color=2F81F7&center=true&vCenter=true&width=600&lines=Hey%2C+I'm+Tanuj+%F0%9F%91%8B;Full-Stack+Developer;React.js+%2B+Spring+Boot;Building+with+AI+%2F+RAG;AWS+Cloud+Enthusiast" alt="Typing SVG" />

<p>
<a href="https://www.linkedin.com/in/tanujmethi"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
<a href="https://tanujmethi.in"><img src="https://img.shields.io/badge/Portfolio-2F81F7?style=for-the-badge&logo=vercel&logoColor=white"></a>
<a href="mailto:tanujcode02@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"></a>
<a href="https://leetcode.com/u/Tanuj_02"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black"></a>
</p>

</div>

---

### 👋 A bit about me

I'm a Computer Science undergrad at JECRC University, Jaipur, three years into figuring out that the interesting part of software isn't the framework you pick — it's what happens when the frontend, backend, database, and cloud actually have to work together without falling over.

I started out just wanting things to *look* right on screen. Somewhere along the way I got pulled into what's happening behind the screen — async pipelines, message queues, vector databases, tenant isolation — and now I'd genuinely rather debug a race condition than fix a CSS margin. (Most days.)

Right now I split my time between:
- Shipping full-stack apps end-to-end with **React.js + Spring Boot**
- Wiring up **AI/RAG systems** — embeddings, vector search, LLM-grounded answers — with Spring AI and Gemini
- Getting real (not tutorial-real) practice on **AWS**, because a project that only runs on `localhost` doesn't count

---

### 🧠 How I actually build things

```
Understand what's actually being asked
        ↓
Sketch the data flow before the UI
        ↓
Build the boring backend plumbing first
        ↓
Wire the frontend to real endpoints, not mocks
        ↓
Break it on purpose, then fix it
        ↓
Deploy it so it's not just "done on my machine"
```

I'd rather spend an extra evening understanding *why* JWT refresh tokens are misbehaving than paste a fix I don't fully get. Slower, but it sticks.

---

### 🛠️ What I reach for

**Languages** — Java, JavaScript, Python, C, C++

**Frontend** — React.js, Redux Toolkit, React Router DOM, Tailwind CSS

**Backend** — Spring Boot, Spring Security, REST APIs, JWT Auth, WebSockets, RabbitMQ

**AI / GenAI** — Spring AI, Google Gemini, Retrieval-Augmented Generation, Qdrant, Agentic AI

**Data & Cloud** — MySQL, Amazon RDS, AWS (S3 · EC2 · Lambda · API Gateway · DynamoDB · VPC · IAM · CloudWatch · ELB)

**Tooling** — Git, Docker, Postman, Linux, VS Code

<p>
<img src="https://skillicons.dev/icons?i=java,spring,react,redux,mysql,aws,rabbitmq,docker,git,py,cpp,tailwind" />
</p>

---

### 🚀 Projects I'm proud of

<details open>
<summary><b>🤖 Helpdesk AI — a support desk that actually reads your docs</b></summary>
<br>

The problem: support teams drown in the same repeated questions buried across scattered internal documents. The fix: a **multi-tenant RAG platform** built on Spring Boot + Spring AI, where each company's data stays strictly walled off from every other company's — enforced at the vector-search layer, not just the UI.

What made this one hard (and worth building):
- An **asynchronous ingestion pipeline** over RabbitMQ: verify → extract text → chunk → embed → store in Qdrant, so uploading a 200-page PDF doesn't block anything
- **Tenant isolation baked into the retrieval layer** itself — `companyId` as vector metadata, filtered at query time, so no cross-tenant leakage is even possible
- **Gemini embeddings + QuestionAnswerAdvisor**, paired with JDBC-backed conversational memory so the assistant actually remembers earlier turns in a session instead of answering each question cold

`Spring Boot` `Spring AI` `Google Gemini` `Qdrant` `RabbitMQ` `Java 21`

</details>

<br>

<details open>
<summary><b>🤝 Skill Swap — trade skills, not money</b></summary>
<br>

A peer-to-peer platform where people teach each other instead of paying for courses. Built the real-time layer with **WebSockets** so chat feels instant rather than polled, secured sessions with JWT, and used Redux Toolkit to cut down redundant API calls — the frontend actually feels fast, not just looks fast.

🔗 **Live:** [skill-swap-ptp.vercel.app](https://skill-swap-ptp.vercel.app/)

`React.js` `Spring Boot` `REST APIs` `Amazon RDS`

</details>

<br>

<details open>
<summary><b>🎧 AudioBook Streaming App — Audible, built from scratch</b></summary>
<br>

A full audiobook platform, not just a player widget — auth, streaming playback, an **admin analytics dashboard**, and a community layer with nested comment replies and ratings. AWS S3 handles both audio files and cover art, so storage scales independently of the app server.

`React.js` `Spring Boot` `MySQL` `AWS S3`

</details>

---

### 📜 Certifications

| | |
|---|---|
| 🌐 | Juniper Networks Certified Associate, Junos (JNCIA-Junos) |
| ☁️ | AWS Cloud Quest: Cloud Practitioner |
| ☁️ | Google Cloud Computing Foundations |
| 🗣️ | NPTEL — Soft Skills |
| 🧑‍🤝‍🧑 | NPTEL — Leadership and Team Effectiveness |

---

### 🎯 Right now

Heading into my final year, so I'm splitting focus between **DSA + system design** for placements, and pushing my AI/RAG projects from "works in a demo" to "would survive real users." If you're working on something in that space, I'm always up for a conversation.

---

### ☁️ AWS Skill Builder

Active on **AWS Skill Builder**, where I publish articles and pick up badges alongside my hands-on AWS work.

🔗 [builder.aws.com/community/@tanuj02](https://builder.aws.com/community/@tanuj02?tab=badges)

<div align="center">
<sub>📍 Jaipur, India &nbsp;·&nbsp; Building, breaking, and rebuilding things 🚀</sub>
</div>
