<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=28&duration=3000&pause=1000&color=3498DB&center=true&vCenter=true&width=600&lines=👋+Hey%2C+I'm+Isindu+Eshan;🚀+Full+Stack+Developer;💻+Software+Engineering+Student;🌟+Problem+Solver+%26+Innovator" alt="Typing SVG" />
</div>

<div align="center">
  <img src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" width="500" height="300" alt="Coding Animation" style="border-radius: 15px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);"/>
</div>

---

## <div align="center">🎯 About Me</div>

<img align="right" alt="Coding" width="400" src="https://media.giphy.com/media/SWoSkN6DxTszqIKEqv/giphy.gif">

```typescript
const isindu = {
    pronouns: "He/Him",
    code: ["JavaScript", "TypeScript", "Java", "Kotlin", "Python", "SQL"],
    technologies: {
        frontEnd: {
            js: ["React", "Next.js", "Vue.js"],
            css: ["Tailwind CSS", "Styled Components", "SCSS"]
        },
        backEnd: {
            js: ["Node.js", "Express"],
            python: ["Django", "FastAPI"],
            java: ["Spring Boot"]
        },
        mobile: ["React Native", "Flutter", "Android"],
        databases: ["MySQL", "MongoDB", "PostgreSQL", "Firebase"],
        devOps: ["Docker", "AWS", "Vercel", "GitHub Actions"],
        tools: ["Git", "Figma", "VS Code", "Postman"]
    },
    currentFocus: "Building scalable full-stack applications",
    funFact: "I debug with console.log() and MySQL EXPLAIN! 😄"
};
```

<br clear="both"/>

---

## <div align="center">🛠️ Tech Stack</div>

<div align="center">

### 🌐 Frontend Development
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

### 🔧 Backend Development
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge&logo=express&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)

### 📱 Mobile Development
![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-0095D5?style=for-the-badge&logo=kotlin&logoColor=white)

### 🗄️ Database & Storage
![MySQL](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-039BE5?style=for-the-badge&logo=firebase&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)

### ☁️ Cloud & DevOps
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)

### 🛠️ Tools & IDEs
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)

</div>

---

## <div align="center">💼 Database Expertise</div>

<div align="center">

```sql
-- Some of my favorite MySQL queries 🚀

-- Complex JOIN with aggregation
SELECT u.name, COUNT(p.id) as project_count, 
       AVG(p.rating) as avg_rating
FROM users u
LEFT JOIN projects p ON u.id = p.user_id
WHERE u.active = 1
GROUP BY u.id
HAVING project_count > 0
ORDER BY avg_rating DESC;

-- Optimized indexes for better performance
CREATE INDEX idx_projects_user_rating 
ON projects(user_id, rating);
```

**📊 Database Technologies I Work With:**
- **MySQL** - Complex queries, stored procedures, optimization
- **MongoDB** - NoSQL document-based storage
- **PostgreSQL** - Advanced SQL features and JSON support
- **Firebase** - Real-time database for mobile apps

</div>

---

## <div align="center">📊 GitHub Analytics</div>

<div align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=Isindu980&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Isindu980&layout=compact&langs_count=8&theme=tokyonight"/>
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Isindu980&theme=tokyonight" alt="GitHub Streak"/>
</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Isindu980&theme=tokyo-night&hide_border=true" alt="GitHub Activity Graph"/>
</div>

---

## <div align="center">🏆 GitHub Trophies</div>

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=Isindu980&theme=tokyonight&no-frame=false&no-bg=false&margin-w=4&row=1" alt="GitHub Trophies"/>
</div>

---



## <div align="center">💡 What I'm Currently Working On</div>

<div align="center">

🔭 **Current Projects:**
- Building a full-stack web application with React, Node.js, and MySQL
- Developing a mobile app using React Native
- Learning advanced AWS services for cloud deployment

🌱 **Learning:**
- Advanced MySQL optimization techniques
- Microservices architecture
- Docker containerization
- GraphQL APIs

</div>

---

## <div align="center">📈 Coding Activity</div>

<div align="center">

<!--START_SECTION:waka-->
```text
JavaScript   8 hrs 15 mins   ████████████▓░░░░   45.2%
TypeScript   4 hrs 30 mins   ██████▓░░░░░░░░░░   24.8%
SQL          2 hrs 45 mins   ████▓░░░░░░░░░░░░   15.1%
CSS          1 hr 30 mins    ██▓░░░░░░░░░░░░░░   8.3%
Python       1 hr 12 mins    █▓░░░░░░░░░░░░░░░   6.6%
```
<!--END_SECTION:waka-->

</div>

---

## <div align="center">🌐 Connect With Me</div>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/isindu-eshan-a02b01323/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Isindu980)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:isindu980@gmail.com)
[![Facebook](https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white)](https://web.facebook.com/isindu.eshan.5)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/_._isindu_._)

📧 **Email:** isindu980@gmail.com  
🌍 **Portfolio:  (https:www.isindueshan.me)
📍 **Location:** Sri Lanka

</div>

---

## <div align="center">📈 Profile Views</div>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=Isindu980&label=Profile%20views&color=0e75b6&style=flat" alt="Profile views" />
</div>

---

<div align="center">
  <img src="https://media.giphy.com/media/LnQjpWaON8nhr21vNW/giphy.gif" width="60"> 
  <em><b>I love connecting with different people</b> so if you want to say <b>hi, I'll be happy to meet you more!</b> 😊</em>
</div>

<div align="center">
  <h3>💡 "The best code is no code at all... but when we must write code, let's make it count!" 🚀</h3>
</div>

---

<div align="center">
  
**Thanks for visiting my profile! Let's build something amazing together! 🚀**

<img src="https://media.giphy.com/media/jpVnC65DmYeyRL4LHS/giphy.gif" width="100">

</div>
