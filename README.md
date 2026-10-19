<!-- Profile README for https://github.com/Mateosalazar543 -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:6D28D9,100:8B5CF6&height=190&section=header&text=Mateo%20Salazar&fontColor=ffffff&fontSize=52&fontAlignY=38&desc=Systems%20Engineering%20Student%20%C2%B7%20Powered%20by%20AI%20%C2%B7%20Java%20Developer&descAlignY=60&descSize=18" alt="Mateo Salazar header" width="100%" />

<a href="https://github.com/Mateosalazar543">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3200&pause=900&color=8B5CF6&center=true&vCenter=true&width=700&lines=Systems+Engineering+student+%C2%B7+Powered+by+AI;Backend+%C2%B7+Architecture+%C2%B7+Reliable+software;Building+CareStock%3A+pharmacy+inventory+system;Surviving+the+night+shift%2C+one+commit+at+a+time;Bogot%C3%A1%2C+Colombia+%F0%9F%87%A8%F0%9F%87%B4" alt="Typing animation" />
</a>

<br/>

![Followers](https://img.shields.io/github/followers/Mateosalazar543?style=for-the-badge&logo=github&color=0D1117&labelColor=0D1117)
![University](https://img.shields.io/badge/Pontificia_Universidad_Javeriana-0D1117?style=for-the-badge)
![AI](https://img.shields.io/badge/Powered_by-AI-8B5CF6?style=for-the-badge)

<a href="https://github.com/Mateosalazar543?tab=repositories"><img src="https://img.shields.io/badge/Explore_my_projects-0D1117?style=for-the-badge&logo=github&logoColor=white" alt="Explore my projects" /></a>
<a href="https://github.com/Mateosalazar543?tab=followers"><img src="https://img.shields.io/badge/Follow_on_GitHub-8B5CF6?style=for-the-badge&logo=github&logoColor=white" alt="Follow on GitHub" /></a>

</div>

---

## 👨‍💻 About me

I'm a **Systems Engineering student** at **Pontificia Universidad Javeriana** (Bogotá 🇨🇴), **powered by artificial intelligence**: I use AI as a copilot to learn faster, build more and ship better, while still understanding the design decisions behind every line. I'm interested in **backend development, software architecture and building reliable applications**.

| | |
|---|---|
| 🏥 **Building** | **CareStock**, a multi-branch pharmacy inventory management system |
| 🎮 **Created** | **VerbQuest**, a game to learn English irregular verbs |
| 🧠 **Learning** | SOLID · MVC · GoF design patterns · transactional data access · testing |
| 🤖 **Powered by** | AI-assisted learning and development: faster iteration, deeper understanding |
| 🎯 **Goal** | Turn complex requirements into code that's maintainable and practical |
| 💬 **Ask me about** | Java, JavaFX, PostgreSQL, design patterns, clean architecture |

> [!TIP]
> I like projects where design decisions matter: consistency, traceability and code that someone else can pick up and understand.

---

## 🛠️ Tech stack

<div align="center">

**Languages**

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

**Tools & technologies**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![JavaFX](https://img.shields.io/badge/JavaFX-007396?style=for-the-badge&logo=openjdk&logoColor=white)
![Maven](https://img.shields.io/badge/Apache_Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Neon](https://img.shields.io/badge/Neon_Postgres-00E599?style=for-the-badge&logo=postgresql&logoColor=0D1117)
![AI-Assisted](https://img.shields.io/badge/AI--Assisted_Development-8B5CF6?style=for-the-badge)

</div>

---

## 🚀 Featured projects

<table>
<tr>
<td width="50%" valign="top">

#### 🏥 [CareStock](https://github.com/puj-course/FIS_2630_1204_G1)

Pharmacy inventory management with multi-branch segregation, session-aware operations, inventory traceability and a JavaFX interface.

**Stack:** Java · JavaFX · PostgreSQL · JDBC · Maven

**Engineering:** MVC · GoF patterns · transactions · caching · automated tests

<a href="https://github.com/puj-course/FIS_2630_1204_G1">View project →</a>

</td>
<td width="50%" valign="top">

#### 🎮 [VerbQuest](https://github.com/Mateosalazar543/VerbQuest)

A gamified experience to practice English irregular verbs, with adaptive difficulty and responsive design.

**Stack:** HTML · CSS · JavaScript

**Highlights:** adaptive quizzes · mobile-first UI · interactive learning

<a href="https://github.com/Mateosalazar543/VerbQuest">View project →</a>

</td>
</tr>
</table>

<details>
<summary><b>🏗️ CareStock: architecture at a glance</b> (click to expand)</summary>

<br/>

```mermaid
flowchart LR
    A[JavaFX View] --> B[Controller]
    B --> C[Services / Business logic]
    C --> D[Data access · JDBC]
    D --> E[(PostgreSQL · Neon)]
    C -. cache .-> F[(In-memory cache)]
    G[GitHub Actions] -. build & tests .-> B
```

Layers keep UI, business rules and persistence separate, so each part can be tested and changed on its own.

</details>

---

## 🧩 Engineering principles

| Principle | What it means in practice |
|---|---|
| 🧼 **Clean code** | Readable names, small functions, no surprises |
| 🏛️ **Purposeful architecture** | Patterns used because they solve a problem, not for decoration |
| 🗄️ **Reliable data** | Transactions, constraints and traceable changes |
| 🧪 **Tested** | Automated tests as a safety net for refactoring |
| 🤖 **AI with judgment** | AI speeds me up; I review, understand and own every decision |
| 🎨 **Good UX** | Software people actually enjoy using |

---

## 📊 GitHub stats

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=Mateosalazar543&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=8B5CF6&icon_color=8B5CF6&include_all_commits=true" />
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api?username=Mateosalazar543&show_icons=true&theme=default&hide_border=true&title_color=6D28D9&icon_color=6D28D9&include_all_commits=true" />
  <img alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=Mateosalazar543&show_icons=true&theme=tokyonight&hide_border=true" height="170" />
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=Mateosalazar543&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=8B5CF6" />
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=Mateosalazar543&layout=compact&theme=default&hide_border=true&title_color=6D28D9" />
  <img alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Mateosalazar543&layout=compact&theme=tokyonight&hide_border=true" height="170" />
</picture>

<br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=Mateosalazar543&theme=tokyonight&hide_border=true&background=0D1117&ring=8B5CF6&fire=8B5CF6&currStreakLabel=8B5CF6" />
  <source media="(prefers-color-scheme: light)" srcset="https://streak-stats.demolab.com?user=Mateosalazar543&theme=default&hide_border=true&ring=6D28D9&fire=6D28D9" />
  <img alt="GitHub streak" src="https://streak-stats.demolab.com?user=Mateosalazar543&theme=tokyonight&hide_border=true" height="170" />
</picture>

</div>

---

## 🗺️ Roadmap

- [x] Build and ship **VerbQuest**
- [x] Apply MVC, GoF patterns and transactional data access in **CareStock**
- [ ] Complete **CareStock** with CI, automated tests and documentation
- [ ] Learn **Spring Boot** and build a REST API
- [ ] Explore **Docker** and cloud deployment
- [ ] Contribute to open source

---

## 🌙 Night Shift at the Repo

> *Every developer works the night shift sometimes. Here's mine.*

```text
╔════════════════════════════════════════════════════╗
║  🔦 NIGHT SHIFT · 12:00 AM → 6:00 AM               ║
║  🔋 POWER LEFT: ██████████░░ 87%  (☕ + 🤖 powered)  ║
║  📟 STATUS: all systems stable · nothing moved...   ║
║             ...probably.                            ║
╚════════════════════════════════════════════════════╝
```

### 📹 Security cameras

| Camera | Location | Status |
|---|---|---|
| 📹 **CAM 01** | CareStock | 🟢 Online · in active development |
| 📹 **CAM 02** | VerbQuest | 🟢 Online · shipped |
| 📹 **CAM 03** | Spring Boot lab | 🟡 Loading... |
| 📹 **CAM 04** | Docker cellar | 🔴 Offline · coming soon |

### 🚪 Who's moving in the hallway?

The animatronics of software: they only show up when you stop watching. These are my defenses.

| Intruder | Real-life bug | Defense |
|---|---|---|
| 🐻 **Null Pointer Freddy** | `NullPointerException` | Validate inputs, use `Optional`, fail early |
| 🐰 **Off-by-one Bonnie** | Index and boundary errors | Boundary tests |
| 🐔 **Memory-leak Chica** | Unclosed connections and resources | `try-with-resources` |
| 🦊 **Race-condition Foxy** | Concurrency and inconsistent data | Transactions, proper isolation |

### 🕛 Surviving until 6 AM

```mermaid
timeline
    title My shift, hour by hour
    12 AM : Java and OOP foundations
    1 AM : PostgreSQL and JDBC
    2 AM : MVC · SOLID · GoF patterns
    3 AM : Testing and CI with GitHub Actions
    4 AM : Spring Boot and REST APIs
    5 AM : Docker and cloud deployment
    6 AM : Shift complete · ship it 🌅
```

---

## 📫 Let's connect

<div align="center">

<a href="https://github.com/Mateosalazar543"><img src="https://img.shields.io/badge/GitHub-Mateosalazar543-0D1117?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
<a href="https://www.linkedin.com/in/TU-USUARIO/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:TU-CORREO@ejemplo.com"><img src="https://img.shields.io/badge/Email-Write_me-8B5CF6?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>

<br/><br/>

*Thanks for visiting! Survive the night. Ship the code. 🚀*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:8B5CF6,50:6D28D9,100:0D1117&height=110&section=footer" alt="Footer wave" width="100%" />

</div>
