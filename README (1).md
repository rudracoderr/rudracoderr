<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=220&section=header&text=Rudraksh%20Kashyap&fontSize=48&fontColor=c9b8ff&animation=fadeIn&fontAlignY=38&desc=Backend-leaning%20Full%20Stack%20Engineer%20%7C%20Systems%20Thinker%20%7C%20Builder&descAlignY=58&descSize=18" width="100%"/>

<br/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=500&size=22&duration=3000&pause=1000&color=A78BFA&center=true&vCenter=true&width=650&lines=Building+FEEL+%E2%80%94+an+Animal+Rescue+Coordination+Platform;Learning+System+Design+%2B+Redis+%2B+PostgreSQL;Exploring+AI+Agents+and+LLMs;Node.js+%2B+React+%2B+React+Native+%2B+MongoDB" alt="Typing SVG" />
</a>

<br/><br/>

<a href="https://github.com/rudracoderr"><img src="https://img.shields.io/badge/GitHub-1a1b27?style=for-the-badge&logo=github&logoColor=A78BFA" /></a>
<a href="https://www.linkedin.com/in/rudraksh-devs/"><img src="https://img.shields.io/badge/LinkedIn-1a1b27?style=for-the-badge&logo=linkedin&logoColor=A78BFA" /></a>
<a href="https://portfolio-rudrakshh.netlify.app"><img src="https://img.shields.io/badge/Portfolio-1a1b27?style=for-the-badge&logo=vercel&logoColor=A78BFA" /></a>
<a href="mailto:rudrakshwork07@gmail.com"><img src="https://img.shields.io/badge/Email-1a1b27?style=for-the-badge&logo=gmail&logoColor=A78BFA" /></a>
<img src="https://img.shields.io/badge/India-1a1b27?style=for-the-badge&logo=googlemaps&logoColor=A78BFA" />

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=rudracoderr&style=for-the-badge&color=302b63&labelColor=1a1b27" />
<img src="https://img.shields.io/github/followers/rudracoderr?style=for-the-badge&color=302b63&labelColor=1a1b27&logo=github" />
<img src="https://img.shields.io/github/stars/rudracoderr?style=for-the-badge&color=302b63&labelColor=1a1b27&logo=github" />

</div>

<br/>

## About Me

```ts
const rudraksh = {
  role: "Backend-leaning Full Stack Developer",
  education: "Bachelor of Computer Applications (BCA)",
  status: "Student",
  location: "India",
  currentlyBuilding: "FEEL — Animal Rescue Coordination Platform",
  interests: [
    "Backend Engineering",
    "Full Stack Development",
    "Software Architecture",
    "System Design",
    "Artificial Intelligence",
  ],
};
```

I'm a Computer Applications student who spends most of his time on the backend side of things — API design, data modeling, and the decisions that make a system hold up under real usage. I work across the stack with **Node.js**, **Express**, **React**, **React Native**, **MongoDB**, and **Firebase**, but the part I enjoy most is figuring out how the pieces should talk to each other before I write the first line of a controller.

Right now that means building **FEEL**, a platform for coordinating animal rescues, and using it as a testbed for things like role-based access, geospatial queries, and notification pipelines — not because a tutorial told me to, but because the problem actually needed them.

I'm not chasing shiny badges. I'd rather ship something that works under a bit of pressure, understand *why* it works, and keep narrowing the gap between "student project" and "production system."

## Current Focus

```yaml
Currently:
  Building: FEEL - Animal Rescue Coordination Platform
  Learning: [Redis, PostgreSQL, System Design, AI Agents, LLMs]
  Refining: Backend architecture & API design patterns
  Goal: Becoming a dependable backend engineer
```

<br/>

## Tech Stack

**Languages**
<p><img src="https://skillicons.dev/icons?i=js,ts,html,css,cpp&theme=dark" /></p>

**Frontend**
<p><img src="https://skillicons.dev/icons?i=react,redux,tailwind,materialui&theme=dark" /></p>

**Backend**
<p><img src="https://skillicons.dev/icons?i=nodejs,express,react&theme=dark" /></p>

