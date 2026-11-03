<div align="center">

<img src="https://raw.githubusercontent.com/Adithya-charan/Adithya-charan/main/assets/hero.svg" alt="Adithya Charan Yaramalla, AI Engineer and Full-Stack Developer. I build AI that does real work, and the full stack that ships it." width="100%" />

<br/>

<a href="https://adithyacharanin.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-0B1020?style=for-the-badge&logo=googlechrome&logoColor=22D3EE" alt="Portfolio" /></a>
<a href="https://www.linkedin.com/in/adithya-charan-6b7bb138b/"><img src="https://img.shields.io/badge/LinkedIn-0B1020?style=for-the-badge&logo=linkedin&logoColor=22D3EE" alt="LinkedIn" /></a>
<a href="mailto:adityayaramalla@gmail.com"><img src="https://img.shields.io/badge/Email-0B1020?style=for-the-badge&logo=gmail&logoColor=22D3EE" alt="Email" /></a>
<a href="https://adithyacharanin.vercel.app/assets/resume/Adithya_Charan_Resume.pdf"><img src="https://img.shields.io/badge/R%C3%A9sum%C3%A9-0B1020?style=for-the-badge&logo=readdotcv&logoColor=22D3EE" alt="Résumé (PDF)" /></a>
<a href="https://unstop.com/u/yadi80725"><img src="https://img.shields.io/badge/Unstop-0B1020?style=for-the-badge&logo=target&logoColor=22D3EE" alt="Unstop" /></a>

</div>

<br/>

### `00` &nbsp;Signal

I'm a third-year B.Tech student in Artificial Intelligence & Data Science at KL University. Most of my time goes into LLM agents, retrieval, voice interfaces and computer vision, and into the backend and frontend work it takes to turn a model into something people can use.

I care about the boring half of AI products: input validation, deterministic rules around model output, audit trails, and tests. Many of my weekends are hackathons, which is where a lot of these projects started.

<br/>

### `01` &nbsp;The pattern I keep building

Across my projects the model is rarely the final authority. It observes or proposes, and a layer I can test decides what actually happens.

<img src="https://raw.githubusercontent.com/Adithya-charan/Adithya-charan/main/assets/pattern.svg" alt="Five floating 3D blocks labelled observe, reason, guard, act and verify, with a pulse travelling across them." width="100%" />

<table>
<tr>
<td width="20%" valign="top"><b>CUBE Returns Manager</b><br/><sub>A vision model observes</sub></td>
<td width="20%" valign="top"><b>Vaani</b><br/><sub>An LLM plans</sub></td>
<td width="20%" valign="top"><b>RecoverAI</b><br/><sub>A fine-tuned LLM recommends</sub></td>
<td width="20%" valign="top"><b>TrustLayer</b><br/><sub>A classifier tags PII</sub></td>
<td width="20%" valign="top"><b>RESOLVE</b><br/><sub>Memory recalls past fixes</sub></td>
</tr>
<tr>
<td valign="top"><sub>→ a deterministic rules engine decides the disposition</sub></td>
<td valign="top"><sub>→ the laptop agent runs only allowlisted actions</sub></td>
<td valign="top"><sub>→ policy authorizes before anything executes</sub></td>
<td valign="top"><sub>→ backend-enforced role policies, fully audited</sub></td>
<td valign="top"><sub>→ verification checks whether the fix stayed fixed</sub></td>
</tr>
</table>

<br/>

### `02` &nbsp;Selected builds

<table>
<tr>
<td width="50%" valign="top">

#### [RESOLVE](https://github.com/Adithya-charan/ResolveAi)
**Incident response that remembers.** Links each new incident to past root causes, failed and successful fixes, and whether the remediation held.

Uses Hindsight agent memory for recall and keeps structured incident history in PostgreSQL, with an LLM reasoning over both.

`Next.js` `TypeScript` `FastAPI` `PostgreSQL (Neon)` `Hindsight` `Groq`

</td>
<td width="50%" valign="top">

#### [CUBE Returns Manager](https://github.com/Adithya-charan/cube-04-returns-manager)
**Inspecting returned products with evidence.** Checks identity, completeness and condition from photos, then decides restock, refurbish or review.

Qwen3-VL only reports observations. A tested Python rules engine makes the call and sends uncertain cases to a human.

