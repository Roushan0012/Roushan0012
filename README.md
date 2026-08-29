<!-- 🏁 Custom Banner -->
<p align="center">
  <a href="https://github.com/Roushan0012">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&center=true&vCenter=true&width=650&lines=AI%2FML+Engineer+%7C+Generative+AI+%2B+Agentic+Systems;LangGraph+%2B+LangChain+%7C+RAG+Architect;B.Tech+CSE+%40+IIIT+Bhagalpur+%F0%9F%8E%93;700%2B+DSA+%26+CP+Problems+Solved+%E2%9A%99%EF%B8%8F" alt="Typing SVG" />
  </a>
</p>

<h1 align="center">Hi 👋, I'm Roushan Kumar</h1>
<h3 align="center">AI/ML Engineer &middot; Generative AI, RAG &amp; Agentic LLM Systems &middot; B.Tech CSE @ IIIT Bhagalpur</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/roushan-kumar-b7b7a9296">LinkedIn</a> ·
  <a href="https://github.com/Roushan0012">GitHub</a> ·
  <a href="mailto:roushan.230101106@iiitbh.ac.in">College Email</a> ·
  <a href="mailto:kashyaproushankumar@gmail.com">Personal Email</a>
</p>

<table>
<tr>
<td width="370" valign="top">
  <img src="./avi-ascii.svg" width="370" alt="Roushan ASCII Portrait" />
</td>
<td width="490" valign="top">
  <img src="./info-card.svg" width="490" alt="Info Card" />
</td>
</tr>
</table>

<p align="center">
  <img src="./contrib-heatmap.svg" width="100%" alt="Contribution Heatmap" />
</p>

<p align="center"><sub>Contribution graph refreshes daily via GitHub Actions — no token, no auth.</sub></p>

---

## 🚀 About Me

- 🎓 Pursuing **B.Tech in Computer Science and Engineering** at **Indian Institute of Information Technology, Bhagalpur** (CGPA: 7.76 / 10 | 2023 – Expected May 2027).
- 🤖 **AI/ML Engineer** specializing in Generative AI, Retrieval-Augmented Generation (RAG), and autonomous agentic LLM systems in Python.
- 🛠️ Shipped **production AI applications** and solved **700+ Data Structures & Algorithms and Competitive Programming problems**.
- 💼 Former **AI Developer Intern** at **AI Ally** (Remote) — engineered conversational speech-to-JSON pipelines, LangChain tool-calling, and fault-tolerant REST integrations.
- 🏆 **2nd Rank** at IDEA-ONE National Health Hackathon (ICMR Bhubaneswar) & **National Finalist** at AI HealthTech Grand Finale, Bharat Mandapam.
- 📧 Reach me at: **roushan.230101106@iiitbh.ac.in** / **kashyaproushankumar@gmail.com**

---

## 💼 Experience

**AI Developer Intern (Remote)** — AI Ally  
<sub>May 2025 – Aug 2025</sub>
- Developed Python data-processing pipelines converting unstructured speech and text into structured JSON, integrating OpenAI Whisper and LangChain to reach **98% intent-classification accuracy**.
- Engineered 3 LangChain tool-calls for real-time database querying, letting the agent verify live pricing across **200+ catalog items** and eliminate out-of-stock ordering errors.
- Integrated AI modules with backend REST components over reusable JSON interfaces, hardened by a **3-layer guard** of input validation, response parsing, and exception handling for inconsistent model output.

---

## 🚀 Featured Projects

### 🧠 **[CognitRAG.ai — Enterprise PDF Hybrid RAG Intelligence Platform](https://github.com/Roushan0012/CognitRAG.ai)**
`Python` · `Flask` · `React 18` · `FAISS` · `BM25Okapi` · `Hugging Face (MiniLM)` · `Groq LPU` · `SSE Streaming`
- Built a **6-stage hybrid retrieval pipeline** pairing 384-dimensional FAISS dense vectors with BM25 sparse keyword search, fusing top-15 candidates via Reciprocal Rank Fusion ($k=60$) to maximize recall.
- Optimized precision using a **MiniLM cross-encoder reranker** (narrowing 15 fused candidates to 5), resolving 300-character child chunks to 1200-character parent context blocks for factual generation.
- Streamed low-latency answers token-by-token over **Server-Sent Events (SSE)** from a Flask REST API to a React 18 frontend with per-passage relevance scores and page-level citations.

