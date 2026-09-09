<div align="center">

<img src="https://raw.githubusercontent.com/Shehzad-Nisar/Shehzad-Nisar/main/assets/banner.svg" width="100%" alt="Shehzad Nisar — Software Engineer" />

<br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=15&duration=2600&pause=1200&color=2DD4BF&center=true&vCenter=true&width=650&lines=SOFTWARE+ENGINEER+%E2%80%94+JAVA+BACKEND+DEVELOPER;BUILDING+REST+APIs+%26+LAYERED+SYSTEMS;MERN+STACK+%2F+FULL-STACK+DEVELOPMENT;OPEN+TO+SOFTWARE+ENGINEERING+ROLES" alt="rotating role tagline" />

<br/><br/>

</div>

## `TECH STACKS`

<div align="center">

<sub><b>FRONTEND</b></sub>
<br/>
<img src="https://skillicons.dev/icons?i=react,nextjs,ts,js,tailwind&theme=dark" alt="React, Next.js, TypeScript, JavaScript, Tailwind CSS" />

<br/><br/>
<sub><b>BACKEND</b></sub>
<br/>
<img src="https://skillicons.dev/icons?i=java,spring,py,fastapi&theme=dark" alt="Java, Spring Boot, Python, FastAPI" />

<br/><br/>
<sub><b>DATABASES</b></sub>
<br/>
<img src="https://skillicons.dev/icons?i=mysql,mongodb&theme=dark" alt="MySQL, MongoDB" />

<br/><br/>
<sub><b>AI / ML</b></sub>
<br/>
<img src="https://skillicons.dev/icons?i=tensorflow,opencv&theme=dark" alt="TensorFlow, OpenCV" />

<br/><br/>
<sub><b>TOOLS</b></sub>
<br/>
<img src="https://skillicons.dev/icons?i=git,github,docker,postman&theme=dark" alt="Git, GitHub, Docker, Postman" />

</div>

<br/>

## `SYSTEM.STATUS`

```
> booting profile.exe
> loading identity ................ OK
> loading focus ..................... JAVA / SPRING BOOT
> loading domain .................... BACKEND SYSTEMS
> loading secondary ................. MERN STACK · AI/ML
> status ............................ ACCESS GRANTED
```
Final-year Computer Science graduate transitioning into professional software engineering, with a primary focus on backend development using Java and Spring Boot. I build REST APIs, apply layered application architecture, and think about software from the database and domain layer up—not just the API endpoint down.

Alongside backend engineering, I build full-stack applications using the MERN ecosystem, including MongoDB, Express, React, Next.js, and TypeScript. I also have hands-on experience developing AI/ML systems with TensorFlow Lite, MediaPipe, and FastAPI.

My current direction is clear: deepening my expertise in backend engineering, scalable APIs, software architecture, databases, and distributed systems, while continuing to leverage full-stack and AI/ML experience when building complete products.

Software Engineer · Java Backend Developer · Spring Boot Developer · MERN Stack Developer · Systems & API Development

Connect with me

📧 Email: shehzadnisar07@gmail.com
<br/>

## `CURRENT.MISSION`

```
╭──────────────────────────────────────────────────────────────╮
│  CURRENT SYSTEM                                                │
├──────────────────────────────────────────────────────────────┤
│  STATUS          ●  BUILDING                                   │
│  PRIMARY            Java · Spring Boot                         │
│  DOMAIN             Backend Systems & REST APIs                │
│  ARCHITECTURE       Layered — Controller → Service → Repository│
│  DATABASE           MySQL · MongoDB                             │
│  SECONDARY          MERN Stack · AI/ML · TensorFlow Lite        │
│  NEXT UP            JPA · Spring Security · Docker             │
╰──────────────────────────────────────────────────────────────╯
```

**Currently open to:**

```
Java Backend Development
Software Engineering
MERN / Full-Stack Development
```

<br/>

## `PROJECTS`

<br/>

### `01` — Distributed Digital Wallet
**A banking / wallet backend system**, not a CRUD tutorial. Models real financial operations — account creation, balance state, and transaction processing — through a properly layered Spring Boot architecture with validation enforced at every boundary.

```
CLIENT
  │
  ▼
CONTROLLER   → request validation & routing
  │
  ▼
SERVICE      → business logic, transaction rules
  │
  ▼
REPOSITORY   → data access abstraction
  │
  ▼
DATABASE     → persistent account & transaction state
```

