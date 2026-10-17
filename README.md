![header](https://user-images.githubusercontent.com/59575502/127335491-fdba1874-e943-4d3c-ab8c-678ffe22f8b8.png)

<h1 align="center">Hi <img src="https://raw.githubusercontent.com/ABSphreak/ABSphreak/master/gifs/Hi.gif" width="30px">, I am Noel Yohannes Ghebremeskel</h1>
<h3 align="center">Full-Stack Developer · Toronto</h3>

<div align="center">
    <a href="https://nyohen.github.io" target="_blank"><img src="https://img.shields.io/badge/Portfolio-nyohen.github.io-%23ff4b1f?style=flat-square" alt="Portfolio"></a>
    <a href="https://www.linkedin.com/in/noel-yohannes" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?&style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
    <a href="mailto:yohannesghebremesk@gmail.com"><img src="https://img.shields.io/badge/Email-yohannesghebremesk%40gmail.com-%23393837?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
</div>

<p align="center">
    <em>
        I build software you can check: tools where the important numbers are verified by code, not taken on faith.<br>
        Student at <b>York University</b> (Lassonde School of Engineering) · 2+ years shipping code at <b>MPAC</b><br>
        <b>Open to Winter + Summer 2027</b> software, cloud and data internships and co-ops · Canadian citizen
    </em>
    <br><br>
    <b><i>Thought: "Life is full of choices… choose wisely!"</i></b>
</p>

<hr>

### 🔭 What I'm building

**Casefile**: AI investigation assistant
Drafts anti-money-laundering case write-ups where plain code, not the AI, checks every figure.
- A LangGraph agent writes the narrative sentence by sentence, each linked to the transactions it cites.
- A deterministic verifier checks every amount, date, account and ID against the ledger. Unproven sentences retry up to 3 times, then go to a human.
- Flagged **417 / 417** deliberately corrupted claims, with **0 / 994** clean claims falsely flagged. **36** automated tests in CI.
- `Python` `LangGraph` `FastAPI` `SQLite` `React` `TypeScript` `Docker` `GitHub Actions`

**RootCause**: incident diagnosis agent
An on-call agent that finds why a microservice broke, then re-queries the telemetry to prove it before it reports.
- Gathers evidence from metrics, traces and logs, and proposes a root cause.
- Proves it with fresh, independent queries (a later window, stricter thresholds). It loops at most 3 times, then reports "inconclusive".
- A 15-service simulated store with 10 failure flags that have known answers. **52** automated tests in CI.
- `Python` `LangGraph` `FastAPI` `Prometheus` `Jaeger` `React` `TypeScript` `Docker`

<sub>Both repos are private while I finish them. So far the AI step has only run on a stand-in model; real-model testing is next.</sub>

### 💼 Experience

**Junior Systems Developer**, MPAC · Apr 2025 – Oct 2026
- Built a React investigation dashboard over AWS Redshift data with a staff AI engineer, plus an AWS QuickSight dashboard. Delivered both to the VP.
- Rebuilt legacy sign-in with AWS Amplify and Cognito, adding multi-factor authentication.
- Re-architected ArcGIS Online field mapping to fetch aliases through the Esri REST API.

**Co-op Developer**, MPAC · Jan – Sep 2023
- Automated the company-wide offboarding workflow with Python AWS Lambda functions and auto-created Jira Service Desk tickets.

### 🛠 Toolkit
**Languages** Python · TypeScript · JavaScript · SQL · HTML · CSS
**Front end** React
**Back end & data** FastAPI · REST APIs · AWS Redshift · SQLite
**Cloud & DevOps** AWS Lambda · Cognito · Amplify · QuickSight · Docker · Kubernetes · GitHub Actions
**AI systems** LangGraph agents · verification loops

### 🎓 Education
**York University**, Lassonde School of Engineering: BA, Specialized Honours in Digital Media (Development Stream) · Expected 2027
**Seneca Polytechnic**: Advanced Diploma, Computer Programming & Analysis · 2020 – 2023 · President's Honour List

### 😄 About me
- 💬 Ask me about front-end and back-end development, AWS, or building AI tools you can trust
- 📫 How to reach me: [Email](mailto:yohannesghebremesk@gmail.com) · [LinkedIn](https://www.linkedin.com/in/noel-yohannes)
- 😄 Pronouns: He/Him
- ⚡ Fun fact: I speak Italian and Tigrinya

---
