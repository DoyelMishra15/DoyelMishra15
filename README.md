<div align="center">

<img src="assets/header.svg" width="100%" alt="Doyel Mishra — Software Engineer, Backend, Full Stack, Applied AI/ML. Building ideas into software, one system at a time."/>

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-263F70?style=for-the-badge&labelColor=101F3D)](https://portfoliodoyel.netlify.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-263F70?style=for-the-badge&labelColor=101F3D)](https://www.linkedin.com/in/doyel-mishra-80932128b)
[![LeetCode](https://img.shields.io/badge/LeetCode-263F70?style=for-the-badge&labelColor=101F3D)](https://leetcode.com/u/FXyzwjysre/)
[![Email](https://img.shields.io/badge/Email-263F70?style=for-the-badge&labelColor=101F3D)](mailto:sujandoyel@gmail.com)
[![Scrimba · 20% off](https://img.shields.io/badge/Scrimba%20%C2%B7%2020%25%20off-263F70?style=for-the-badge&labelColor=101F3D)](https://scrimba.com?via=u45dd0e6)

<img src="assets/divider.svg" width="100%" alt=""/>

</div>

## About

I'm a Computer Science student (B.Tech, C.V. Raman Global University, class of 2027, CGPA 9.49) building toward a software engineering role at a product company.

I'm drawn to the parts of a project that make an idea hold up: the API contract, a scheduler that has to be provably correct, a test suite that catches regressions, and a README that says plainly what is and isn't deployed. That is why my projects pair a Python backend (mostly FastAPI) and a React frontend with real tests, and why I'd rather document a limitation than hide it.

I learn by building one thing end to end, then going back to fix its weakest part. Around that I practice DSA in Python, work through machine learning and NLP, and follow a structured full-stack course. I'm also looking to contribute to open source and learn from how other people review and structure code.

<br/>

## Currently working on

| Status | Focus | Detail |
|---|---|---|
| In progress | **[Scrimba](https://scrimba.com?via=u45dd0e6) Full Stack Developer Path** | Interactive lessons, applied directly in my React projects |
| In progress | **DSA in Python** | Regular problem solving; 200+ LeetCode problems so far |
| In progress | **Machine Learning** | Moving from classical models toward transformers, embeddings and retrieval |
| Ongoing | **Practical projects** | Backend-heavy products with tests, docs and stated limitations |
| Ongoing | **Open source and community** | Learning from other developers' code and discussions |

<div align="center"><img src="assets/divider.svg" width="100%" alt=""/></div>

## Selected work

<table>
<tr><td>

<sub>01 · FEATURED</sub>

### [LifeLine](https://github.com/DoyelMishra15/Lifeline)

**Turns scattered personal documents into a prioritized source of truth, and into an emergency action plan when something goes wrong.**

Collect → understand → prioritize → respond. Built for the **WeMakeDevs × AWS First Commit** hackathon (Build It track). [3-minute demo ↗](https://youtu.be/hGvXdTfEL2w)

**Technically interesting:** the full workflow runs locally in GitHub Codespaces with AWS SAM and LocalStack, using a deterministic offline reasoning engine and Tesseract OCR in place of cloud inference. The same SAM template defines the intended production path on Lambda, Bedrock, Cognito and Amplify, documented as **not yet deployed or tested against live AWS services**. A **108-test** backend suite covers validation, prioritization, local JWT auth, reminder sweeps, conflict detection and per-user data isolation.

![Python](https://img.shields.io/badge/Python-263F70?style=flat-square&labelColor=263F70) ![React](https://img.shields.io/badge/React-263F70?style=flat-square&labelColor=263F70) ![AWS SAM](https://img.shields.io/badge/AWS%20SAM-263F70?style=flat-square&labelColor=263F70) ![LocalStack](https://img.shields.io/badge/LocalStack-263F70?style=flat-square&labelColor=263F70) ![Docker](https://img.shields.io/badge/Docker-263F70?style=flat-square&labelColor=263F70)

</td></tr>
</table>

<table>
<tr>
<td width="50%" valign="top">

<sub>02</sub>

### [OrbitOps India](https://github.com/DoyelMishra15/orbitops-india)

**Satellite pass prediction and conflict-free ground-station scheduling for university CubeSat teams.**

Predicts AOS / max-elevation / LOS passes from live Celestrak data (or an offline fixture) and resolves competing requests into one schedule, with a plain-language reason for every accepted and rejected request.

**Technically interesting:** weighted interval scheduling (DP), cross-checked against a brute-force solver on 200 randomized instances. 44 backend tests pass.

![FastAPI](https://img.shields.io/badge/FastAPI-263F70?style=flat-square&labelColor=263F70) ![React](https://img.shields.io/badge/React%20%2B%20TS-263F70?style=flat-square&labelColor=263F70) ![Skyfield](https://img.shields.io/badge/Skyfield%20SGP4-263F70?style=flat-square&labelColor=263F70)

</td>
<td width="50%" valign="top">

<sub>03</sub>

### [Reflow](https://github.com/DoyelMishra15/reflow-revenue-recovery) &nbsp;·&nbsp; [Live demo ↗](https://reflow-revenue-recovery.onrender.com/)

**A gated ML pipeline for failed-payment recovery.**

Built for the Razorpay AI Buildathon. Hard safety gates decide what is safe to retry; a gradient-boosted classifier only scores the probability of success; every decision is audited.

**Technically interesting:** the model is kept out of the safety-critical decision. Rules gate, ML ranks.

![FastAPI](https://img.shields.io/badge/FastAPI-263F70?style=flat-square&labelColor=263F70) ![scikit-learn](https://img.shields.io/badge/scikit--learn-263F70?style=flat-square&labelColor=263F70) ![Decision Systems](https://img.shields.io/badge/Decision%20Systems-263F70?style=flat-square&labelColor=263F70)

</td>
</tr>
<tr>
<td width="50%" valign="top">

<sub>04</sub>

### [CareerLens AI](https://github.com/DoyelMishra15/CareerLens-AI)

**Resume ↔ job-description matching with skill-gap analysis and AI bullet rewriting.**

Semantic matching on an async backend; warm requests under 2 seconds.

**Technically interesting:** embedding-based matching rather than keyword overlap, served through an async API.

![FastAPI](https://img.shields.io/badge/FastAPI-263F70?style=flat-square&labelColor=263F70) ![sentence-transformers](https://img.shields.io/badge/sentence--transformers-263F70?style=flat-square&labelColor=263F70) ![spaCy](https://img.shields.io/badge/spaCy-263F70?style=flat-square&labelColor=263F70)

</td>
<td width="50%" valign="top">

<sub>MORE</sub>

### [All repositories →](https://github.com/DoyelMishra15?tab=repositories)

Data and ML side projects, including Streamlit dashboards and exploratory analysis, are in the full repository list.

</td>
</tr>
</table>

<div align="center"><img src="assets/divider.svg" width="100%" alt=""/></div>

## Tech stack

**Used in projects**

| | |
|---|---|
| **Languages** | ![Python](https://img.shields.io/badge/Python-263F70?style=flat-square&labelColor=263F70) ![Java](https://img.shields.io/badge/Java-263F70?style=flat-square&labelColor=263F70) ![C](https://img.shields.io/badge/C-263F70?style=flat-square&labelColor=263F70) ![JavaScript](https://img.shields.io/badge/JavaScript-263F70?style=flat-square&labelColor=263F70) ![TypeScript](https://img.shields.io/badge/TypeScript-263F70?style=flat-square&labelColor=263F70) |
| **Frontend** | ![HTML](https://img.shields.io/badge/HTML-263F70?style=flat-square&labelColor=263F70) ![CSS](https://img.shields.io/badge/CSS-263F70?style=flat-square&labelColor=263F70) ![React](https://img.shields.io/badge/React-263F70?style=flat-square&labelColor=263F70) ![Vite](https://img.shields.io/badge/Vite-263F70?style=flat-square&labelColor=263F70) |
| **Backend** | ![FastAPI](https://img.shields.io/badge/FastAPI-263F70?style=flat-square&labelColor=263F70) ![Flask](https://img.shields.io/badge/Flask-263F70?style=flat-square&labelColor=263F70) ![Pydantic](https://img.shields.io/badge/Pydantic-263F70?style=flat-square&labelColor=263F70) ![pytest](https://img.shields.io/badge/pytest-263F70?style=flat-square&labelColor=263F70) |
| **Databases** | ![MySQL](https://img.shields.io/badge/MySQL-263F70?style=flat-square&labelColor=263F70) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-263F70?style=flat-square&labelColor=263F70) ![SQLite](https://img.shields.io/badge/SQLite-263F70?style=flat-square&labelColor=263F70) |
| **AI / ML** | ![scikit-learn](https://img.shields.io/badge/scikit--learn-263F70?style=flat-square&labelColor=263F70) ![PyTorch](https://img.shields.io/badge/PyTorch-263F70?style=flat-square&labelColor=263F70) ![Transformers](https://img.shields.io/badge/Transformers-263F70?style=flat-square&labelColor=263F70) ![sentence-transformers](https://img.shields.io/badge/sentence--transformers-263F70?style=flat-square&labelColor=263F70) ![spaCy](https://img.shields.io/badge/spaCy-263F70?style=flat-square&labelColor=263F70) |
| **Data analysis** | ![NumPy](https://img.shields.io/badge/NumPy-263F70?style=flat-square&labelColor=263F70) ![Pandas](https://img.shields.io/badge/Pandas-263F70?style=flat-square&labelColor=263F70) ![Matplotlib](https://img.shields.io/badge/Matplotlib-263F70?style=flat-square&labelColor=263F70) ![Streamlit](https://img.shields.io/badge/Streamlit-263F70?style=flat-square&labelColor=263F70) |
| **Tools** | ![Git](https://img.shields.io/badge/Git-263F70?style=flat-square&labelColor=263F70) ![GitHub](https://img.shields.io/badge/GitHub-263F70?style=flat-square&labelColor=263F70) ![VS Code](https://img.shields.io/badge/VS%20Code-263F70?style=flat-square&labelColor=263F70) ![Jupyter](https://img.shields.io/badge/Jupyter-263F70?style=flat-square&labelColor=263F70) ![Docker](https://img.shields.io/badge/Docker-263F70?style=flat-square&labelColor=263F70) ![Codespaces](https://img.shields.io/badge/Codespaces-263F70?style=flat-square&labelColor=263F70) |

**Currently learning** &nbsp; [![Scrimba Full Stack Path](https://img.shields.io/badge/Scrimba%20Full%20Stack%20Path-0A1530?style=flat-square&labelColor=0A1530)](https://scrimba.com?via=u45dd0e6) ![DSA in Python](https://img.shields.io/badge/DSA%20in%20Python-0A1530?style=flat-square&labelColor=0A1530) ![Machine Learning](https://img.shields.io/badge/Machine%20Learning-0A1530?style=flat-square&labelColor=0A1530)

<sub>AWS Lambda, Bedrock, Cognito and Amplify appear in LifeLine's production design but have not been deployed or tested live, so they aren't listed as used.</sub>

<div align="center"><img src="assets/divider.svg" width="100%" alt=""/></div>

## Learn Full Stack Development with Scrimba

I'm currently working through Scrimba's Full Stack Developer Path. I enjoy its interactive learning environment, where you can pause lessons, edit code directly, and learn by building.

<div align="center">

<a href="https://scrimba.com?via=u45dd0e6"><img src="assets/scrimba-offer.svg" width="100%" alt="Get 20% off your Scrimba subscription — claim the discount"/></a>

### **GET 20% OFF YOUR SCRIMBA SUBSCRIPTION**

**[Claim the discount →](https://scrimba.com?via=u45dd0e6)**

<sub><a href="https://scrimba.com?via=u45dd0e6">https://scrimba.com?via=u45dd0e6</a></sub>

</div>

<table>
<tr>
<td width="33%" valign="top">

**Interactive lessons**<br/>
<sub>Pause the video, change the code, run it in place.</sub>

</td>
<td width="33%" valign="top">

**Build as you learn**<br/>
<sub>Project-based paths from front-end basics toward full stack.</sub>

</td>
<td width="33%" valign="top">

**20% off for you**<br/>
<sub>Buyers who use my link get 20% off their Scrimba subscription.</sub>

</td>
</tr>
</table>

> **Affiliate disclosure:** this is my affiliate link as a Scrimba affiliate (Scrimbassador, Starter level). Buyers who use it receive 20% off their subscription, and I may earn a 30% commission on qualifying payments during their first 12 months. It doesn't add to what you pay.

<div align="center"><img src="assets/divider.svg" width="100%" alt=""/></div>

## Certifications and achievements

**Certifications**

- Google Cybersecurity Certificate
- Beginner: Introduction to Generative AI
- Intermediate: Gemini for Google Cloud
- Advanced: Generative AI for Developers

**Achievements**

![Smart India Hackathon 2025 · National Finalist](https://img.shields.io/badge/Smart%20India%20Hackathon%202025-National%20Finalist-263F70?style=flat-square&labelColor=101F3D) ![ISRO · Internship Selectee](https://img.shields.io/badge/ISRO-Internship%20Selectee-263F70?style=flat-square&labelColor=101F3D) ![LeetCode · 200+ solved](https://img.shields.io/badge/LeetCode-200%2B%20solved-263F70?style=flat-square&labelColor=101F3D) ![CGPA 9.49/10](https://img.shields.io/badge/CGPA-9.49%2F10-263F70?style=flat-square&labelColor=101F3D)

<div align="center"><img src="assets/divider.svg" width="100%" alt=""/></div>

## GitHub stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=DoyelMishra15&show_icons=true&bg_color=0A1530&border_color=263F70&icon_color=718FCB&title_color=DCE5F5&text_color=A9B7CC&ring_color=718FCB&rank_icon=percentile&include_all_commits=true" height="165" alt="GitHub stats for DoyelMishra15"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=DoyelMishra15&layout=compact&bg_color=0A1530&border_color=263F70&title_color=DCE5F5&text_color=A9B7CC" height="165" alt="Most used languages"/>

<img src="https://streak-stats.demolab.com?user=DoyelMishra15&background=0A1530&border=263F70&ring=718FCB&fire=DCE5F5&currStreakLabel=DCE5F5&sideLabels=A9B7CC&dates=A9B7CC&sideNums=EAF1FF&currStreakNum=EAF1FF" height="150" alt="Contribution streak"/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=DoyelMishra15&bg_color=0A1530&color=A9B7CC&line=718FCB&point=EAF1FF&area=true&area_color=263F70&hide_border=true" width="100%" alt="Contribution activity graph"/>

<sub>Rendered by third-party services. If a card doesn't load, the numbers are on my <a href="https://github.com/DoyelMishra15">profile</a>.</sub>

</div>

<div align="center"><img src="assets/divider.svg" width="100%" alt=""/></div>

## Let's connect

I'm open to software engineering and AI/ML roles, project discussions and open-source collaboration. If something here is relevant to what you're building, or you want to talk backend design, ML systems or DSA, reach out.

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Doyel%20Mishra-263F70?style=for-the-badge&labelColor=101F3D)](https://www.linkedin.com/in/doyel-mishra-80932128b)
[![Portfolio](https://img.shields.io/badge/Portfolio-portfoliodoyel.netlify.app-263F70?style=for-the-badge&labelColor=101F3D)](https://portfoliodoyel.netlify.app/)
[![LeetCode](https://img.shields.io/badge/LeetCode-Profile-263F70?style=for-the-badge&labelColor=101F3D)](https://leetcode.com/u/FXyzwjysre/)
[![Email](https://img.shields.io/badge/Email-sujandoyel%40gmail.com-263F70?style=for-the-badge&labelColor=101F3D)](mailto:sujandoyel@gmail.com)

<br/>

<img src="https://komarev.com/ghpvc/?username=DoyelMishra15&label=PROFILE%20VIEWS&color=263F70&labelColor=101F3D&style=flat-square" alt="Profile views"/>

<img src="assets/footer.svg" width="100%" alt="Midnight sky with a crescent moon"/>

</div>
