<div align="center">

<h1>Rupak Kumar</h1>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=20&duration=3200&pause=900&color=2C7BE5&center=true&vCenter=true&width=720&lines=SELECT+insights+FROM+raw_data%3B;Data+Analyst+%7C+Python+%7C+SQL+%7C+Power+BI;Clean.+Analyse.+Visualise.+Decide." alt="Typing SVG" />
</a>

<br/>

<a href="www.linkedin.com/in/rupak-kumar-1483abc"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="https://leetcode.com/u/Rupak1483/"><img src="https://img.shields.io/badge/LeetCode-Rupak1483-FFA116?style=flat-square&logo=leetcode&logoColor=black" alt="LeetCode"/></a>
<a href="mailto:rupaksingh8975@gmail.com"><img src="https://img.shields.io/badge/Gmail-Contact-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Gmail"/></a>
<img src="https://komarev.com/ghpvc/?username=Rupaksingh17&label=Profile+Views&color=203a43&style=flat-square" alt="Views"/>

</div>

---

## Profile as a Query

```sql
SELECT
    name,
    role,
    primary_tools,
    focus
FROM   analysts
WHERE  username = 'Rupaksingh17';
```

## About Me

```python
class DataAnalyst:
    def __init__(self):
        self.name = "Rupak Kumar"
        self.role = "Data Analyst"
        self.languages = ["C++", "Python", "SQL"]
        self.libraries = ["Pandas", "NumPy"]
        self.bi_tools = ["Power BI", "Excel", "Streamlit"]
        self.environment = ["Jupyter", "VS Code", "Git", "GitHub", "Codex"]
        self.practice = "Daily problem solving on LeetCode using C++"

    def approach(self):
        return [
            "Understand the business question",
            "Clean and validate the data",
            "Explore patterns and test assumptions",
            "Build dashboards and reports",
            "Communicate findings clearly",
        ]

    def currently_improving(self):
        return ["Advanced SQL", "Statistical analysis", "Data storytelling"]
```

---

## How I Work

```mermaid
flowchart LR
    A[Raw Data] --> B[Clean with Pandas and NumPy]
    B --> C[Query with SQL]
    C --> D[Explore in Jupyter]
    D --> E[Visualise in Power BI and Excel]
    E --> F[Share via Streamlit Apps and Reports]
    F --> G[Business Decision]
```

---

## Skill Proficiency (self-assessed)

```text
Python         ████████████████░░░░   80%
SQL            ███████████████░░░░░   75%
Excel          ████████████████░░░░   80%
Power BI       ██████████████░░░░░░   70%
Pandas         ████████████████░░░░   80%
NumPy          ██████████████░░░░░░   70%
Streamlit      ████████████░░░░░░░░   60%
C++            ██████████████░░░░░░   70%
```

---

## Tech Stack

<div align="center">

<h4>Languages</h4>

<img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white"/>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>

<br/>

<h4>Data Analysis</h4>

<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white"/>
<img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white"/>

<br/>

<h4>Visualisation and Apps</h4>

<img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
<img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white"/>
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white"/>

<br/>

<h4>Tools</h4>

<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
<img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white"/>
<img src="https://img.shields.io/badge/Codex-412991?style=for-the-badge&logo=openai&logoColor=white"/>

</div>

---

## Analyst Toolkit in Action

```python
import pandas as pd
import numpy as np

df = pd.read_csv("sales_data.csv")

df = (
    df.drop_duplicates()
      .assign(order_date=lambda d: pd.to_datetime(d["order_date"]))
      .dropna(subset=["revenue"])
)

monthly = (
    df.groupby(df["order_date"].dt.to_period("M"))["revenue"]
      .agg(total="sum", average="mean", orders="count")
      .reset_index()
)

monthly["growth_pct"] = monthly["total"].pct_change().mul(100).round(2)
print(monthly.tail())
```

---

## GitHub Activity

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=Rupaksingh17&show_icons=true&theme=github_dark&hide_border=true&count_private=true" alt="GitHub Stats"/>
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Rupaksingh17&layout=compact&theme=github_dark&hide_border=true&langs_count=6" alt="Top Languages"/>

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Rupaksingh17&theme=github-dark&hide_border=true" alt="Streak"/>

<br/>

<h4>LeetCode</h4>

<a href="https://leetcode.com/u/Rupak1483/"><img src="https://img.shields.io/badge/LeetCode-Rupak1483-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode Profile"/></a>
<img src="https://img.shields.io/badge/C++-84_solved-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++ solved"/>
<img src="https://img.shields.io/badge/MySQL-16_solved-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL solved"/>
<img src="https://img.shields.io/badge/50_Days_Badge-2026-2C7BE5?style=for-the-badge" alt="50 Days Badge 2026"/>

<br/><br/>

<table align="center">
  <tr>
    <th>Level</th>
    <th>Strongest Topics</th>
  </tr>
  <tr>
    <td>Advanced</td>
    <td>Dynamic Programming, Divide and Conquer, Backtracking</td>
  </tr>
  <tr>
    <td>Intermediate</td>
    <td>Math, Database, Binary Search</td>
  </tr>
  <tr>
    <td>Fundamental</td>
    <td>Array, String, Sorting</td>
  </tr>
</table>

</div>

---

## Currently

| Status | Details |
|--------|---------|
| Learning | Advanced SQL, statistics for data analysis |
| Building | Dashboards in Power BI and data apps in Streamlit |
| Practising | Data structures and algorithms in C++ on LeetCode |
| Open to | Data analyst roles, internships and collaboration |

---

## Contact

```text
Email     : rupaksingh8975@gmail.com
LinkedIn  : linkedin.com/in/rupak-kumar-38431b26b
LeetCode  : leetcode.com/u/Rupak1483
GitHub    : github.com/Rupaksingh17
```

<div align="center">
<sub>Data tells a story. I make sure it is heard.</sub>
</div>
