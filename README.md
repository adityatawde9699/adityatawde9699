# Aditya S. Tawde
### AI & Data Science Undergrad | Backend Developer | System Architect

[LinkedIn](https://www.linkedin.com/in/aditya-s-tawde-7a1392315) | [Email](mailto:adityatawde9699@gmail.com) | [Portfolio/Website Link if available]

**Focus:** Building modular AI systems, production-ready ML pipelines, and scalable backend architectures. Currently bridging the gap between local LLM orchestration and system-level control.

---

## 🛠 Engineering Stack

| Domain | Technologies |
| :--- | :--- |
| **AI & NLP** | Python, Gemini API (Function Calling), LangChain concepts, NLTK, Scikit-learn, Faster-Whisper |
| **Backend & API** | FastAPI, Django, Flask, AsyncIO, RESTful APIs, SQLite/PostgreSQL |
| **Data Engineering** | Pandas, NumPy, Selenium (Automation), Beautiful Soup, Matplotlib/Seaborn |
| **Infrastructure** | Linux (VM), Docker (Learning), Git, System Monitoring (psutil) |

---

## 🚀 Featured Architecture & Projects

### [1. Amadeus AI: Modular Intelligent Assistant](https://github.com/adityatawde9699/Amadeus-AI)
*A local-first, voice-controlled OS assistant using Google Gemini 2.0 for intent routing and system orchestration.*

* **Architecture:** Implements a Service-Oriented Architecture (SOA) separating the Core Logic, Tool Executor, and Voice Services.
* **Key Engineering Features:**
    * **Native Function Calling:** Dynamically maps natural language to 25+ system tools (File I/O, Process Management, Calendar).
    * **Smart Routing:** Uses a custom **TF-IDF + SVM classifier** to predict relevant tools before API calls, reducing latency and token usage.
    * **Async Concurrency:** leveraging `asyncio` for non-blocking voice listening and background system monitoring.
    * **Context Management:** Custom `ConversationManager` with token-window optimization.

### [2. End-to-End Fake Review Detection System](https://github.com/adityatawde9699/fake-review-system)
*Full-stack sentiment analysis and deceptive opinion spam detection pipeline.*

* **The Pipeline:** Raw Text → NLTK Preprocessing (Stopwords/Tokenization) → TF-IDF Vectorization → Logistic Regression.
* **Performance:** Trained on **100k+ Yelp reviews**; exposes confidence metrics via a Streamlit UI.
* **Deployment:** Serialized model serving using `joblib` with optimized inference capability.

### [3. DataScraperViz: Automated Financial Intelligence](https://github.com/adityatawde9699/datascraperviz)
*Automated data ingestion engine for financial markets and job boards.*

* **Automation:** Robust Selenium scripts with `WebDriverWait` strategies to handle dynamic DOM loading (LinkedIn/Edge WebView2).
* **Integration:** Real-time data fetching via **Alpha Vantage API**.
* **Visualization:** Automated generation of interactive financial plots using Plotly and Seaborn.

---

## 📜 Professional Certifications

* **Machine Learning Foundations** – University of Washington (Focus: Regression, Classification, Clustering)
* **Deep Learning & Generative AI** – IBM (Focus: Prompt Engineering, AI Pipelines)
* **Data Analysis with Python** – IBM (Focus: Pandas, Data Wrangling)
* **Programming with JavaScript** – Meta

---

## 📈 GitHub Activity

<p align="left">
<img src="https://github-readme-stats.vercel.app/api?username=adityatawde9699&show_icons=true&theme=graywhite&hide_border=true&count_private=true" height="150" alt="GitHub Stats" />
</p>
