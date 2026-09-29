<a href="https://bellaazharr.github.io/"><img src="header.svg" width="100%" alt="Ain Nurnabila, data engineer in progress" /></a>

<div align="center">

<a href="https://bellaazharr.github.io/"><img src="https://img.shields.io/badge/E--PORTFOLIO-ENTER-00E5B0?style=for-the-badge&labelColor=0d0717&logo=googlechrome&logoColor=00E5B0" /></a>
<a href="https://www.linkedin.com/in/ain-nurnabila-39885529a/"><img src="https://img.shields.io/badge/LINKEDIN-CONNECT-ff4fd8?style=for-the-badge&labelColor=0d0717&logo=linkedin&logoColor=ff4fd8" /></a>
<a href="mailto:bellaaazharr28@gmail.com"><img src="https://img.shields.io/badge/EMAIL-TRANSMIT-00E5B0?style=for-the-badge&labelColor=0d0717&logo=gmail&logoColor=00E5B0" /></a>

</div>

<img src="terminal.svg" width="100%" alt="terminal intro" />

<img src="t-about.svg" width="100%" alt="01 about me" />

Hi, I'm Bella. My favourite part of any project is the messy middle, when the data is all over the place and nobody's sure yet what shape it should be in.

Two moments that taught me the most so far:

- A web scraper whose HTML parser broke on a live site. The fix wasn't more parsing code, it was finding the internal API the site was already using.
- A loan & savings system for Koperasi KADA Kelantan. Splitting loans and savings into two separate modules made each one easier to test, and easier for the client to trust.

Most of what I build comes back to one question: *how much structure does this data actually need?*

<img src="t-missions.svg" width="100%" alt="02 mission log" />

<a href="https://bellaazharr.github.io/"><img src="missions.svg" width="100%" alt="projects" /></a>

<details>
<summary><b>⟢ peek inside the flight price pipeline</b> <sub>(click to expand)</sub></summary>

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
    classDef ml fill:#302b63,stroke:#ff4fd8,color:#fff
    classDef out fill:#3a2e05,stroke:#F2C811,color:#fff
```

</details>

<img src="t-stack.svg" width="100%" alt="03 toolkit" />

<img src="stack.svg" width="100%" alt="toolkit" />

<img src="t-edu.svg" width="100%" alt="04 education and certs" />

**Universiti Teknologi Malaysia (UTM)**<br/>
Bachelor of Computer Science (Data Engineering) with Honours<br/>
`YEAR 4` `CGPA 3.39`

<details open>
<summary><b>⟢ certifications unlocked</b> <sub>(5)</sub></summary>
<br/>

- [x] Microsoft Certified: Azure Data Fundamentals (AZ-900)
- [x] Alteryx Designer Core
- [x] AWS Academy Cloud Foundations
- [x] AWS Academy Cloud Developing
- [x] AWS Academy Lab Project: Cloud Data Pipeline Builder

</details>

<img src="t-telemetry.svg" width="100%" alt="05 telemetry" />

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=bellaazharr&bg_color=0d0717&color=e9e4ff&line=00E5B0&point=ff4fd8&area=true&area_color=ff4fd8&hide_border=true&radius=12" width="100%" />

<img src="https://github-readme-stats.vercel.app/api?username=bellaazharr&show_icons=true&hide_border=true&count_private=true&bg_color=0d0717&title_color=ff4fd8&icon_color=00E5B0&text_color=e9e4ff&border_radius=12" height="160" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=bellaazharr&layout=compact&hide_border=true&bg_color=0d0717&title_color=ff4fd8&text_color=e9e4ff&border_radius=12" height="160" />

<br/><br/>

<sub>still learning, still breaking things, still fixing them.</sub>

<img src="https://komarev.com/ghpvc/?username=bellaazharr&color=ff4fd8&style=flat-square&label=VISITORS+LOGGED" />

</div>
