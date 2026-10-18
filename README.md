# Hi, I'm Abhishek Lakhani 👋

### Applied AI Engineer · NLP & LLM Systems · M.Sc. student at TU Chemnitz, Germany

<p align="left">
  <a href="https://www.linkedin.com/in/abhishek-lakhani-4896271a6/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://abhisheklakhani-it.github.io/Abhishek-Lakhani/">
    <img src="https://img.shields.io/badge/Portfolio-111827?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio"/>
  </a>
  <a href="mailto:lakhaniabhi.it@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
</p>

I build NLP and LLM systems in Python and **measure them before I trust them**: held-out test sets, standard metrics (nDCG, MRR, F1) and significance tests, then a tested FastAPI service in Docker. Every public project below has real numbers in its README, automated tests that run without API keys, and an honest "limitations" section.

- 🎓 M.Sc. Automotive Software Engineering, TU Chemnitz (master's thesis in preparation: real-time LiDAR health monitoring)
- 🔬 Machine Learning Intern at TU Chemnitz (federated learning across Solid Pods, TensorFlow)
- 💼 **Open to:** working student (Werkstudent), internship, master's thesis and junior roles in Applied AI / ML engineering
- 📍 Chemnitz, open to relocate anywhere in Germany · no visa sponsorship required · English (fluent), German (B1)

---

## 🚀 Featured projects

| Project | What it does | Result |
|:--|:--|:--|
| 📈 [**SmartVisual**](https://www.smartvisual.eu) · *live, anyone can use it; code private* | Upload CSV/Excel, ask in English or German, get KPIs, 18 chart types, maps and short insights. The LLM only interprets the question; every number is computed in code. React, TypeScript, Supabase, Cloudflare Workers | 22-question eval on 3 datasets in CI, **every value within 0.01** of independent answers · [try it](https://www.smartvisual.eu) |
| 🔎 [**RAG Document QA**](https://github.com/abhisheklakhani-it/rag-docqa) | Upload PDFs (also scanned, via OCR), ask questions, get cited answers streamed over SSE. FastAPI, hybrid BM25 + dense retrieval, multi-stage Docker | nDCG@10 **0.728** vs 0.567 for TF-IDF · rejects 87% of off-topic questions · 73 tests |
| 🧭 [**Semantic Search API**](https://github.com/abhisheklakhani-it/semantic-search-api) | Production-style search API: hybrid dense + sparse BM25 in **Qdrant**, optional cross-encoder reranking, filters, pagination, Docker Compose | nDCG@10 **0.737** (dense alone 0.715) · reranker benchmarked and kept off · 33 tests |
| ⚡ [**ONNX Inference Optimization**](https://github.com/abhisheklakhani-it/onnx-inference-optimization) | Fine-tuned German DistilBERT exported to ONNX, fused and int8-quantized, served by FastAPI | **1.46×** PyTorch throughput · **4×** smaller · −0.3 pt accuracy · 147 MB image |
| 🇩🇪 [**German Text Classifier**](https://github.com/abhisheklakhani-it/german-text-classifier) | German news topics (10kGNAD): embeddings + Qdrant kNN baseline vs fine-tuned DistilBERT | macro-F1 **0.897** vs 0.845 · McNemar p < 0.001 |
| 🧾 [**LLM Structured Extractor**](https://github.com/abhisheklakhani-it/llm-structured-extractor) | Messy EN/DE job postings → validated JSON with Pydantic, retry on validation errors, field-level evaluation | all-fields-correct on held-out set **0.40 → 0.67** · 43 tests |
| 📊 [**Retrieval Eval Bench**](https://github.com/abhisheklakhani-it/retrieval-eval-bench) | TF-IDF vs BM25 vs dense (FAISS) vs hybrid retrieval on BEIR SciFact, train/test split, paired significance tests | hybrid nDCG@10 **0.734** (p = 0.013) |
| 🏭 [**Test Bench Commissioning App**](https://github.com/abhisheklakhani-it/n8n-test-bench-commissioning-tracker) | Role-based web app for test-bench commissioning with priority notifications and a shop-floor tablet mode; grew out of an n8n prototype | FastAPI · PostgreSQL · Docker · CI · **137 tests** · [live demo](https://test-bench-commissioning.onrender.com) |
| ✍️ [**LinkedIn Post Generator**](https://github.com/abhisheklakhani-it/linkedin-post-generator) | Few-shot LangChain app, EN/DE posts as validated structured output, flags numbers the user never gave | Streamlit UI · 34 tests |

---

## 🛠️ Tech I have used in the projects above

**Languages:** Python · SQL · JavaScript / TypeScript

**LLM & NLP:** LLMs · prompt engineering · structured outputs · RAG · LangChain · Hugging Face Transformers · fine-tuning · sentence embeddings · text classification

**Search:** Qdrant · FAISS · BM25 · TF-IDF · hybrid search (RRF) · cross-encoder reranking

**ML:** PyTorch · TensorFlow · scikit-learn · pandas · NumPy · evaluation (nDCG, MRR, recall@k, F1, significance tests)

**Backend & MLOps:** FastAPI · Pydantic · Docker / Compose · ONNX Runtime · quantization · pytest · GitHub Actions · SQLAlchemy · PostgreSQL · Streamlit · n8n

**Web & deployment:** React · Next.js · TypeScript · Supabase · Prisma · Playwright · Cloudflare Workers · Vercel · Render

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX_Runtime-005CED?style=flat-square&logo=onnx&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)

---

## 💼 Experience

- **Machine Learning Intern**, Technische Universität Chemnitz · 06/2025 – 01/2026
  Privacy-focused image classification in TensorFlow with federated learning across decentralised Solid Pod data sources; reproducible Python experiment tooling.
- **Software Development Intern**, Wokontech IT Solution, India · 10/2021 – 03/2022
  Object detection pipelines on 5,000+ images, data curation, evaluation, annotation workflow in CVAT.
- **Backend Development Intern**, White Orange Software, India · 12/2020 – 05/2021
  Backend features in Core PHP, MySQL query tuning, code reviews and documentation.

## 🎓 Education

- **M.Sc. Automotive Software Engineering**, Technische Universität Chemnitz · since 04/2022
- **B.E. Computer Science and Engineering**, Gujarat Technological University · 2017 – 2021

---

📫 The fastest way to reach me is [e-mail](mailto:lakhaniabhi.it@gmail.com) or [LinkedIn](https://www.linkedin.com/in/abhishek-lakhani-4896271a6/). My resume is on my [portfolio](https://abhisheklakhani-it.github.io/Abhishek-Lakhani/).
