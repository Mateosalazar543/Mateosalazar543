<!-- Profile README for https://github.com/Mateosalazar543 -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0A1628,50:1D4ED8,100:38BDF8&height=170&section=header&text=Mateo%20Salazar%20Bogota&fontColor=ffffff&fontSize=60&fontAlignY=50&animation=fadeIn" alt="Mateo Salazar Bogota" width="100%" />

**Systems Engineering Student · Powered by AI · Java Developer**

<a href="https://github.com/Mateosalazar543">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=18&duration=3200&pause=900&color=3B82F6&center=true&vCenter=true&width=520&height=40&lines=Backend+%C2%B7+Architecture+%C2%B7+Reliable+software;Building+CareStock%3A+pharmacy+inventory;Turning+complex+requirements+into+clean+code;Bogot%C3%A1%2C+Colombia+%F0%9F%87%A8%F0%9F%87%B4" alt="Backend, architecture and reliable software" />
</a>

![Followers](https://img.shields.io/github/followers/Mateosalazar543?style=flat-square&logo=github&color=1D4ED8&labelColor=0D1117)
![University](https://img.shields.io/badge/Pontificia_Universidad_Javeriana-1D4ED8?style=flat-square&labelColor=0D1117)
![AI](https://img.shields.io/badge/Powered_by-AI-38BDF8?style=flat-square&labelColor=0D1117)

<a href="https://github.com/Mateosalazar543?tab=repositories"><img src="https://img.shields.io/badge/Explore_my_projects-0D1117?style=for-the-badge&logo=github&logoColor=white" alt="Explore my projects" /></a>
<a href="https://github.com/Mateosalazar543?tab=followers"><img src="https://img.shields.io/badge/Follow_on_GitHub-2563EB?style=for-the-badge&logo=github&logoColor=white" alt="Follow on GitHub" /></a>

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1D4ED8,100:38BDF8&height=3" alt="" width="100%" />

## 👨‍💻 About me

I'm a **Systems Engineering student** at **Pontificia Universidad Javeriana** (Bogotá 🇨🇴), **powered by artificial intelligence**. I use AI as a copilot to learn faster, build more and ship better, while still understanding the design decisions behind every line.

I'm interested in **backend development, software architecture and building reliable applications**.

| | |
|---|---|
| 🏥 **Building** | **CareStock**, a multi-branch pharmacy inventory management system |
| 🎮 **Created** | **VerbQuest**, a game to learn English irregular verbs |
| 🧠 **Learning** | SOLID · MVC · GoF design patterns · transactional data access · testing |
| 🤖 **Powered by** | AI-assisted learning and development |
| 🎯 **Goal** | Turn complex requirements into maintainable, practical code |
| 💬 **Ask me about** | Java, JavaFX, PostgreSQL, design patterns, clean architecture |

<details>
<summary><b>☕ Prefer code? Here's my bio in Java</b> (click to expand)</summary>

```java
class Mateo implements SystemsEngineer {

  String city    = "Bogotá, Colombia";
  String uni     = "Javeriana";
  String[] focus = {"Backend",
                    "Architecture",
                    "Reliable data"};
  boolean poweredByAI = true;

  void build() {
    learn(); design(); test(); ship();
  }
}
```

</details>

> [!NOTE]
> I like projects where design decisions matter: consistency, traceability and code that someone else can pick up and understand.

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1D4ED8,100:38BDF8&height=3" alt="" width="100%" />
## 🛠️ Tech stack

<div align="center">

**Languages**

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=java,c,cpp,js,html,css&theme=dark&perline=6" />
  <source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=java,c,cpp,js,html,css&theme=light&perline=6" />
  <img alt="Java, C, C++, JavaScript, HTML, CSS" src="https://skillicons.dev/icons?i=java,c,cpp,js,html,css&theme=dark&perline=6" />
</picture>

**Backend & Persistence**

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=postgres&theme=dark" />
  <source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=postgres&theme=light" />
  <img alt="PostgreSQL" src="https://skillicons.dev/icons?i=postgres&theme=dark" />
</picture>

![JavaFX](https://img.shields.io/badge/JavaFX-1D4ED8?style=flat-square&logo=openjdk&logoColor=white)
![JDBC](https://img.shields.io/badge/JDBC-0D1117?style=flat-square&labelColor=0D1117&color=38BDF8)
![Neon](https://img.shields.io/badge/Neon_Postgres-0D1117?style=flat-square&logo=postgresql&logoColor=38BDF8)

**Tools & DevOps**

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=maven,git,githubactions,docker,linux&theme=dark&perline=5" />
  <source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=maven,git,githubactions,docker,linux&theme=light&perline=5" />
  <img alt="Maven, Git, GitHub Actions, Docker, Linux" src="https://skillicons.dev/icons?i=maven,git,githubactions,docker,linux&theme=dark&perline=5" />
</picture>

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1D4ED8,100:38BDF8&height=3" alt="" width="100%" />


## 🚀 Featured projects

### 🏥 [CareStock](https://github.com/puj-course/FIS_2630_1204_G1)

Pharmacy inventory management with multi-branch segregation, session-aware operations, inventory traceability and a JavaFX interface.

| | |
|---|---|
| **Stack** | Java · JavaFX · PostgreSQL · JDBC · Maven |
| **Engineering** | MVC · GoF patterns · transactions · caching · automated tests |

<a href="https://github.com/puj-course/FIS_2630_1204_G1">View project →</a>

<details>
<summary><b>🏗️ Architecture at a glance</b> (click to expand)</summary>

<br/>

```mermaid
flowchart TB
    A[JavaFX View]:::ui --> B[Controller]:::ui
    B --> C[Services / Business logic]:::logic
    C --> D[Data access · JDBC]:::logic
    D --> E[(PostgreSQL · Neon)]:::data
    C -. cache .-> F[(In-memory cache)]:::data

    classDef ui fill:#1D4ED8,stroke:#93C5FD,color:#ffffff
    classDef logic fill:#0EA5E9,stroke:#BAE6FD,color:#ffffff
    classDef data fill:#0F172A,stroke:#38BDF8,color:#ffffff
```

Layers keep UI, business rules and persistence separate, so each part can be tested and changed on its own.

</details>

### 🎮 [VerbQuest](https://github.com/Mateosalazar543/VerbQuest)

A gamified experience to practice English irregular verbs, with adaptive difficulty and responsive design.

| | |
|---|---|
| **Stack** | HTML · CSS · JavaScript |
| **Highlights** | Adaptive quizzes · mobile-first UI · interactive learning |

<a href="https://github.com/Mateosalazar543/VerbQuest">View project →</a>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1D4ED8,100:38BDF8&height=3" alt="" width="100%" />

## 🧩 Engineering principles

| Principle | What it means in practice |
|---|---|
| 🧼 **Clean code** | Readable names, small functions, no surprises |
| 🏛️ **Purposeful architecture** | Patterns used because they solve a problem, not for decoration |
| 🗄️ **Reliable data** | Transactions, constraints and traceable changes |
| 🧪 **Tested** | Automated tests as a safety net for refactoring |
| 🤖 **AI with judgment** | AI speeds me up; I review, understand and own every decision |
| 🎨 **Good UX** | Software people actually enjoy using |

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1D4ED8,100:38BDF8&height=3" alt="" width="100%" />

## 📊 GitHub stats

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=Mateosalazar543&show_icons=true&bg_color=0D1117&title_color=38BDF8&icon_color=3B82F6&text_color=C9D1D9&border_color=1E3A8A&border_radius=12&include_all_commits=true" />
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api?username=Mateosalazar543&show_icons=true&bg_color=FFFFFF&title_color=1D4ED8&icon_color=2563EB&text_color=334155&border_color=BFDBFE&border_radius=12&include_all_commits=true" />
  <img alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=Mateosalazar543&show_icons=true&bg_color=0D1117&title_color=38BDF8&icon_color=3B82F6&text_color=C9D1D9&border_color=1E3A8A&border_radius=12&include_all_commits=true" width="420" />
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=Mateosalazar543&layout=compact&bg_color=0D1117&title_color=38BDF8&text_color=C9D1D9&border_color=1E3A8A&border_radius=12" />
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=Mateosalazar543&layout=compact&bg_color=FFFFFF&title_color=1D4ED8&text_color=334155&border_color=BFDBFE&border_radius=12" />
  <img alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Mateosalazar543&layout=compact&bg_color=0D1117&title_color=38BDF8&text_color=C9D1D9&border_color=1E3A8A&border_radius=12" width="420" />
</picture>

<br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=Mateosalazar543&background=0D1117&ring=3B82F6&fire=38BDF8&currStreakNum=FFFFFF&sideNums=FFFFFF&currStreakLabel=38BDF8&sideLabels=94A3B8&dates=64748B&border=1E3A8A&border_radius=12" />
  <source media="(prefers-color-scheme: light)" srcset="https://streak-stats.demolab.com?user=Mateosalazar543&background=FFFFFF&ring=2563EB&fire=1D4ED8&currStreakNum=0F172A&sideNums=0F172A&currStreakLabel=1D4ED8&sideLabels=475569&dates=64748B&border=BFDBFE&border_radius=12" />
  <img alt="GitHub streak" src="https://streak-stats.demolab.com?user=Mateosalazar543&background=0D1117&ring=3B82F6&fire=38BDF8&currStreakNum=FFFFFF&sideNums=FFFFFF&currStreakLabel=38BDF8&sideLabels=94A3B8&dates=64748B&border=1E3A8A&border_radius=12" width="420" />
</picture>

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1D4ED8,100:38BDF8&height=3" alt="" width="100%" />

## 🗺️ Roadmap

`▰▰▱▱▱▱` **2 of 6 goals completed**

| Status | Goal |
|---|---|
| ✅ **Done** | Build and ship **VerbQuest** |
| ✅ **Done** | Apply MVC, GoF patterns and transactional data access in **CareStock** |
| 🔨 **In progress** | Complete **CareStock** with CI, automated tests and documentation |
| 🔜 **Next** | Learn **Spring Boot** and build a REST API |
| 🔜 **Next** | Explore **Docker** and cloud deployment |
| 🔜 **Next** | Contribute to open source |

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1D4ED8,100:38BDF8&height=3" alt="" width="100%" />

## 📫 Let's connect

<div align="center">

<a href="https://github.com/Mateosalazar543"><img src="https://img.shields.io/badge/GitHub-Mateosalazar543-0D1117?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
<!-- Add your own links when ready, then remove the comment markers:
<a href="https://www.linkedin.com/in/YOUR-USERNAME/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:YOUR-EMAIL@example.com"><img src="https://img.shields.io/badge/Email-Write_me-2563EB?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
-->

<br/><br/>

*Thanks for visiting! Keep learning. Keep building. 🚀*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:38BDF8,50:1D4ED8,100:0A1628&height=90&section=footer" alt="" width="100%" />

</div>