---

### 🚆 **[roushan-railfreight — Railway Commodity Reservation System (Freight IRCTC)](https://github.com/Roushan0012/roushan-railfreight)**
`Next.js 14` · `React` · `TypeScript` · `Supabase (PostgreSQL)` · `Tailwind CSS` · `Row-Level Security (RLS)` · `ACID Transactions`
- Engineered a production-grade B2B freight slot booking platform on dedicated rail corridors with multi-tenant organization onboarding, cargo classification multipliers, and dynamic distance-based pricing.
- Implemented transactional Postgres RPCs (`book_slot_atomic`, `cancel_booking_atomic`) with `FOR UPDATE` row-level locks on schedules, enforcing atomic capacity guarantees and zero-overselling invariants.
- Built an interactive DFCCIL network controller operations dashboard for route scheduling, transit tracking, and automated electronic consignment receipt generation.

---

### 🔥 **[Forest Weather Index (FWI) Prediction](https://github.com/Roushan0012/Forest_Weather_Index_Prediction)**
`Python` · `Flask` · `Scikit-learn` · `Pandas` · `NumPy` · `Ridge/Lasso Regression` · `AWS Elastic Beanstalk`
- Developed an end-to-end machine learning pipeline analyzing meteorological indices (FFMC, DMC, DC, ISI, BUI) from the Algerian Forest Fires dataset to predict Fire Weather Index values.
- Conducted exploratory data analysis, correlation filtering, and feature scaling, evaluating multiple regularized linear models (Ridge, Lasso, ElasticNet) with cross-validation.
- Packaged the inference pipeline into an interactive Flask web application and automated cloud deployment on AWS Elastic Beanstalk.

---

### 🗺️ **[Smart Agentic AI Travel Planner](https://github.com/Roushan0012)**
`Python` · `LangGraph` · `LangChain` · `FastAPI` · `Streamlit` · `Docker`
- Architected an agentic workflow on **LangGraph using a StateGraph with conditional routing**, letting one LLM node autonomously select and re-invoke 4 Python tools until a complete itinerary is produced.
- Implemented weather, place-search, currency-conversion, and arithmetic tools via LLM tool-calling and split the system into a **FastAPI service and Streamlit client** across 8 modular Python packages.

---

### 🏛️ **[Samadhan — AI Civic Issue Reporting Portal](https://github.com/Roushan0012)**
`Flask` · `GPT-4o Vision` · `React` · `TypeScript` · `Multilingual NLP`
- Designed a scalable Flask REST backend exposing 3 endpoints that route citizen photos to **GPT-4o Vision** and return structured JSON with issue title, category, description, and priority in a single call.
- Constrained model output to 7 civic categories using a 3-stage normalizer and a 2-check moderation route, and shipped a **React 18 and TypeScript client** supporting 5+ Indian languages and 3 report states.

---

### 📦 **[ParcelPilot — AI Operations Copilot](https://github.com/Roushan0012)**
`React` · `Next.js` · `FastAPI` · `Node.js` · `PostgreSQL (Supabase)` · `LangChain`
- Built a full-stack AI agent application for real-time policy reasoning and operational queries across contracts, policies, and operational records with role-based access control.
- Collaborated across 5+ development phases, validating modules through unit and integration testing before deployment — reducing manual lookup time for complex queries from 10 minutes to under 15 seconds (**97% improvement**).

---

## 🧰 Technical Arsenal

<p align="center">
  <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=18&pause=1000&center=true&vCenter=true&width=520&lines=AI+%2F+ML+Engineer;LangGraph+%2B+LangChain+%7C+RAG;B.Tech+CSE+%40+IIIT+Bhagalpur" alt="typing banner" />
</p>

<p align="center"><sub><b>Languages</b></sub></p>
<p align="center">
  <img src="https://skillicons.dev/icons?i=python,cpp,c,js,ts,html,css" alt="languages" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="SQL" />
</p>

<p align="center"><sub><b>AI & Machine Learning</b></sub></p>
<p align="center">
  <img src="https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn" alt="ML Frameworks" />
  <img src="https://img.shields.io/badge/Generative_AI-FF6F00?style=for-the-badge&logo=openai&logoColor=white" alt="GenAI" />
  <img src="https://img.shields.io/badge/Deep_Learning-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="Deep Learning" />
  <img src="https://img.shields.io/badge/Transformers-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Transformers" />
  <img src="https://img.shields.io/badge/NLP_%26_CV-4B8BBE?style=for-the-badge" alt="NLP & CV" />