`YOLOv8` `Qwen3-VL (Ollama)` `FastAPI` `React` `SQLite` `pytest`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [Vaani](https://github.com/Adithya-charan/Vaani)
**A voice-first remote operator for a Windows laptop.** Speak or type on an Android phone in English, Hindi, Telugu or a mix, and the laptop carries it out.

The AI proposes a plan, and the agent executes only a short allowlist of actions over a private Tailscale link.

`Kotlin` `Jetpack Compose` `Python` `FastAPI` `Groq` `Sarvam AI`

</td>
<td width="50%" valign="top">

#### [Memora](https://github.com/Adithya-charan/memora)
**Ask your own photos and documents questions.** Finds the warranty card, the invoice, the screenshot, and cites the source files for every answer.

Fully local: Gemma models through Ollama, hybrid embedding and FTS5 keyword search in SQLite, with a native Android client over Wi-Fi.

`Python` `FastAPI` `Ollama` `SQLite FTS5` `Kotlin` `Jetpack Compose`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [TrustLayer](https://github.com/Adithya-charan/Trustlayer)
**Role-aware data masking for banking and finance.** Discovers sensitive columns and returns each requester only what their role needs.

Hybrid rule + ML PII detection, backend-enforced policies, an audit trail of every decision, and a multilingual voice assistant over that trail.

`FastAPI` `SQLAlchemy` `PostgreSQL` `React` `LiveKit` `n8n`

</td>
<td width="50%" valign="top">

#### [RecoverAI](https://github.com/Adithya-charan/Recover-Ai)
**Winning back revenue that's slipping away.** Detects failed payments, abandoned checkouts and overdue receivables, then plans a recovery.

ML predicts recovery probability, a LoRA fine-tuned Qwen2.5 recommends the action, and a policy layer authorizes it before execution.

`Python` `FastAPI` `scikit-learn` `Transformers + PEFT` `Razorpay` `React`

</td>
</tr>
</table>

<sub><b>Also built:</b>
<a href="https://github.com/Adithya-charan/janavani">JanaVani</a> (multilingual civic issue reporting) ·
<a href="https://github.com/Adithya-charan/SupportIQ">SupportIQ</a> (autonomous customer support with voice) ·
<a href="https://github.com/Adithya-charan/shopsahayak">ShopSahayak</a> (talk to your shop's data) ·
<a href="https://github.com/Adithya-charan/SwasthyaSetu">SwasthyaSetu</a> (multilingual telemedicine) ·
<a href="https://github.com/Adithya-charan/Chiefos">ChiefOS</a> (AI chief of staff) ·
<a href="https://github.com/Adithya-charan/VyaparSetu">Vyapara Setu</a> (business formalization for entrepreneurs)
</sub>

<br/><br/>

### `03` &nbsp;Stack

<img src="https://raw.githubusercontent.com/Adithya-charan/Adithya-charan/main/assets/stack.svg" alt="Technologies orbiting a glowing core: Python, TypeScript, Kotlin, FastAPI, React, Next.js, PostgreSQL, Ollama, LiveKit, PyTorch, YOLOv8 and Gemini." width="100%" />

<table>
<tr>
<td width="22%"><b>Languages</b></td>
<td>
<img src="https://img.shields.io/badge/Python-0B1020?style=flat-square&logo=python&logoColor=22D3EE" alt="Python" />
<img src="https://img.shields.io/badge/TypeScript-0B1020?style=flat-square&logo=typescript&logoColor=22D3EE" alt="TypeScript" />
<img src="https://img.shields.io/badge/JavaScript-0B1020?style=flat-square&logo=javascript&logoColor=22D3EE" alt="JavaScript" />
<img src="https://img.shields.io/badge/Java-0B1020?style=flat-square&logo=openjdk&logoColor=22D3EE" alt="Java" />
<img src="https://img.shields.io/badge/Kotlin-0B1020?style=flat-square&logo=kotlin&logoColor=22D3EE" alt="Kotlin" />
<img src="https://img.shields.io/badge/SQL-0B1020?style=flat-square&logo=postgresql&logoColor=22D3EE" alt="SQL" />
</td>
</tr>
<tr>
<td><b>AI & ML</b></td>
<td>
<img src="https://img.shields.io/badge/PyTorch-0B1020?style=flat-square&logo=pytorch&logoColor=22D3EE" alt="PyTorch" />
<img src="https://img.shields.io/badge/scikit--learn-0B1020?style=flat-square&logo=scikitlearn&logoColor=22D3EE" alt="scikit-learn" />
<img src="https://img.shields.io/badge/XGBoost-0B1020?style=flat-square" alt="XGBoost" />
<img src="https://img.shields.io/badge/YOLOv8-0B1020?style=flat-square&logo=ultralytics&logoColor=22D3EE" alt="YOLOv8" />
<img src="https://img.shields.io/badge/Hugging%20Face-0B1020?style=flat-square&logo=huggingface&logoColor=22D3EE" alt="Hugging Face" />
<img src="https://img.shields.io/badge/Ollama-0B1020?style=flat-square&logo=ollama&logoColor=22D3EE" alt="Ollama" />
</td>
</tr>
<tr>
<td><b>LLMs & Voice</b></td>
<td>
<img src="https://img.shields.io/badge/Gemini-0B1020?style=flat-square&logo=googlegemini&logoColor=22D3EE" alt="Gemini" />
<img src="https://img.shields.io/badge/Groq-0B1020?style=flat-square" alt="Groq" />
<img src="https://img.shields.io/badge/Qwen-0B1020?style=flat-square" alt="Qwen" />
<img src="https://img.shields.io/badge/LiveKit-0B1020?style=flat-square&logo=webrtc&logoColor=22D3EE" alt="LiveKit" />
<img src="https://img.shields.io/badge/Sarvam%20AI-0B1020?style=flat-square" alt="Sarvam AI" />
</td>
</tr>
<tr>
<td><b>Backend</b></td>
<td>
<img src="https://img.shields.io/badge/FastAPI-0B1020?style=flat-square&logo=fastapi&logoColor=22D3EE" alt="FastAPI" />
<img src="https://img.shields.io/badge/Pydantic-0B1020?style=flat-square&logo=pydantic&logoColor=22D3EE" alt="Pydantic" />
<img src="https://img.shields.io/badge/SQLAlchemy-0B1020?style=flat-square&logo=sqlalchemy&logoColor=22D3EE" alt="SQLAlchemy" />
<img src="https://img.shields.io/badge/Node.js-0B1020?style=flat-square&logo=nodedotjs&logoColor=22D3EE" alt="Node.js" />
<img src="https://img.shields.io/badge/Express-0B1020?style=flat-square&logo=express&logoColor=22D3EE" alt="Express" />
<img src="https://img.shields.io/badge/Spring%20Boot-0B1020?style=flat-square&logo=springboot&logoColor=22D3EE" alt="Spring Boot" />
</td>
</tr>
<tr>
<td><b>Frontend & Mobile</b></td>
<td>
<img src="https://img.shields.io/badge/React-0B1020?style=flat-square&logo=react&logoColor=22D3EE" alt="React" />
<img src="https://img.shields.io/badge/Next.js-0B1020?style=flat-square&logo=nextdotjs&logoColor=22D3EE" alt="Next.js" />
<img src="https://img.shields.io/badge/Vite-0B1020?style=flat-square&logo=vite&logoColor=22D3EE" alt="Vite" />
<img src="https://img.shields.io/badge/Tailwind%20CSS-0B1020?style=flat-square&logo=tailwindcss&logoColor=22D3EE" alt="Tailwind CSS" />
<img src="https://img.shields.io/badge/Jetpack%20Compose-0B1020?style=flat-square&logo=jetpackcompose&logoColor=22D3EE" alt="Jetpack Compose" />
</td>
</tr>
<tr>
<td><b>Data</b></td>
<td>
<img src="https://img.shields.io/badge/PostgreSQL-0B1020?style=flat-square&logo=postgresql&logoColor=22D3EE" alt="PostgreSQL" />
<img src="https://img.shields.io/badge/SQLite-0B1020?style=flat-square&logo=sqlite&logoColor=22D3EE" alt="SQLite" />
<img src="https://img.shields.io/badge/MySQL-0B1020?style=flat-square&logo=mysql&logoColor=22D3EE" alt="MySQL" />
<img src="https://img.shields.io/badge/MongoDB-0B1020?style=flat-square&logo=mongodb&logoColor=22D3EE" alt="MongoDB" />
<img src="https://img.shields.io/badge/Firebase-0B1020?style=flat-square&logo=firebase&logoColor=22D3EE" alt="Firebase" />
</td>
</tr>
<tr>
<td><b>Tooling & Deploy</b></td>
<td>
<img src="https://img.shields.io/badge/Git-0B1020?style=flat-square&logo=git&logoColor=22D3EE" alt="Git" />
<img src="https://img.shields.io/badge/Docker-0B1020?style=flat-square&logo=docker&logoColor=22D3EE" alt="Docker" />
<img src="https://img.shields.io/badge/pytest-0B1020?style=flat-square&logo=pytest&logoColor=22D3EE" alt="pytest" />
<img src="https://img.shields.io/badge/n8n-0B1020?style=flat-square&logo=n8n&logoColor=22D3EE" alt="n8n" />
<img src="https://img.shields.io/badge/Vercel-0B1020?style=flat-square&logo=vercel&logoColor=22D3EE" alt="Vercel" />
<img src="https://img.shields.io/badge/Render-0B1020?style=flat-square&logo=render&logoColor=22D3EE" alt="Render" />
</td>
</tr>
</table>

<br/>

### `04` &nbsp;On the podium

<table>
<tr><th align="left">Event</th><th align="left">Result</th><th align="left">Where · When</th></tr>
<tr><td>Square Hacks, Students Change Initiatives Festival</td><td><b>Best Design</b> · top 30 of 600+ teams</td><td>IIT Delhi · Dec 2025</td></tr>
<tr><td>Systems for Machine Learning 2.0 (SysML 2.0)</td><td><b>Winner</b> · federated learning for edge devices</td><td>IISc Bengaluru, ACM Student Chapter</td></tr>
<tr><td>National Student Change Initiatives Fest 2026</td><td><b>Winner</b> · pitch deck</td><td>Delhi · Mar 2026</td></tr>
<tr><td>NASA International Space Apps Challenge 2025</td><td><b>Best Use of Science</b></td><td>VIT-AP University · Oct 2025</td></tr>
<tr><td>SustainX · SDGs to Startups</td><td><b>Winner</b></td><td>VIT-AP University · 2026</td></tr>
<tr><td>Code Fusion 2026</td><td><b>2nd Place</b></td><td>VR Siddhartha, Vijayawada · Jan 2026</td></tr>
<tr><td>D³ Rewind & Recode, national finale</td><td><b>4th Prize</b> · AI-powered lecture generator</td><td>IIT Bhubaneswar</td></tr>
</table>

<sub>Photos, certificates and write-ups for each event are on my <a href="https://adithyacharanin.vercel.app/#hackathons">portfolio</a>.</sub>

<br/><br/>

### `05` &nbsp;Roles

<table>
<tr><td width="34%"><b>Technical Lead</b><br/><sub>KL-VEDA, KL University · Nov 2025 – present</sub></td><td>Lead a 10+ member team building campus web apps. I own the architecture, sprint planning and code reviews.</td></tr>
<tr><td><b>Member, Web & Software Development</b><br/><sub>Websico · Sep 2025 – present</sub></td><td>Build responsive full-stack apps with React, Node.js and Express.</td></tr>
<tr><td><b>Student Member</b><br/><sub>IEEE Consumer Technology Society · 2026</sub></td><td>Professional membership.</td></tr>
</table>

<br/>

### `06` &nbsp;Activity

<img src="https://raw.githubusercontent.com/Adithya-charan/Adithya-charan/main/profile-3d-contrib/profile-night-rainbow.svg" alt="3D isometric view of Adithya-charan's GitHub contributions over the last year, with language and activity statistics." width="100%" />

<sub>Rebuilt every night by a GitHub Action from my real contribution data. The live record is my <a href="https://github.com/Adithya-charan">contribution graph</a>.</sub>

<br/>

### `07` &nbsp;Current direction

- **Agents with guardrails:** LLM planners paired with deterministic checks, policies and audit trails
- **Retrieval and memory:** grounded answers that cite their sources, and systems that learn from past outcomes
- **Voice in Indian languages:** speech interfaces that work in Telugu, Hindi and English
- **Local-first models:** running open models on my own hardware with Ollama, so private data stays private

<br/>

### `08` &nbsp;Connect

Open to AI engineering roles, internships and research collaborations.

[Portfolio](https://adithyacharanin.vercel.app/) &nbsp;·&nbsp;
[LinkedIn](https://www.linkedin.com/in/adithya-charan-6b7bb138b/) &nbsp;·&nbsp;
[Email](mailto:adityayaramalla@gmail.com) &nbsp;·&nbsp;
[Résumé](https://adithyacharanin.vercel.app/assets/resume/Adithya_Charan_Resume.pdf) &nbsp;·&nbsp;
[Unstop](https://unstop.com/u/yadi80725)

<br/>

<img src="https://raw.githubusercontent.com/Adithya-charan/Adithya-charan/main/assets/footer.svg" alt="AI proposes. Systems verify. People decide." width="100%" />
