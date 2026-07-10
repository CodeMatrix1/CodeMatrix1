<h1 align="center">Hi, I'm Manyam Srivallabh 👋</h1>

<p align="center">
  <b>Pre-Final Year at IIT Madras · Quant Finance + Materials Engineering (Dual Degree)</b>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/srivallabh-manyam-7a1033298/">LinkedIn</a> ·
  <a href="mailto:mm23b049@smail.iitm.ac.in">Email</a>
</p>

---

## About Me

- Pre-final year student at IIT Madras with a strong interest in AI/ML and full-stack development. I enjoy building things at the intersection of software engineering and GenAI — particularly when large-scale AI integrations change the way users interact with applications. Still early in the journey, but actively exploring full-stack development, ML, RAG, NLP, and agentic systems through projects and internships.
---

## Experience

**`RAG & GenAI Intern`**
Tecnod8.ai · Sep 2025 – Nov 2025
- Built production RAG pipelines using hierarchical chunking, late chunking, and HyDE for improved retrieval on enterprise documents.
- Developed a multilingual document layout extractor combining DocLayout-YOLO, PaddleOCR, and VLM refinement for accurate region detection on complex PDFs.
- Ranked **top 13 out of 150+ teams** in the NCIIPC Grand Challenge RAG track.

**`AI & Software Engineering Intern`**
Genius Labs · May 2025 – Jul 2025
- Built the front-end UI of an AI-powered exam preparation web app using Next.js, handling component architecture and workflow design.
- Designed a scalable test-management framework integrating question generation, participation, and evaluation workflows.
- Engineered student dashboard and workflows for an AI-based doubt-solver and talking-PPT module.

---

## Competitions

**IMC Prosperity 2025** — Algorithmic Trading Challenge
- Ranked **#69 globally and #10 nationally** among ~9,000 teams. Built quantitative strategies including Pairs Trading, Market Making, Statistical Arbitrage, and Trend Following across a 15-day simulation.

**WorldQuant IQC 2025** — International Quant Championship
- Qualified for **Round 2**, ranked **#11,597 out of 88,000+** participants worldwide.

**NCIIPC Grand Challenge** — RAG Track (Tecnod.ai)
- Ranked **top 13 out of 150+ teams** in a national cybersecurity-focused RAG evaluation challenge. Built during internship at Tecnod8.ai.

**Google Summer of Code 2026** — Rocket.Chat
- Submitted a proposal for the "Minimal MCP Generator" project — an agentic system that auto-generates lightweight MCP servers exposing task-relevant API endpoints, exploring MCP architecture and automated tool generation.

---

## Projects

---

### Movie Recommender — Full Stack
Full-stack movie recommendation platform with semantic and collaborative filtering.

**Tech Stack:** `Next.js` `FastAPI` `MongoDB` `JWT` `Sentence-Transformers`

**Highlights:**
- Built personalized watchlists, ratings, and user-based authentication across a modular full-stack platform.
- Implemented semantic matching on 10K+ movies using Sentence-BERT embeddings and cosine similarity.
- Integrated SVD-based collaborative filtering achieving **78.8% Precision@10** with **<100ms** recommendation latency.

---

### LiquidCuts — Financial News-Liquidity Tracker
Gathers financial news and computes stock reactions to corporate events of variious companies.

**Tech Stack:** `Next.js` `MongoDB` `JWT` `Google Search API` `yFinance`

**Highlights:**
- Integrated Google Search API and yFinance to evaluate stock price reactions to 100+ event-driven news articles.
- Separated out layoffs, legal issues, and other critical events from company-specific news using keyword extraction.
- Aggregated and visualized trends from 50+ layoff events across top 5 tech companies over 4 years.

---

### Financial News Sentiment Analyzer
End-to-end sentiment classification pipeline on 5.8K+ labeled financial news statements.

**Tech Stack:** `Python` `PyTorch` `Scikit-learn` `Streamlit` `Pickle` `NLP` `Deep Learning`

**Highlights:**
- Benchmarked TF-IDF, Word2Vec, LSTM, FinBERT, and Logistic Regression for sentiment classification.
- Boosted accuracy from **51.7% (Naive Bayes) to 70.5% (LSTM)** through progressive model improvements.
- Deployed an interactive Streamlit app for real-time financial sentiment inference.

---

### Retrieval Techniques Benchmark
Systematic evaluation of retrieval strategies on the BEIR SciFact dataset (5K docs).

**Tech Stack:** `Python` `Sparse and Dense Retrieval` `RRF` `Cross-Encoder Reranking`

**Highlights:**
- Improved context recall from **72.8% (BM25) to 81.4%** using hybrid retrieval, RRF, and cross-encoder reranking.
- Achieved **79.4% context recall at 51ms** average query latency with BM25 + dense retrieval + RRF.
- Integrated BGE embeddings for dense retrieval and BGE reranker for cross-encoder reranking.

---

### LocalRAG — Offline PDF Query Engine
Fully local RAG pipeline for querying PDF documents without any cloud dependency.

**Tech Stack:** `Python` `Ollama` `ChromaDB` `LangChain` `SentenceTransformer`

**Highlights:**
- Built end-to-end pipeline — PDF ingestion, chunking, vector embeddings, semantic retrieval, and response generation.
- Supports Mistral and Phi-2 via Ollama; embeddings via all-MiniLM-L12-v2 stored in ChromaDB.
- Includes automated response evaluation module for quality assessment.

---

### Document Layout Detection *(Work in Progress)*
Layout detection pipeline for complex PDFs using object detection and OCR.

**Tech Stack:** `Python` `PyMuPDF` `PaddleOCR` `HuggingFace` `OpenCV` `DocLayout-YOLO` `VLMs`

**Highlights:**
- Detecting and labelling layout regions on PDFs using DocLayout-YOLO and PaddleOCR.
- Developed a VLM refinement step that uses OCR context and full-page images to correct misclassified boxes.
- Adding post-processing and box overlap-resolution to improve robustness of detector classification.

---

### MCP Generator *(Work in Progress)*
Agentic system that converts natural language into executable Rocket.Chat MCP tool modules.

**Tech Stack:** `Python` `LangGraph` `LangChain` `Node.js` `Handlebars` `Express`

**Highlights:**
- 8-node LangGraph pipeline: tag classification → candidate retrieval → workflow drafting → endpoint mapping → validation → plan finalization.
- Generates tool cache and confirmed workflow artifacts loaded and dispatched by a local MCP runtime server.

---

## Skills

**AI / ML**
`RAG` `LangChain` `LangGraph` `Retrieval Systems` `NLP`

**Frameworks & Libraries**
`PyTorch` `TensorFlow` `Scikit-learn` `HuggingFace` `Ollama` `Pandas` `NumPy`

**Languages**
`Python` `JavaScript` `C` `C++`

**Web & Backend**
`Next.js` `React` `Node.js` `FastAPI` `MongoDB` `PostgreSQL`

**Tools**
`Git` `GitHub` `Docker (basic)` `Streamlit`

---

## Certifications

- Advanced Learning Algorithms — DeepLearning.AI
- Regression and Classification — DeepLearning.AI
- Probability and Statistics
- Data Structures and Algorithms

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=CodeMatrix1&show_icons=true&theme=default&hide_border=true&count_private=true" height="150"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=CodeMatrix1&layout=compact&theme=default&hide_border=true" height="150"/>
</p>
