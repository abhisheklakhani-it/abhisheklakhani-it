# Hi there, I'm Abhishek Lakhani 👋

### AI / ML Engineer | LLMs, RAG & Machine Learning Systems

<p align="left">
  <a href="https://www.linkedin.com/in/abhishek-lakhani-4896271a6/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://github.com/abhisheklakhani-it">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
  <a href="https://abhisheklakhani-it.github.io/Abhishek-Lakhani/">
    <img src="https://img.shields.io/badge/Portfolio-111827?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio"/>
  </a>
</p>

---

## 👨‍💻 About Me

I'm an **AI / ML Engineer** focused on building practical machine-learning and LLM applications — especially **RAG systems, information retrieval, NLP, evaluation, and production-oriented Python services**.

I'm currently completing my **M.Sc. in Automotive Software Engineering at TU Chemnitz, Germany**, with a background spanning machine learning, computer vision, backend development, and privacy-aware ML research.

I like working where **ML research meets software engineering**: measurable experiments, reproducible pipelines, clean APIs, testing, containerization, and systems that can actually be used.

- 🧠 **Focus:** LLMs, RAG, information retrieval, NLP, deep learning
- 🔎 **Retrieval:** TF-IDF, BM25, dense embeddings, FAISS, hybrid search
- 🧪 **ML engineering:** evaluation, experiment design, metrics, statistical testing
- ⚙️ **Backend:** Python, FastAPI, REST APIs, Docker
- 🔐 **Research:** privacy-preserving / decentralized machine learning
- 🚗 **Domain:** Automotive Software Engineering
- 💼 **Open to:** AI/ML Engineer, Applied AI, RAG/LLM, ML Engineer, Data/AI internships, working-student and thesis opportunities
- 📍 **Germany**

---

## 🛠️ Tech Stack

### Languages

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

### AI / ML

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LLMs](https://img.shields.io/badge/LLMs-8A2BE2?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-6D28D9?style=flat-square)
![FAISS](https://img.shields.io/badge/FAISS-Vector_Search-0467DF?style=flat-square)
![Sentence Transformers](https://img.shields.io/badge/Sentence--Transformers-FFD21E?style=flat-square)

### Backend / Data / MLOps

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![PyTest](https://img.shields.io/badge/PyTest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)

### Web / Cloud

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)

---

## 🚀 Featured Projects

### 🔎 [RAG DocQA](https://github.com/abhisheklakhani-it/rag-docqa)

**Production-style document question answering system with hybrid retrieval**

- FastAPI service with **BM25 + dense vector + TF-IDF retrieval**
- **BGE-small / FAISS** semantic retrieval
- PDF, Markdown and text ingestion with **OCR for scanned PDFs**
- Streaming LLM responses through **Server-Sent Events**
- Retrieval evaluation with **Recall@k, MRR and nDCG@10**
- Dockerized with a multi-stage build
- **73 automated tests** covering retrieval, streaming, OCR, APIs and evaluation

### 📊 [Retrieval Eval Bench](https://github.com/abhisheklakhani-it/retrieval-eval-bench)

**Benchmarking retrieval strategies for RAG systems**

- Compares **TF-IDF, BM25, dense embeddings and hybrid retrieval**
- Evaluated on the **SciFact / BEIR** dataset
- Separate train/test evaluation for parameter tuning
- Measures **Recall@1/5/10, MRR@10 and nDCG@10**
- Includes **paired randomization tests** and bootstrap confidence intervals
- Examines where lexical, semantic and hybrid retrieval succeed or fail

### ✍️ [LinkedIn Post Generator](https://github.com/abhisheklakhani-it/linkedin-post-generator)

**LLM-powered content generation application**

- Built with **LangChain, Streamlit and Pydantic**
- Few-shot example selection based on tone, language and length
- Structured JSON output with validation
- Grounding checks for unsupported numbers
- **English / German** output with configurable LLM providers
- **34 automated tests**

### 🤖 [ML Project](https://github.com/abhisheklakhani-it/mlproject)

End-to-end machine-learning project covering data preparation, model training and evaluation.

### 🐦 [Bird Species Classifier](https://github.com/abhisheklakhani-it/bird_species_classifier)

Computer-vision classification project focused on image-based machine learning.

### 💳 [Spendly](https://github.com/abhisheklakhani-it/spendly)

Personal-finance application focused on expense tracking and budgeting.

### 🌐 [Portfolio](https://github.com/abhisheklakhani-it/Abhishek-Lakhani)

Current portfolio built with **React, TypeScript, Vite, Tailwind CSS, Framer Motion and Three.js**, with GitHub-project integration and automated GitHub Pages deployment.

---

## 🔬 Research & Engineering Interests

- **Retrieval-Augmented Generation (RAG)**
- **Information Retrieval & Search**
- **LLM application engineering**
- **NLP & text classification**
- **Computer Vision**
- **Evaluation & benchmarking**
- **Privacy-preserving / decentralized ML**
- **MLOps and reproducible ML systems**
- **AI applications for automotive and intelligent systems**

---

## 💼 Experience

### Machine Learning Intern — TU Chemnitz

Worked on privacy-focused machine learning experiments involving **decentralized data sources / Solid Pods**, image classification and reproducible Python pipelines.

### Software Development Intern — Wokontech IT Solution

Worked on computer-vision / object-detection workflows, dataset preparation and model evaluation.

### Backend Development Intern — White Orange Software

Worked on backend development with **Core PHP and MySQL**, including implementation, query optimisation and documentation.

---

## 🎓 Education

**M.Sc. Automotive Software Engineering**  
Technische Universität Chemnitz, Germany · 2022 – Present

**B.E. Computer Science Engineering**  
Gujarat Technological University, India · 2017 – 2021

---

## 🌐 Portfolio & Contact

<p>
  <a href="https://abhisheklakhani-it.github.io/Abhishek-Lakhani/">🌐 Portfolio</a> ·
  <a href="https://www.linkedin.com/in/abhishek-lakhani-4896271a6/">💼 LinkedIn</a> ·
  <a href="mailto:lakhaniabhi.it@gmail.com">📧 Email</a>
</p>

---

## 📌 Current Direction

I'm currently focused on **AI engineering roles involving LLMs, RAG, information retrieval, machine learning and production-oriented Python systems**.

I especially enjoy projects where the goal is not only to build a model, but to **measure it, test it, deploy it and understand its real-world behaviour**.