**Databases**
<p><img src="https://skillicons.dev/icons?i=mongodb,postgres,redis&theme=dark" /></p>

**Cloud & Backend-as-a-Service**
<p><img src="https://skillicons.dev/icons?i=firebase,gcp&theme=dark" /></p>

**Authentication**
<p><img src="https://skillicons.dev/icons?i=firebase&theme=dark" /></p>

**DevOps**
<p><img src="https://skillicons.dev/icons?i=docker,git,githubactions,railway&theme=dark" /></p>

**Version Control**
<p><img src="https://skillicons.dev/icons?i=git,github&theme=dark" /></p>

**Developer Tools**
<p><img src="https://skillicons.dev/icons?i=vscode,postman,figma,vercel,netlify&theme=dark" /></p>

<br/>

## Software Engineering Principles

| Principle | How I Apply It |
|---|---|
| **Clean Code** | Small, single-responsibility functions; consistent naming; readable over clever |
| **REST APIs** | Resource-oriented routes, proper status codes, versioned endpoints |
| **Authentication** | Firebase Auth, JWT-based session handling |
| **Authorization** | Role-based access control (RBAC) at the route/middleware layer |
| **Scalable Architecture** | Layered structure — routes, controllers, services, models |
| **Security** | Helmet, rate limiting, input validation, environment-based secrets |
| **Performance** | Pagination, indexing, and query shaping over premature caching |
| **Database Design** | Normalized schemas where relational, denormalized where read-heavy |
| **Code Reviews** | Small, reviewable commits with clear diffs and messages |
| **Problem Solving** | Break the system down before touching the editor |
| **Testing** | Manual + scripted API testing via Postman, expanding into automated tests |
| **Deployment** | CI-friendly builds, environment configs, Railway/Netlify pipelines |

<br/>

## Featured Projects

<details>
<summary><b>🐾 FEEL — Animal Rescue Coordination Platform</b></summary>
<br/>

**Project Overview**
A mobile-first platform connecting animal rescuers, volunteers, and administrators to coordinate rescue requests in real time. Built to replace ad-hoc coordination (calls, messages, spreadsheets) with a structured workflow.

**Architecture**
- React Native client (iOS/Android) communicating with a Node.js/Express REST API
- MongoDB as the primary data store, modeled around rescue requests, users, and roles
- Firebase used for authentication and push notifications
- Layered backend: routes → controllers → services → models

**Key Features**
- Real-time rescue request submission and tracking
- Volunteer assignment and status workflow (reported → assigned → in-progress → resolved)
- Admin dashboard for oversight and case management
- Geolocation-based matching between rescue requests and nearby volunteers

**Tech Stack**
`React Native` `Node.js` `Express` `MongoDB` `Firebase Authentication` `Firebase Cloud Messaging`

**Engineering Challenges**
- Designing a role model that cleanly separates rescuer, volunteer, and admin permissions without duplicating logic across routes
- Structuring geospatial queries in MongoDB to match volunteers to nearby cases efficiently
- Keeping the notification pipeline reliable across app states (foreground/background/killed)

**Security Features**
- Firebase-backed authentication
- Role-based authorization middleware on protected routes
- Helmet for secure HTTP headers
- Rate limiting on public-facing endpoints

**Performance Optimizations**
- Paginated list endpoints for rescue requests and case history
- Indexed geospatial and status fields in MongoDB

**Scalability**
- Stateless API design to allow horizontal scaling
- Service layer decoupled from route handlers to keep business logic portable

**Repository:** `github.com/rudracoderr/feel`
**Status:** 🚧 In active development
**Roadmap:** Volunteer reputation scoring · in-app chat · multi-city rollout · admin analytics dashboard

</details>

<details>
<summary><b>⛅ Weather Application</b></summary>
<br/>

**Project Overview**
A React-based weather lookup application that fetches and displays live conditions for any searched location.

**Key Features**
- City-based weather search
- Current conditions display (temperature, description, icon)
- Responsive layout for mobile and desktop

**Tech Stack**
`React` `Weather API`

**Repository:** `github.com/rudracoderr/weather-app`
**Status:** ✅ Complete

</details>

<details>
<summary><b>💼 Portfolio Website</b></summary>
<br/>

