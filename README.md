<h1 align="center">Hi 👋, I'm Abhishek Singh</h1>

<h3 align="center">AI Engineer · Generative AI · RAG · Agentic AI</h3>

<p align="center">
  <a href="https://linkedin.com/in/abhi2612"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge" alt="LinkedIn"/></a>
  <a href="mailto:abhisheksinghh2612@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://kaggle.com/abhishek9792"><img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" alt="Kaggle"/></a>
</p>

---

## 🧑‍💻 About Me

I'm an **AI Engineer at Incanus Technologies**, based in **Pune**, where I build GenAI systems for education:

- 💬 **Lecture-grounded RAG chatbot** (LangChain, Whisper, vector DB) that answers student doubts *only* from lecture content, with timestamp links to the exact video moment — **97% grounded answers** across 500+ test queries, with a safe fallback for out-of-scope questions
- 📝 **Multi-agent AI grading workflows** in n8n (extractor → grader → validator) that grade descriptive answers against faculty rubrics — cut evaluation time from **15 to 4 min per paper (~73%)**, saving **25+ faculty hours per exam cycle**
- ✅ Built for trust: rubric-constrained prompts, schema-validated outputs, PII redaction and confidence-based routing to human review — **90% agreement with faculty grades**, with every grading decision logged and auditable

I enjoy taking AI from idea to working product: designing retrieval pipelines, orchestrating multi-step agent workflows with **LangGraph**, and shipping them behind clean **FastAPI** services.

- 🎓 **M.Sc. in Data Science** — IIIT Lucknow
- 🤖 Working on **LLMs, RAG, agentic workflows, computer vision and deep learning**
- 👨‍🏫 Alongside engineering, I teach and mentor **AI and Data Science** (ADYPU Pune, FacePrep) and have mentored **100+ learners**
- 📫 Reach me at **abhisheksinghh2612@gmail.com**

---

## 🚀 Featured Projects

### 🎬 [Multi-Modal Compliance Orchestration Engine](https://github.com/datascientistabhishek/MultiModal-Compliance-Engine)
An AI system that audits **YouTube video ads** for brand and platform compliance.
- Extracts the transcript and on-screen text (OCR) from a video with **Azure Video Indexer**
- Retrieves the relevant rules from guideline documents indexed in **Azure AI Search** (RAG)
- **Azure OpenAI (GPT-4o)** audits the content and returns a **PASS / FAIL report** with each issue's category, severity and description
- Orchestrated as a **LangGraph** workflow, served through a **FastAPI** `/audit` endpoint, with **LangSmith** and **Azure Monitor (OpenTelemetry)** for tracing

`Python` `LangGraph` `FastAPI` `Azure OpenAI` `Azure AI Search` `Azure Video Indexer` `Docker`

### 👄 [Lip Reading AI](https://github.com/datascientistabhishek/Lip-Reading-AI-model)
A deep learning model that predicts spoken sentences from **silent video**, using only lip movements.
- **CNN + BiLSTM + CTC loss** architecture in **PyTorch**, trained on the **GRID corpus** (20 speakers)
- On 5 **unseen speakers**, fine-tuning cut the **Word Error Rate from 0.44 to 0.13** (CER 0.21 → 0.05)
- Full pipeline: OpenCV / ffmpeg preprocessing → training → fine-tuning → evaluation → **Streamlit** app

`Python` `PyTorch` `OpenCV` `Deep Learning` `Streamlit`

### 🧠 [Face Recognition Platform with AI Q&A](https://github.com/datascientistabhishek/Face-recognition_platform)
A browser-based platform that registers faces from a webcam and recognises **multiple faces in real time**.
- **React** frontend and a **Node.js WebSocket** server that streams frames to Python microservices
- **FastAPI** face-recognition service built on **OpenCV**, with face data stored in **SQLite**
- RAG chat assistant (**LangChain + FAISS + Gemini**) that answers questions about registered users

`React` `Node.js` `WebSockets` `FastAPI` `OpenCV` `LangChain` `FAISS` `Gemini`

---

## 🛠️ Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

**Generative AI & LLMs**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langgraph&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-6E40C9?style=flat-square)
![MCP](https://img.shields.io/badge/MCP-191919?style=flat-square)
![Prompt Engineering](https://img.shields.io/badge/Prompt%20Engineering-412991?style=flat-square)

**Machine Learning & Deep Learning**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

**Backend, Cloud & Deployment**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

**Data & Visualization**

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat-square)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square)

**Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat-square)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

---

<p align="center"><i>Open to conversations about AI engineering, GenAI and Data Science roles — feel free to reach out!</i></p>
