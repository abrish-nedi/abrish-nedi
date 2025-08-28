<!-- Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&height=180&color=0:0ea5e9,100:6366f1&text=Welcome%20to%20Abreham's%20GitHub!&fontAlignY=35&animation=fadeIn&fontColor=ffffff" alt="welcome banner"/>

<h1 align="center">👋 Hi, I'm Abreham Nedi</h1>
<p align="center">
Cloud ☁️ | Java & Spring Boot ⚙️ | Flutter 📱 | DevOps Curious 🛠️<br/>
<em>Atlanta, GA • he/him</em>
</p>

<p align="center">
  <a href="https://komarev.com/ghpvc/?username=abrish-nedi&style=for-the-badge">
    <img src="https://komarev.com/ghpvc/?username=abrish-nedi&style=for-the-badge" alt="Profile views"/>
  </a>
  <a href="mailto:abrehamnedi@gmail.com">
    <img src="https://img.shields.io/badge/Email-abrehamnedi%40gmail.com-blue?style=for-the-badge&logo=gmail" alt="email"/>
  </a>
  <a href="https://www.linkedin.com/in/abrehamnedi">
    <img src="https://img.shields.io/badge/LinkedIn-Abreham%20Nedi-0A66C2?style=for-the-badge&logo=linkedin" alt="linkedin"/>
  </a>
  <a href="https://github.com/abrish-nedi">
    <img src="https://img.shields.io/badge/GitHub-abrish--nedi-181717?style=for-the-badge&logo=github" alt="github"/>
  </a>
</p>

---

## 🚀 About Me
- 🎓 **B.S. in Computer Science** (GSU) & 4+ yrs building software
- 💼 Java, Spring Boot, JPA/Hibernate, MySQL/Postgres, REST APIs
- 📱 Flutter/Dart mobile • Firebase • SQLite
- ☁️ AWS basics (EC2, S3, RDS), Docker, CI/CD
- 🎯 Goal: **Backend/Full-Stack/Cloud role in Atlanta, GA**

---

## 🧰 Tech Stack
<p>
  <img src="https://skillicons.dev/icons?i=java,spring,hibernate,postgres,mysql,docker,aws,git,github,js,ts,react,html,css,flutter,firebase,python" />
</p>

---

## 📊 GitHub Stats
<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=abrish-nedi&show_icons=true&theme=tokyonight&include_all_commits=true" height="165" alt="stats"/>
  <img src="https://github-readme-streak-stats.herokuapp.com?user=abrish-nedi&theme=tokyonight&date_format=j%20M%5B%20Y%5D" height="165" alt="streak"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=abrish-nedi&layout=compact&theme=tokyonight&langs_count=10" height="165" alt="top langs"/>
</div>

---

## 🧩 Featured Projects
| Project | Description | Repo |
|---|---|---|
| 📚 **Recipe & Meal Planner** | Flutter app with Firebase auth, image upload, and search/filter | [Repo](https://github.com/abrish-nedi) <!-- replace with exact repo link --> |
| ✅ **Task Manager (Flutter + Firebase)** | Real-time CRUD, nested sub-tasks, sorting/filtering | [Repo](https://github.com/abrish-nedi) |
| 🐠 **Virtual Aquarium (Flutter)** | Animated fish, add/customize, local storage | [Repo](https://github.com/abrish-nedi) |
| 🃏 **Card Organizer** | Organize cards by suits with SQLite | [Repo](https://github.com/abrish-nedi) |
| 💬 **Message Board App** | Firebase auth + real-time chat | [Repo](https://github.com/abrish-nedi) |
| 💸 **Expense Tracker (JavaFX + Spring Boot + Postgres + Docker)** | REST APIs, Docker Compose, JPA | [Repo](https://github.com/abrish-nedi) |

> Tip: Pin 6 repos to your profile (Profile → Customize your pins).

---

## 🗺️ Activity Graph
<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=abrish-nedi&theme=react-dark&hide_border=true&area=true" alt="activity graph"/>
</p>

---

## 🤝 Connect
- 📫 **abrehamnedi@gmail.com**
- 💼 **/in/abrehamnedi**
- 🌐 Portfolio: *add when ready*

---

### ⭐ Bonus: Snake Contributions (optional)
Create `.github/workflows/snake.yml`:

```yaml
name: Generate snake animation
on:
  schedule: [{cron: "0 3 * * *"}]
  workflow_dispatch:
permissions:
  contents: write
jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: abrish-nedi
          outputs: |
            dist/snake.svg
      - name: Push snake.svg to output branch
        run: |
          git config user.name "github-actions[bot]"
          git config user.email "41898282+github-actions[bot]@users.noreply.github.com"
          git add -A
          git commit -m "Update snake"
          git push
