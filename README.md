# Sohan Kumar Anumalasetty

CS @ IIITDM Kancheepuram · CGPA 9.14 · Building at the intersection of ML systems and backend engineering.

Interned at **Dhruva Space**, where I built the geospatial pipeline that finds valid observation windows across a 50-satellite constellation, cutting invalid scheduling by 94%.  
Interned at **O.C. Tanner**, where I built a GitHub audit tool automating SOC 2 compliance checks across 1000+ repos, cutting audit time from hours to under 3 minutes.

Hit me up → asohankumar34@gmail.com

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white&style=for-the-badge)](https://www.linkedin.com/in/sohan-kumar-anumalasetty/)
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Sohanuu66)
[![LeetCode](https://img.shields.io/badge/LeetCode%20350+-FFA116?logo=leetcode&logoColor=black&style=for-the-badge)](https://leetcode.com/u/sohanuuu/)
[![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white&style=for-the-badge)](mailto:asohankumar34@gmail.com)

---

## What I'm building

**[Loom](https://github.com/Sohanuu66/Loom)** — Agentic AI email orchestration system. LangGraph StateGraph drives multi-step reasoning over Gmail, streaming live tool-selection and execution steps to the frontend via SSE. Two-layer guardrail system (Intent Gate + Output Guard) validated by a LangSmith-traced custom eval suite. Dual OAuth architecture (Supabase Identity + Google OAuth) for secure multi-inbox connections. *In progress.*

`Python` `FastAPI` `LangGraph` `OpenAI` `Supabase` `LangSmith` `OAuth 2.0`

---

## Projects

**[Agentic RAG Document Intelligence System](https://github.com/Sohanuu66/Agentic-RAG)** — FastAPI RAG pipeline with hybrid retrieval (dense ChromaDB/FAISS + sparse BM25, fused via Reciprocal Rank Fusion) and cross-encoder reranking. An LLM-driven orchestrator agent dynamically routes each query between cached-evidence reuse, retrieval, and generation. Citation-grounded answers validated by an NLI-based hallucination detector and a RAGAS eval suite. Autonomous web-search fallback (Tavily) for low-confidence retrieval, with SQLite-backed session memory across multi-turn conversations.

`Python` `FastAPI` `ChromaDB` `FAISS` `OpenAI` `RAGAS` `Tavily`

---

**[Sentinel-EC — Fraud Detection Platform](https://github.com/Sohanuu66/Sentinel-EC)** — End-to-end fraud detection pipeline on the IEEE-CIS dataset (590K transactions, 431 features, 28:1 class imbalance). CatBoost with 5-fold time-based CV hit 0.902 ROC-AUC / 0.437 PR-AUC, with MLflow-tracked threshold calibration. Deployed as a FastAPI inference service supporting real-time and batch scoring, containerized with Docker, with an AWS S3-backed model registry.

`Python` `FastAPI` `CatBoost` `MLflow` `MongoDB Atlas` `Docker` `AWS S3`

---

**[TRAFIX — Traffic Operations Intelligence Platform](https://github.com/harshinis30/Flipkart-Gridlock)** — Full-stack traffic incident platform (FastAPI + React) built at Flipkart Gridlock 2.0. A Random Forest classifier predicts road-closure probability and generates composite severity scores. A TF-IDF + cosine similarity engine retrieves the top-3 similar past incidents from 8,173 historical events to inform dispatcher response, with an automated feedback pipeline that retrains the model on post-incident outcomes.

`Python` `FastAPI` `scikit-learn` `React` `Vite` `Leaflet`

---

## Current Focus

- Agentic workflows and production RAG pipelines
- LLM evals and observability
- Backend architecture and system design at scale
- ML systems — inference, deployment, and monitoring

---

## Tech Stack

### Languages
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)

### AI / Agentic Systems
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langgraph&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)

### Backend & Infrastructure
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)

### ML / AI
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white)
![mlflow](https://img.shields.io/badge/mlflow-%23d9ead3.svg?style=for-the-badge&logo=numpy&logoColor=blue)

### Databases
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/postgresql-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)

---

## GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.shion.dev/api?username=Sohanuu66&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" height="165"/>
  <img src="https://github-readme-stats.shion.dev/api/top-langs/?username=Sohanuu66&theme=tokyonight&hide_border=true&layout=compact" height="165"/>
</p>