<details>
<summary><b>Engineering details</b></summary>
<br/>

- Interface-driven service contracts with dependency injection
- Separation of concerns enforced across controller / service / repository layers
- Account and transaction validation handled at the service boundary, not in the client
- Designed around OOP principles rather than procedural request handling

</details>

![Java](https://img.shields.io/badge/-Java-0D1117?style=flat-square&logo=openjdk&logoColor=2DD4BF)
![Spring Boot](https://img.shields.io/badge/-Spring%20Boot-0D1117?style=flat-square&logo=springboot&logoColor=2DD4BF)
![REST API](https://img.shields.io/badge/-REST%20API-0D1117?style=flat-square&logo=fastapi&logoColor=2DD4BF)
![MySQL](https://img.shields.io/badge/-MySQL-0D1117?style=flat-square&logo=mysql&logoColor=2DD4BF)

**[→ View repository](https://github.com/Shehzad-Nisar/Distributed-Digital-Wallet)**

<br/>

### `02` — Sign Analyzer
**Real-time Pakistan Sign Language recognition** — a full pipeline from camera input to spoken output, running in real time. Recognizes Pakistan Sign Language gestures, including Urdu alphabet signs and dynamic, word-level gestures, and speaks the result back in English or Urdu.

```
MOBILE FRONTEND (Expo React Native)
  │  camera stream
  ▼
MEDIAPIPE HAND LANDMARKS
  │  landmark coordinates
  ▼
WEBSOCKET  (real-time channel)
  │
  ▼
FASTAPI  (Python backend)
  │
  ▼
TENSORFLOW LITE  → gesture inference
  │
  ▼
PREDICTION  → English / Urdu text + speech
```

<details>
<summary><b>Engineering details</b></summary>
<br/>

- Real-time inference loop with landmark extraction on-device via MediaPipe
- Persistent WebSocket channel between mobile client and inference backend
- Dynamic (multi-frame) gesture recognition, not just static-pose classification
- TensorFlow Lite chosen for on-path latency; FastAPI chosen for async I/O under a streaming workload

</details>

![Python](https://img.shields.io/badge/-Python-0D1117?style=flat-square&logo=python&logoColor=2DD4BF)
![FastAPI](https://img.shields.io/badge/-FastAPI-0D1117?style=flat-square&logo=fastapi&logoColor=2DD4BF)
![TensorFlow Lite](https://img.shields.io/badge/-TensorFlow%20Lite-0D1117?style=flat-square&logo=tensorflow&logoColor=2DD4BF)
![React Native](https://img.shields.io/badge/-Expo%20React%20Native-0D1117?style=flat-square&logo=expo&logoColor=2DD4BF)

**[→ View repository](https://github.com/Shehzad-Nisar/sign-analyzer)**

<br/>

### `03` — Basho Valley Foundation
An educational web platform built for a real-world foundation client — not a demo. Focused on content clarity and performance for a non-technical audience.

```
TYPESCRIPT  →  REACT  →  NEXT.JS  →  TAILWIND CSS  →  WEB PLATFORM
```

![Next.js](https://img.shields.io/badge/-Next.js-0D1117?style=flat-square&logo=nextdotjs&logoColor=2DD4BF)
![TypeScript](https://img.shields.io/badge/-TypeScript-0D1117?style=flat-square&logo=typescript&logoColor=2DD4BF)
![React](https://img.shields.io/badge/-React-0D1117?style=flat-square&logo=react&logoColor=2DD4BF)
![Tailwind](https://img.shields.io/badge/-Tailwind%20CSS-0D1117?style=flat-square&logo=tailwindcss&logoColor=2DD4BF)

**[→ View repository](https://github.com/Shehzad-Nisar/Basho-Valley-Foundation)**

<br/>

## `ARCHITECTURE`

`$ ./architecture --list`

```
JAVA BACKEND                     MERN STACK                     AI SYSTEM
─────────────                    ───────────                    ─────────
Java                              TypeScript                     MediaPipe
  │                                 │                               │
  ▼                                 ▼                               ▼
Spring Boot                      React                           FastAPI
  │                                 │                               │
  ▼                                 ▼                               ▼
REST API                         Next.js                        TensorFlow Lite
  │                                 │                               │
  ▼                                 ▼                               ▼
Service Layer                   MongoDB                         Inference
  │
  ▼
Repository
  │
  ▼
Database
```

Java backend is the system I'm building depth in. MERN stack and AI/ML are systems I've shipped real work in — the architecture above is ordered by where my focus actually is.

<br/>

## `CONTRIBUTION.ENGINE`

```
╭─────────────────────────────────────────────────╮
│  LIVE METRICS — PULLED DIRECTLY FROM GITHUB      │
╰─────────────────────────────────────────────────╯
```

<p align="center">
  <img width="48%" src="https://github-readme-stats.vercel.app/api?username=Shehzad-Nisar&show_icons=true&theme=dark&hide_border=true&bg_color=0D1117&title_color=2DD4BF&icon_color=2DD4BF&text_color=8B949E&ring_color=2DD4BF" />
  <img width="48%" src="https://streak-stats.demolab.com/?user=Shehzad-Nisar&theme=dark&hide_border=true&background=0D1117&stroke=2DD4BF&ring=2DD4BF&fire=2DD4BF&currStreakLabel=2DD4BF&sideLabels=8B949E&sideNums=E6EDF3&currStreakNum=E6EDF3&dates=8B949E" />
</p>

<p align="center">
  <img width="98%" src="https://github-readme-activity-graph.vercel.app/graph?username=Shehzad-Nisar&theme=react-dark&bg_color=0D1117&color=2DD4BF&line=2DD4BF&point=E6EDF3&area=true&area_color=2DD4BF&hide_border=true" />
</p>

<sub>Every number above is generated live by a GitHub-connected service — nothing on this page is hard-coded.</sub>

<br/>

## `ENGINEERING.PRINCIPLES`

```
01 — Understand the problem before writing code.
02 — Prefer simple, explicit architecture over clever abstractions.
03 — Validate at every system boundary, not just the edges.
04 — Design for change; avoid tight coupling.
05 — Build systems, not isolated features.
06 — Readable code is a deliverable, not an afterthought.
```

<br/>

## `LEARNING.PROTOCOL`

`$ ./learning --status`

```
JAVA                      BUILDING
  │
  ▼
SPRING BOOT               BUILDING
  │
  ▼
REST APIs                 BUILDING
  │
  ▼
MERN STACK (React/Next)   BUILDING
  │
  ▼
DATABASES (MySQL/Mongo)   BUILDING
  │
  ▼
SPRING SECURITY           LEARNING
  │
  ▼
DOCKER                    LEARNING
  │
  ▼
SYSTEM DESIGN             EXPLORING
  │
  ▼
DISTRIBUTED SYSTEMS       EXPLORING
```

<sub>Self-assessed, not claimed mastery — status labels reflect where I actually am on each.</sub>

<br/>

<details>
<summary><code>SYSTEM MESSAGE</code></summary>
<br/>

```
01001000 01100101 01101100 01101100 01101111 00100000 01001001 00100000 01100001 01101101 00100000 01010011 01101000 01100101 01101000 01111010 01100001 01100100 00100000 01001110 01101001 01110011 01100001 01110010 00100000 01100001 01101110 01100100 00100000 01001001 00100000 01100001 01101101 00100000 01100001 00100000 01010011 01101111 01100110 01110100 01110111 01100001 01110010 01100101 00100000 01000101 01101110 01100111 01101001 01101110 01100101 01100101 01110010 00101110
```

**[→ ACCESS](https://github.com/Shehzad-Nisar/secret-terminal)**

</details>

<br/>

## `CONTACT`

```
PROTOCOL      EMAIL / LINKEDIN / GITHUB
STATUS        OPEN TO BACKEND / SOFTWARE ENGINEERING / MERN ROLES
RESPONSE      WITHIN 24–48H
```

<p align="left">
<a href="mailto:shehzadnisar07@gmail.com"><img src="https://img.shields.io/badge/-Email-0D1117?style=flat-square&logo=gmail&logoColor=2DD4BF" /></a>
<a href="https://www.linkedin.com/in/shehzad-nisar-873467369"><img src="https://img.shields.io/badge/-LinkedIn-0D1117?style=flat-square&logo=linkedin&logoColor=2DD4BF" /></a>
<a href="https://github.com/Shehzad-Nisar"><img src="https://img.shields.io/badge/-GitHub-0D1117?style=flat-square&logo=github&logoColor=2DD4BF" /></a>
</p>

<br/>

<div align="center">
<sub>01010011 01001000 01000101 01001000 01011010 01000001 01000100 &nbsp;·&nbsp; built like a system, not a template</sub>
</div>
