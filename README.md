<div align="center">

# Hi, I'm Shiva 👋

<a href="https://github.com/Shivakrishnareddy-03"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1200&color=2F81F7&center=true&vCenter=true&width=560&lines=MSc+Data+Analytics+%40+University+of+Glasgow;SQL+%7C+dbt+%7C+Python+%7C+R;Building+end-to-end+data+projects" alt="Typing intro" /></a>

📍 Glasgow, UK &nbsp;·&nbsp; 🎯 Open to 2027 summer internships in Data Analytics, Data Science and ML

<a href="mailto:shivakrishnareddy2003@gmail.com"><img src="https://img.shields.io/badge/Email-shivakrishnareddy2003%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>

</div>

---

## 🧰 Tech stack

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/SQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL" />
<img src="https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white" alt="R" />
<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas" />
<img src="https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white" alt="dbt" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
<img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite" />
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" alt="Streamlit" />
<img src="https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white" alt="Plotly" />
<img src="https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white" alt="Supabase" />
<img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions" />
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
</p>

---

## 💼 Experience

### Data Analyst · [Swinfy Solutions](https://www.swinfy.com)

Core team member on **[Naamji](https://naamji.com)**, a live Indian baby-name platform with a 50,000-name catalogue.

<p>
<a href="https://naamji.com"><img src="https://img.shields.io/badge/Live_Site-naamji.com-C9A227?style=flat-square&logo=googlechrome&logoColor=white" alt="Live site" /></a>
<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
<img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white" alt="Supabase" />
<img src="https://img.shields.io/badge/SQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="SQL" />
</p>

<p align="center">
<a href="https://naamji.com"><img src="assets/naamji.jpg" width="760" alt="Naamji homepage" /></a>
</p>

- **Names data:** cleaned and structured the names catalogue and wrote the SQL behind it, so names can be filtered by religion, language, gender, rashi, Nakshatra, numerology and starting syllable
- **Backend:** fitted the data model into the app's Supabase (PostgreSQL) backend
- **Name cards:** designed and built every shareable name card, rendered dynamically for each name
- **Pages:** built the admin dashboard and the user pages, including profile, quiz results and shortlist sharing for family voting
- **Production support:** fixed bugs and errors on the live site

*The codebase is private company work; the product is live at [naamji.com](https://naamji.com).*

---

## 🚀 Featured project

### E-Commerce Order Analytics Platform

<p>
<a href="https://github.com/Shivakrishnareddy-03/E-Commerce-Order-Analytics-Platform"><img src="https://img.shields.io/badge/Code-GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="Code" /></a>
<a href="https://e-commerce-order-analytics-platform.onrender.com"><img src="https://img.shields.io/badge/Live_Dashboard-Render-46E3B7?style=flat-square&logo=render&logoColor=white" alt="Live dashboard" /></a>
<a href="https://youtu.be/TuanlATElKM"><img src="https://img.shields.io/badge/Demo_Video-YouTube-FF0000?style=flat-square&logo=youtube&logoColor=white" alt="Demo video" /></a>
</p>

Raw e-commerce CSVs → normalised PostgreSQL database → tested dbt star schema → live BI dashboard.
A two-person project with [Khasim Shaik](https://github.com/Khasim0210): he built the 3NF database and ingestion (Phase 1); I built the analytics layer and the app (Phases 2 and 3).

<p align="center">
<a href="https://e-commerce-order-analytics-platform.onrender.com"><img src="assets/dashboard.png" width="760" alt="Live Streamlit dashboard: key metrics, monthly revenue trend and order status" /></a>
</p>

<details>
<summary><b>What I built</b> (click to expand)</summary>
<br>

- **dbt star schema:** a 112K-row fact table with 4 dimensions, guarded by 43 data quality tests
- **CI/CD:** GitHub Actions runs SQLFluff linting and dbt tests on every pull request
- **Advanced SQL:** CTEs and window functions (LAG, RANK, cumulative sums, cohort retention), tuned with indexes and `EXPLAIN ANALYZE`
- **Dashboard:** Streamlit + Plotly, 6 charts and 3 live filters, every chart querying the live Neon PostgreSQL database
- **Deployment:** Render, with continuous deployment from GitHub

</details>

<details>
<summary><b>Data model</b> (click to expand)</summary>
<br>

<p align="center">
<img src="https://raw.githubusercontent.com/Shivakrishnareddy-03/E-Commerce-Order-Analytics-Platform/main/star_schema.png" width="720" alt="Star schema: fact_order_items with customer, product, seller and date dimensions" />
</p>

</details>

---

## 📂 More projects

| Project | What it is | Stack |
|---|---|---|
| [**sql-notes**](https://github.com/Shivakrishnareddy-03/sql-notes) | A hand-written SQL reference, from `SELECT` basics to joins, subqueries and window functions. Each note has a worked example and a plain-words explanation. | SQL · Markdown |
| [**UK Data Job Market**](https://github.com/Shivakrishnareddy-03/uk-data-job-market) *(in progress)* | SQL analysis of 3,684 UK data-job salary records (2024–25): pay by role, seniority and company size, and how the UK compares with other markets. | SQLite · DBeaver |
| **Beru** *(private, in progress)* | A personal AI assistant with voice input and output, short- and long-term memory, and a FastAPI backend. | Python · FastAPI |

---

## 📈 Right now

- 🎓 MSc modules: Regression Models, Statistical Inference, Probability, Databases and R programming
- 📊 Finishing the UK Data Job Market analysis
- 🤖 Building Beru in my spare time

---

## 🐍 Contribution activity

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Shivakrishnareddy-03/Shivakrishnareddy-03/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Shivakrishnareddy-03/Shivakrishnareddy-03/output/github-snake.svg" />
  <img alt="Snake eating my GitHub contribution graph" src="https://raw.githubusercontent.com/Shivakrishnareddy-03/Shivakrishnareddy-03/output/github-snake.svg" />
</picture>

<div align="center">

*Thanks for stopping by!*

</div>
