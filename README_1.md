<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,45:302b63,100:00B894&height=210&section=header&text=Ain%20Nurnabila&fontSize=48&fontColor=ffffff&fontAlignY=36&animation=twinkling&desc=data%20engineer%20in%20progress%20%E2%80%A2%20final%20year%20%40%20UTM&descSize=16&descAlignY=57" width="100%" />

<a href="https://bellaazharr.github.io/">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&duration=2600&pause=900&color=00E5B0&center=true&vCenter=true&width=600&lines=%3E+initialising+bella.exe...;final+year+CS+%40+UTM+%C2%B7+Data+Engineering;teaching+Spark+to+guess+flight+prices;building+pipelines+that+don't+break+at+2am;currently+accepting+internship+requests_" alt="typing intro" />
</a>

<br/>

[![E-Portfolio](https://img.shields.io/badge/E--Portfolio-Enter-00B894?style=for-the-badge&logo=googlechrome&logoColor=white)](https://bellaazharr.github.io/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ain-nurnabila-39885529a/)
[![Email](https://img.shields.io/badge/Email-Transmit-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:bellaaazharr28@gmail.com)
![Status](https://img.shields.io/badge/status-open%20to%20internships-00E5B0?style=for-the-badge&labelColor=0f0c29)

</div>

```text
> booting bella.exe ...

[ ok ] loading coffee ........................ done
[ ok ] mounting spark cluster ................ done
[ ok ] loading certifications (5) ............ done
[ ok ] location ............................... selangor, malaysia
[ >> ] degree progress ....................... ███████████████████░  year 4 / 4
[ >> ] flight price pipeline ................. running
[ ?? ] next mission .......................... your team, maybe?
```

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:00B894,50:302b63,100:0f0c29&height=3" width="100%" />

### `~/about-me`

Hi, I'm Bella. I'm a final-year Computer Science student at UTM, majoring in Data Engineering. My favourite part of any project is the messy middle, when the data is all over the place and nobody's sure yet what shape it should be in.

Two moments that taught me the most so far:

- A web scraper whose HTML parser broke on a live site. The fix wasn't more parsing code, it was finding the internal API the site was already using.
- A loan & savings system for Koperasi KADA Kelantan. Splitting loans and savings into two separate modules made each one easier to test, and easier for the client to trust.

Most of what I build comes back to one question: *how much structure does this data actually need?*

### `~/mission-log`

| mission | stack | status |
|---|---|---|
| **Flight Price Prediction Pipeline**<br/><sub>Spark medallion pipeline + IEEE-format paper, under lecturer supervision</sub> | PySpark · MLlib · Power BI | `🟡 in progress` |
| **Loan & Savings System**<br/><sub>for Koperasi Kakitangan KADA Kelantan Berhad, with Lembaga Kemajuan Pertanian Kemubu (KADA)</sub> | Web app | `🟢 delivered` |
| **Staff Leave Management Subsystem**<br/><sub>part of a larger Staff HR system, fully documented</sub> | SAP Business Application Studio | `🟢 deployed` |
| **Student Management System**<br/><sub>for IKM Johor Bahru (TVET MARA): registration + timetable upload</sub> | Flutter · Supabase · Netlify | `🟢 live` |
| **Jumping Pou**<br/><sub>a platformer game written from scratch, with full report</sub> | C++ | `✅ shipped` |

<details>
<summary><b>▸ peek inside the flight price pipeline</b> <sub>(click to expand)</sub></summary>

<br/>

```mermaid
%%{init: {'theme':'dark', 'themeVariables': {'fontFamily':'monospace', 'lineColor':'#00E5B0'}}}%%
flowchart LR
    K1["Kaggle<br/>flight prices"]:::src --> B
    K2["Kaggle<br/>US flight delays"]:::src --> B
    OM["Open-Meteo<br/>weather API"]:::src --> B
    B[("Bronze<br/>raw")]:::bronze --> S[("Silver<br/>cleaned")]:::silver
    S --> G[("Gold<br/>aggregates")]:::gold
    G --> C[("Curated<br/>enriched")]:::cur
    C --> RF{{"Random Forest<br/>vs linear baseline"}}:::ml
    RF --> PB["Power BI<br/>dashboard"]:::out

    classDef src fill:#1b1b3a,stroke:#6c63ff,color:#fff
    classDef bronze fill:#3a2414,stroke:#cd7f32,color:#fff
    classDef silver fill:#2a2f36,stroke:#c0c0c0,color:#fff
    classDef gold fill:#3a3212,stroke:#ffd700,color:#fff
    classDef cur fill:#0f2e2a,stroke:#00E5B0,color:#fff
    classDef ml fill:#302b63,stroke:#00E5B0,color:#fff
    classDef out fill:#3a2e05,stroke:#F2C811,color:#fff
```

</details>

### `~/toolkit`

<div align="center">

<img src="https://skillicons.dev/icons?i=python,postgres,azure,aws,flutter,supabase,git&theme=dark" />

<br/><br/>

![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Alteryx](https://img.shields.io/badge/Alteryx-0078A8?style=flat-square&logo=alteryx&logoColor=white)

</div>

### `~/education`

**Universiti Teknologi Malaysia (UTM)**
Bachelor of Computer Science (Data Engineering) with Honours
`Year 4` · `CGPA 3.39`

<sub>Coursework I've enjoyed: Data Engineering, Business Intelligence, Cloud Computing, High Performance Data Processing</sub>

### `~/certifications-unlocked`

- [x] Microsoft Certified: Azure Data Fundamentals (AZ-900)
- [x] Alteryx Designer Core
- [x] AWS Academy Cloud Foundations
- [x] AWS Academy Cloud Developing
- [x] AWS Academy Lab Project: Cloud Data Pipeline Builder

### `~/e-portfolio`

Everything in one place, with projects, coursework and reflections sorted by semester.

**[→ enter bellaazharr.github.io](https://bellaazharr.github.io/)** · <sub>[academic record repo](https://github.com/bellaazharr/eportfolio-SECP3843)</sub>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0f0c29,50:302b63,100:00B894&height=3" width="100%" />

### `~/telemetry`

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=bellaazharr&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="165" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=bellaazharr&layout=compact&theme=tokyonight&hide_border=true" height="165" />

<img src="https://streak-stats.demolab.com/?user=bellaazharr&theme=tokyonight&hide_border=true" width="80%" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=bellaazharr&theme=tokyo-night&hide_border=true&area=true" width="100%" />

<br/>

<sub>still learning, still breaking things, still fixing them.</sub>

![Profile Views](https://komarev.com/ghpvc/?username=bellaazharr&color=00B894&style=flat-square&label=visitors%20logged)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00B894,50:302b63,100:0f0c29&height=110&section=footer" width="100%" />

</div>
