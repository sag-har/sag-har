<div align="center">

<!-- Animated Header -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=28&pause=1000&color=6E57F7&center=true&vCenter=true&width=700&lines=Saghar+Mehmood;AI+%2F+ML+Engineer;Computer+Vision+%7C+NLP+%7C+RAG+Systems;BS+Artificial+Intelligence" alt="Typing SVG" />
</a>

<br/>

<img src="https://komarev.com/ghpvc/?username=sagharmehmood&label=Profile+Views&color=6E57F7&style=flat-square" alt="Profile views" />
&nbsp;
<a href="https://linkedin.com/in/sagharmehmood">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" />
</a>
&nbsp;
<a href="mailto:sagharmehmood@email.com">
  <img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" />
</a>
&nbsp;
<img src="https://img.shields.io/badge/Location-Islamabad%2C%20Pakistan-6E57F7?style=flat-square&logo=googlemaps&logoColor=white" />

</div>

---

## About Me

I'm an AI/ML engineer with a BS in Artificial Intelligence from PMAS Arid Agriculture University Rawalpindi (2026). My work spans computer vision, signal processing, NLP, and retrieval-augmented generation — with hands-on experience building end-to-end AI pipelines from data preprocessing through deployment.

My final year project involved multimodal deception detection — integrating EEG signals, facial video, and audio into a single inference system. I'm currently deepening my knowledge of LLM pipelines, vector search, and cloud-based ML deployment.

**Areas of focus:** Machine Learning · Computer Vision · NLP · RAG Systems · Backend AI Applications

---

## Technical Skills

**Languages & Frameworks**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)

**ML / AI Libraries**

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-017CEE?style=flat-square&logo=xgboost&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

**Specialized Libraries**

![DeepFace](https://img.shields.io/badge/DeepFace-4B0082?style=flat-square&logoColor=white)
![Librosa](https://img.shields.io/badge/Librosa-FF4B4B?style=flat-square&logoColor=white)
![MNE](https://img.shields.io/badge/MNE--Python-00897B?style=flat-square&logoColor=white)

**Backend & APIs**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)

**Frontend & Mobile**

![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=flat-square&logo=react&logoColor=black)

**Data & Infrastructure**

![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)

---

## Featured Projects

### Multimodal Lie Detection System
`FYP · 2025–2026`

**Problem:** Existing deception detection approaches rely on a single data source (e.g., facial expressions alone), which limits reliability across subjects and conditions.

**Approach:** Built a three-modality pipeline that fuses EEG signals, facial video, and audio into a single inference system. Each modality is processed independently before a late-fusion layer produces a combined classification output.

**Technologies:** Python · XGBoost · TensorFlow · BiLSTM · OpenCV · DeepFace · Librosa · Flask · React Native · SQL Server · FFmpeg

**Key Contributions:**
- Designed the EEG feature extraction pipeline using Muse 2 hardware, extracting band power features (alpha, beta, theta, delta) for XGBoost classification
- Integrated DeepFace for action unit detection and trained a BiLSTM on facial feature sequences for temporal classification
- Built a 96-feature audio pipeline using Librosa (MFCCs, pitch, spectral features) with XGBoost classifier
- Developed the Flask REST API and a React Native mobile client to orchestrate session management, file uploads, and result display
- Resolved system-level issues including multipart upload boundary corruption, Flask upload size limits, and feature vector mismatches across modalities

**Results:** EEG modality: 78% accuracy on test set. Audio modality: 74% accuracy. Video modality: 93% accuracy on held-out evaluation data.

---

### DocuMind AI — RAG Document Q&A System
`Personal Project`

**Problem:** Querying large document collections with keyword search returns low-relevance results and requires users to manually locate relevant sections.

**Approach:** Built a retrieval-augmented generation system that chunks and embeds documents into a vector database, enabling semantic search followed by LLM-based answer generation over retrieved context.

**Technologies:** Python · LangChain · FastAPI · Vector Database (FAISS / Chroma) · PDF parsing libraries · OpenAI API

**Key Contributions:**
- Built the document ingestion pipeline: PDF parsing, chunking with overlap, embedding generation, and vector store indexing
- Designed the retrieval layer with similarity search and context window management for LLM prompting
- Developed a FastAPI backend exposing query and document upload endpoints
- Handled edge cases including scanned PDFs, multi-section documents, and long-context truncation

**Outcome:** End-to-end pipeline supporting semantic Q&A over uploaded PDFs with source-grounded responses.

---

### JobSense AI — Resume-to-Job Matching System
`Personal Project`

**Problem:** Job seekers and recruiters spend significant time manually comparing resumes against job descriptions, with inconsistent results.

**Approach:** Built an NLP pipeline that parses resumes and job postings, extracts structured entities (skills, experience, qualifications), and scores candidate-job compatibility.

**Technologies:** Python · NLP (spaCy / HuggingFace) · Scikit-Learn · FastAPI

**Key Contributions:**
- Developed resume parsing logic for unstructured text (PDF/DOCX) into structured fields
- Built entity extraction pipeline to identify skills, job titles, and experience from free text
- Implemented a similarity-based matching layer to rank candidates against job requirements

---

### Vehicle Detection and Traffic Analytics System
`Academic Project`

**Problem:** Manual traffic monitoring is time-intensive and does not scale for real-time or multi-lane environments.

**Approach:** Built an OpenCV-based pipeline for detecting and tracking vehicles in video footage, with downstream analytics on traffic volume and flow patterns.

**Technologies:** Python · OpenCV · NumPy · Object detection (YOLO / background subtraction)

**Key Contributions:**
- Implemented frame-by-frame vehicle detection using a pre-trained detection model
- Built a tracking module using centroid-based tracking across frames
- Aggregated per-frame detections into traffic analytics (vehicle count, speed estimation, lane distribution)

---

## Education

**BS Artificial Intelligence**
PMAS Arid Agriculture University Rawalpindi · Graduated May 2026

Coursework: Machine Learning · Deep Learning · Computer Vision · Natural Language Processing · Signal Processing · Database Systems · Software Engineering

---

## Currently Learning

```
├── LangChain / LlamaIndex — advanced RAG pipeline patterns
├── Cloud ML deployment — AWS SageMaker / GCP Vertex AI basics
├── Vector databases — Pinecone, Weaviate, Qdrant
├── FastAPI — production patterns, async endpoints, dependency injection
└── MLOps fundamentals — experiment tracking, model versioning (MLflow)
```

---

## GitHub Stats

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=sagharmehmood&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&rank_icon=github" />
&nbsp;&nbsp;
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sagharmehmood&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" />

</div>

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=sagharmehmood&theme=tokyonight&hide_border=true" />

</div>

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=sagharmehmood&theme=tokyo-night&hide_border=true&area=true" />

</div>

---

## Contact

I'm open to AI/ML Engineer, Machine Learning Engineer, and Backend AI Developer roles in Islamabad/Rawalpindi — and remote positions.

| | |
|---|---|
| **Email** | sagharmehmood@email.com |
| **LinkedIn** | [linkedin.com/in/sagharmehmood](https://linkedin.com/in/sagharmehmood) |
| **Location** | Islamabad, Pakistan |

---

<div align="center">
  <sub>Updated June 2026</sub>
</div>