</p>

<p align="center"><sub><b>LLM & Agentic AI</b></sub></p>
<p align="center">
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain" />
  <img src="https://img.shields.io/badge/LangGraph-0A0A0A?style=for-the-badge&logoColor=white" alt="LangGraph" />
  <img src="https://img.shields.io/badge/LangSmith-FF9900?style=for-the-badge" alt="LangSmith" />
  <img src="https://img.shields.io/badge/RAG_Pipelines-005571?style=for-the-badge" alt="RAG" />
  <img src="https://img.shields.io/badge/FAISS_Vector_DB-0064a5?style=for-the-badge" alt="FAISS" />
  <img src="https://img.shields.io/badge/Prompt_Engineering-375BD2?style=for-the-badge" alt="Prompt Engineering" />
  <img src="https://img.shields.io/badge/Ollama-FFFFFF?style=for-the-badge&logo=ollama&logoColor=black" alt="Ollama" />
</p>

<p align="center"><sub><b>Backend & Web Development</b></sub></p>
<p align="center">
  <img src="https://skillicons.dev/icons?i=fastapi,flask,nodejs,react,nextjs,tailwind" alt="backend and frontend" />
  <img src="https://img.shields.io/badge/REST_APIs-005571?style=for-the-badge" alt="REST APIs" />
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" alt="Streamlit" />
  <img src="https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white" alt="Pydantic" />
  <img src="https://img.shields.io/badge/Microservices-333333?style=for-the-badge" alt="Microservices" />
</p>

<p align="center"><sub><b>Databases</b></sub></p>
<p align="center">
  <img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,supabase" alt="databases" />
</p>

<p align="center"><sub><b>Cloud, DevOps & Data Tools</b></sub></p>
<p align="center">
  <img src="https://skillicons.dev/icons?i=docker,aws,linux,git,github,vercel" alt="devops" />
  <img src="https://img.shields.io/badge/GitHub_Actions_CI%2FCD-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy" />
  <img src="https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white" alt="pytest" />
</p>

<p align="center"><sub><b>Core Computer Science Concepts</b></sub></p>
<p align="center">
  <img src="https://img.shields.io/badge/Data_Structures_%26_Algorithms-3B82F6?style=for-the-badge" alt="DSA" />
  <img src="https://img.shields.io/badge/OOP-10B981?style=for-the-badge" alt="OOP" />
  <img src="https://img.shields.io/badge/DBMS-8B5CF6?style=for-the-badge" alt="DBMS" />
  <img src="https://img.shields.io/badge/Operating_Systems-F59E0B?style=for-the-badge" alt="OS" />
  <img src="https://img.shields.io/badge/Computer_Networks-EC4899?style=for-the-badge" alt="CN" />
  <img src="https://img.shields.io/badge/System_Design-6366F1?style=for-the-badge" alt="System Design" />
  <img src="https://img.shields.io/badge/Agile-0052CC?style=for-the-badge" alt="Agile" />
</p>

---

## 🏅 Achievements & Leadership

- 🧩 **Competitive Programming & DSA**: Solved **400+ DSA problems on LeetCode** (Rating 1753) and **300+ / 350+ competitive programming challenges on Codeforces and CodeChef**.
- 🏆 **AI HealthTech National Grand Finale Finalist**: Qualified for the National Grand Finale at **Bharat Mandapam, New Delhi**, outperforming 500+ teams nationwide *(Nov 2025)*.
- 🥈 **2nd Rank at IDEA-ONE National Health Hackathon**: Secured 2nd Rank (Regional Round – ICMR Bhubaneswar) against **1000+ teams in 24 hours** *(Oct 2025)*.
- 🌟 **Event Lead & Organiser | IGNITIA (Freshers 2K24)**: Managed budgeting, resource allocation, and logistics for **500+ participants** with 10+ sponsors and vendors *(Oct 2024)*.

---

## 📜 Certifications

- 🏆 **ServiceNow Certified System Administrator (CSA)** — ServiceNow *(Jun 2026)*
- 🏆 **ServiceNow Certified Application Developer (CAD)** — ServiceNow *(Jun 2026)*
- 🤖 **Supervised Machine Learning: Regression and Classification** — DeepLearning.AI / Andrew Ng on Coursera *(May 2024)*