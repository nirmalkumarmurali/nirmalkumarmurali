<div align="center">

![Header](https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=28&duration=3000&pause=1000&color=3B82F6&width=700&lines=Hi+there%2C+I'm+Nirmal+Kumar+Murali+👋;Data+Analyst+%7C+Paris%2C+France+🗼;Python+%7C+SQL+%7C+Power+BI;Actively+seeking+internship+Jun%2FJul+2026)

</div>

---

## 🤖 About Me

Hey, 👋 I'm **Nirmal Kumar Murali**, a passionate Data Analytics and AI enthusiast currently pursuing my **Master's in Data Science & Analytics at EPITA, Paris**. I love solving real-world problems using Python, SQL, Power BI, and Machine Learning.

🔹 **Inshort about me:**

📊 Data Analysis & Visualisation — Python, SQL, Power BI, Tableau, Excel

🤖 Machine Learning & AI — Scikit-Learn, MLflow, TensorFlow, NLP, Hugging Face

📈 Business Intelligence & KPI Reporting — Dashboards, DAX, Decision Support

☁️ Cloud & DevOps — AWS Basics, GitHub Actions, CI/CD, Git

🔹 **Currently:**
- 🎓 MSc Data Science & Analytics — EPITA Paris (2023 – Present)
- 🔍 Actively looking for a **Data Analyst / BI Intern** — Paris · **Jun/Jul 2026**
- 🏗️ Building data projects published on GitHub

🔹 **Let's Connect!**
📩 nirmal-kumar.murali@epita.fr

---

## 🌐 Socials

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nirmal-kumar-murali/)
[![Portfolio](https://img.shields.io/badge/Portfolio-%23000000.svg?logo=vercel&logoColor=white)](https://nirmalkumarmurali.github.io/portfolio)
[![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:nirmal-kumar.murali@epita.fr)
[![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?logo=github&logoColor=white)](https://github.com/nirmalkumarmurali)

---

## 💻 Tech Stack

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white)
![mlflow](https://img.shields.io/badge/mlflow-%23d9ead3.svg?style=for-the-badge&logo=numpy&logoColor=blue)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)
![Scipy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)
![MicrosoftSQLServer](https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?style=for-the-badge&logo=microsoft%20sql%20server&logoColor=white)
![Power Bi](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Streamlit](https://img.shields.io/badge/Streamlit-%23FE4B4B.svg?style=for-the-badge&logo=streamlit&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![Anaconda](https://img.shields.io/badge/Anaconda-%2344A833.svg?style=for-the-badge&logo=anaconda&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Microsoft PowerPoint](https://img.shields.io/badge/Microsoft_PowerPoint-B7472A?style=for-the-badge&logo=microsoft-powerpoint&logoColor=white)

---

## 📂 Featured Projects

| Project | Stack | Status | Link |
|---------|-------|--------|------|
| 🎮 Steam Publisher & Developer Analytics | Python · SQL · Power BI · Pandas | ✅ Complete | [View →](https://github.com/nirmalkumarmurali/steam-publisher-analytics) |
| 🤖 End-to-End ML Pipeline | Python · Scikit-Learn · MLflow | 🔄 In Progress | Coming Soon |
| 💬 AI Job Description Analyser | Python · NLP · Hugging Face · Streamlit | 🔄 Coming Soon | Coming Soon |

---

## 🎮 Steam Project — Key SQL Finding

```sql
-- Most loved publishers (min 5 games, sorted by avg rating)
SELECT publisher,
       COUNT(*) AS game_count,
       AVG(positive * 100.0 / (positive + negative)) AS avg_rating
FROM steam_games
GROUP BY publisher
HAVING COUNT(*) >= 5
ORDER BY avg_rating DESC
LIMIT 5;

-- Key insight: Fireproof Games (97.5%) beats Valve (89.4%)
-- Scale ≠ Quality 🎯
-- Portal 2 = most loved game (98.7% positive across 430K+ reviews) ✅
```

---

## 📊 GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=nirmalkumarmurali&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=nirmalkumarmurali&layout=compact&theme=tokyonight&hide_border=true)

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=nirmalkumarmurali&theme=tokyonight&hide_border=true)

</div>

---

## 🐍 GitHub Contribution Snake

![github-snake](https://raw.githubusercontent.com/nirmalkumarmurali/nirmalkumarmurali/output/github-snake.svg)

---

## 🌟 Fun Facts

- 🌍 I speak **4 languages** — English, French (B1), Tamil & Telugu
- 🚲 I commute across Paris on a **Vélib** — best way to think through data problems
- ☕ Best code happens at **2am** — that's just science
- 🎮 Analysed **10,000+ Steam games** and proved Portal 2 is the most loved game ever
- 📈 Built **3 data projects** from scratch to prove skills are real

---

<div align="center">

![Profile Views](https://komarev.com/ghpvc/?username=nirmalkumarmurali&color=3b82f6&style=flat-square&label=Profile+Views)

**Open to internship opportunities in Data Analytics, BI, and Data Science**

*Paris-based · Available Jun/Jul 2026*

[![Let's Connect](https://img.shields.io/badge/Let's_Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nirmal-kumar-murali/)

</div>