**Project Overview**
A personal portfolio site showcasing projects, skills, and contact information, deployed for public access.

**Key Features**
- Project showcase with links
- Skills overview
- Contact section

**Tech Stack**
`React`

**Repository:** `github.com/rudracoderr/portfolio`
**Status:** ✅ Live

</details>

<details>
<summary><b>🧮 Scientific Calculator</b></summary>
<br/>

**Project Overview**
A browser-based scientific calculator supporting standard and advanced mathematical operations.

**Key Features**
- Standard arithmetic and scientific functions
- Keyboard input support
- Clean, minimal interface

**Tech Stack**
`HTML` `CSS` `JavaScript`

**Repository:** `github.com/rudracoderr/scientific-calculator`
**Status:** ✅ Complete

</details>

<br/>

## Engineering Timeline

```
2025 ─┬─ Started BCA
      ├─ Completed frontend development coursework
      ├─ Built Portfolio Website, Weather App, Scientific Calculator
      │
2026 ─┼─ Building FEEL (Animal Rescue Coordination Platform)
      ├─ Learning Redis, PostgreSQL, System Design
      ├─ Exploring AI Agents & LLMs
      │
Next  ─┴─ Contribute to open source
        Deepen backend engineering & system design skills
        Ship production-grade software
```

<br/>

## GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=rudracoderr&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=A78BFA&icon_color=A78BFA&text_color=c9d1d9" width="49%"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=rudracoderr&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=A78BFA&text_color=c9d1d9" width="39%"/>

<br/>

<img src="https://streak-stats.demolab.com/?user=rudracoderr&theme=tokyonight&hide_border=true&background=0D1117&ring=A78BFA&fire=A78BFA&currStreakLabel=A78BFA" width="70%"/>

</div>

## GitHub Trophies

<div align="center">
<img src="https://github-profile-trophy.vercel.app/?username=rudracoderr&theme=darkhub&no-frame=true&margin-w=8&column=7" width="100%"/>
</div>

## Contribution Activity

<div align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=rudracoderr&theme=tokyo-night&hide_border=true&bg_color=0D1117&color=A78BFA&line=A78BFA&point=c9d1d9" width="100%"/>
</div>

## Contribution Snake

<div align="center">
<img src="https://raw.githubusercontent.com/rudracoderr/rudracoderr/output/github-contribution-grid-snake-dark.svg" width="100%"/>
</div>

<br/>

## Learning Roadmap

```yaml
Learning:
  - Redis
  - PostgreSQL
  - System Design
  - AI Agents
  - LLMs

Building:
  - FEEL (Animal Rescue Coordination Platform)

Reading:
  - Designing Data-Intensive Applications
  - System design case studies

Currently Exploring:
  - AI agent architectures
  - LLM-integrated backend workflows

Next Goal:
  - Ship FEEL to production
  - Land a backend engineering role
```

## Open Source Goals

- Make first meaningful contributions to backend/Node.js open-source projects
- Open-source parts of FEEL's architecture (e.g., the RBAC middleware) once stable
- Write technical notes on system design concepts as I learn them

<br/>

## Connect With Me

<div align="center">

<a href="https://github.com/rudracoderr"><img src="https://img.shields.io/badge/GitHub-1a1b27?style=for-the-badge&logo=github&logoColor=A78BFA" /></a>
<a href="https://www.linkedin.com/in/rudraksh-devs/"><img src="https://img.shields.io/badge/LinkedIn-1a1b27?style=for-the-badge&logo=linkedin&logoColor=A78BFA" /></a>
<a href="mailto:rudrakshwork07@gmail.com"><img src="https://img.shields.io/badge/Email-1a1b27?style=for-the-badge&logo=gmail&logoColor=A78BFA" /></a>
<a href="https://portfolio-rudrakshh.netlify.app"><img src="https://img.shields.io/badge/Portfolio-1a1b27?style=for-the-badge&logo=vercel&logoColor=A78BFA" /></a>

</div>

<br/>

<div align="center">

*"Code is easy to write and hard to maintain — build for the second part."*

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=120&section=footer" width="100%"/>
