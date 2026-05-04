<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=20&duration=2500&pause=1200&color=58A6FF&background=0D111700&center=true&vCenter=true&width=640&height=56&lines=naufal+hilmiaji;backend+%26+infrastructure+developer;building+systems+that+run+in+production" alt="Typing" />

<br/>

<img src="https://img.shields.io/badge/Python-native-1E3B57?style=flat-square&logo=python&logoColor=3776AB" />
<img src="https://img.shields.io/badge/Docker-first-1E3B57?style=flat-square&logo=docker&logoColor=2496ED" />
<img src="https://img.shields.io/badge/Linux-daily-1E3B57?style=flat-square&logo=linux&logoColor=FCC624" />
<img src="https://img.shields.io/badge/Indonesia-🇮🇩-1E3B57?style=flat-square" />

<br/><br/>

[![Portfolio](https://img.shields.io/badge/naufalhilmiaji.github.io-visit-0D1117?style=for-the-badge&logo=githubpages&logoColor=58A6FF&labelColor=1E3B57)](https://naufalhilmiaji.github.io)

</div>

---

```
$ whoami
```

Backend and infrastructure developer focused on systems that handle real data at scale.
I build monitoring platforms, NLP tools for Bahasa Indonesia, and self-host everything on minimal hardware.

- ⚡ &nbsp;Real-time **electricity distribution monitoring** — production system at national scale
- 🧠 &nbsp;**Indonesian NLP** — hoax detection & text summarization, running on ARM hardware via Cloudflare Tunnel
- 📡 &nbsp;**AI notification routing** — content-aware, deduplicating, channel-intelligent delivery
- 🏠 &nbsp;**Self-hosted infra** — ARM STBs, Docker stacks, Cloudflare Tunnels, zero cloud budget
- 💬 &nbsp;**Bot automation** — WhatsApp & Telegram integrations at production scale

---

```
$ ls ~/projects --notable
```

<table>
<tr>
<td colspan="2" valign="top">

**⚡ AVEMON**

Real-time monitoring platform for electricity distribution networks. Hybrid Django + Node.js architecture with background schedulers, multi-database aggregation across PostgreSQL and SQL Server, and WhatsApp alerting gateway.

`Django` `Node.js` `PostgreSQL` `SQL Server` `GitLab CI`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**🧪 id-hoaxclickbait**

Indonesian hoax & clickbait headline detector. TF-IDF + SVM pipeline trained on Bahasa Indonesia corpus using PySastrawi. Containerized FastAPI service, self-hosted on an Amlogic S905X ARM board and exposed via Cloudflare Tunnel.

[`nlp.hilmiaji.dev/cekhoaks`](https://nlp.hilmiaji.dev/cekhoaks) &nbsp;·&nbsp; `FastAPI` `scikit-learn` `TF-IDF + SVM` `PySastrawi` `ARM`

</td>
<td width="50%" valign="top">

**📝 id-text-summarizer**

Extractive text summarizer for Bahasa Indonesia. Manual TextRank implementation — TF-IDF matrix → cosine similarity → PageRank (numpy, no graph lib). Handles text and file uploads. Runs fully on STB, no model file needed.

[`nlp.hilmiaji.dev/ringkas`](https://nlp.hilmiaji.dev/ringkas) &nbsp;·&nbsp; `FastAPI` `TextRank` `PySastrawi` `Docker` `ARM`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**📡 PrioSense**

Event-driven notification intelligence platform. Analyzes urgency, category, and sentiment using NLP, then routes to the optimal channel — WhatsApp, email, Slack, or SMS. Deduplication via RAG-like similarity with user preference learning.

`FastAPI` `Python` `NLP` `RAG` `Content Routing`

</td>
<td width="50%" valign="top">

**🌐 Portfolio**

Personal site built with Astro. Deployed via GitHub Pages with GitHub Actions pipeline.

`Astro` `TypeScript` `GitHub Actions`

</td>
</tr>
</table>

---

```
$ cat stack.json | jq
```

**Backend**

![Python](https://img.shields.io/badge/Python-161B22?style=flat-square&logo=python&logoColor=3776AB)
![Django](https://img.shields.io/badge/Django-161B22?style=flat-square&logo=django&logoColor=44B78B)
![FastAPI](https://img.shields.io/badge/FastAPI-161B22?style=flat-square&logo=fastapi&logoColor=009688)
![PHP](https://img.shields.io/badge/PHP-161B22?style=flat-square&logo=php&logoColor=8993BE)
![CodeIgniter](https://img.shields.io/badge/CodeIgniter-161B22?style=flat-square&logo=codeigniter&logoColor=EF4223)
![REST APIs](https://img.shields.io/badge/REST_APIs-161B22?style=flat-square&logo=fastapi&logoColor=58A6FF)

**Frontend**

![Vue.js](https://img.shields.io/badge/Vue.js-161B22?style=flat-square&logo=vuedotjs&logoColor=4FC08D)
![Astro](https://img.shields.io/badge/Astro-161B22?style=flat-square&logo=astro&logoColor=FF5D01)
![Bootstrap](https://img.shields.io/badge/Bootstrap-161B22?style=flat-square&logo=bootstrap&logoColor=7952B3)
![jQuery](https://img.shields.io/badge/jQuery-161B22?style=flat-square&logo=jquery&logoColor=0769AD)

**Infrastructure**

![Docker](https://img.shields.io/badge/Docker-161B22?style=flat-square&logo=docker&logoColor=2496ED)
![Linux](https://img.shields.io/badge/Linux-161B22?style=flat-square&logo=linux&logoColor=FCC624)
![Nginx](https://img.shields.io/badge/Nginx-161B22?style=flat-square&logo=nginx&logoColor=009639)
![Apache](https://img.shields.io/badge/Apache-161B22?style=flat-square&logo=apache&logoColor=D22128)
![Cloudflare](https://img.shields.io/badge/Cloudflare-161B22?style=flat-square&logo=cloudflare&logoColor=F38020)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-161B22?style=flat-square&logo=github-actions&logoColor=2088FF)
![GitLab CI](https://img.shields.io/badge/GitLab_CI-161B22?style=flat-square&logo=gitlab&logoColor=FC6D26)

**Data & ML**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-161B22?style=flat-square&logo=postgresql&logoColor=4169E1)
![SQL Server](https://img.shields.io/badge/SQL_Server-161B22?style=flat-square&logo=microsoftsqlserver&logoColor=CC2927)
![scikit-learn](https://img.shields.io/badge/scikit--learn-161B22?style=flat-square&logo=scikit-learn&logoColor=F7931E)

**Automation**

![Node.js](https://img.shields.io/badge/Node.js-161B22?style=flat-square&logo=node.js&logoColor=3C873A)
![WhatsApp Bot](https://img.shields.io/badge/WhatsApp_Bot-161B22?style=flat-square&logo=whatsapp&logoColor=25D366)
![Telegram Bot](https://img.shields.io/badge/Telegram_Bot-161B22?style=flat-square&logo=telegram&logoColor=26A5E4)
![Email Automation](https://img.shields.io/badge/Email_Automation-161B22?style=flat-square&logo=gmail&logoColor=EA4335)

---

<div align="center">

[![GitHub Stats](https://github-readme-stats.vercel.app/api?username=naufalhilmiaji&show_icons=true&theme=github_dark&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=3FB950&text_color=C9D1D9&rank_icon=github)](https://github.com/naufalhilmiaji)
&nbsp;
[![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=naufalhilmiaji&layout=compact&theme=github_dark&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=C9D1D9&langs_count=6)](https://github.com/naufalhilmiaji)

<br/>

[![GitHub Streak](https://streak-stats.demolab.com?user=naufalhilmiaji&theme=github-dark-blue&hide_border=true&background=0D1117&ring=58A6FF&fire=3FB950&currStreakLabel=58A6FF)](https://github.com/naufalhilmiaji)

</div>
