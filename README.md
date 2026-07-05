
# Salma AbdelMonem | 🧪 Applied ML Researcher

ML Engineer | FastAPI · Docker · MLflow · LLMs | PhD in Applied ML

## Hi there 👋

I’m Salma, an applied machine learning researcher and PhD in machine learning, and I'm on a hands-on journey exploring my passion for building ML systems.

## 🔧 What I’ve Recently Learned & Built

I’ve been sharpening my engineering toolkit for reliable, maintainable ML apps:

- **Full-stack API Engineering**: Designing asynchronous backend services with (`FastAPI`), structured data validation through (`Pydantic`), and secure (`JWT`) authentication with role-based access control.
- **Containerization & Orchestration**: Packaging multi-service environments (App + MySQL) using (`Docker`) and (`Docker Compose`) to ensure seamless "one-command" deployments.
- **ML Model Serving & Lifespans**: Optimizing production ML delivery by using FastAPI (`lifespan`) handlers to load model weights and assets efficiently at application startup.
- **Database & Clean Architecture**: Building maintainable, decoupled systems using (`SQLAlchemy`) with (`asyncio`) for non-blocking database operations and reliable data persistence.
- **Code quality & automation**: Linting (`flake8`), logging (`loguru`), testing (`pytest`), clean architecture, dependency management using (`poetry`), automation with (`Makefiles`), and CI/CD using (`GitHub Actions`). 
- **NLP with Python and HuggingFace**: Feature engineering, (`KNN`), (`HuggingFace`) models, cosine similarity, and (`Gradio`) UI.
- **Retrieval-Augmented Generation**: With (`LangChain`), (`Chroma vectorstore`), and (`Ollama`).
- **MLflow for customer churn prediction**: Experiment data and model tracking, parameters, metrics, and automated model deployment with (`MLflow`).
- **Sentiment Analysis with Deep Learning**: Text classification using traditional machine learning, CNNs, RNNs, and transformers, with modular training and evaluation pipelines.


# Here is a summary of my latest projects
These projects demonstrate end-to-end machine learning applications that prioritize modularity, scalability, and real-world impact. As I transition into MLOps and LLM Engineering, these projects highlight my expertise in building production-ready systems.

## 🛒 retail-inventory-api

(https://github.com/salmacmpeg/retail-inventory-api)

Production-style retail inventory management system with a full ML serving pipeline.

**Highlights:**
- FastAPI with async SQLAlchemy, JWT auth, and role-based access control
- Dockerized with docker-compose — one command to run app + MySQL together
- ML-based price estimation endpoint with model loaded at startup via lifespan handler
- GitHub Actions CI running lint and tests on every push
- Clean architecture with Pydantic validation, Loguru logging, and Pytest coverage


## 🧠 PersonalityPrediction  

(https://github.com/salmacmpeg/PersonalityPrediction).

Personality classification tool with full CI/CD automation and clean architecture.

**Highlights:**
- Decision Tree pipeline built with Poetry + Makefile.
- Automated testing and linting with GitHub Actions.
- Loguru logging and modular config files.
- Pytest coverage across training/inference workflows.

---

## 🎬 Movies_recommendation_app 

(https://github.com/salmacmpeg/Movies_recommendation_app).

Hybrid movie recommender using metadata + semantic similarity in Gradio.

**Highlights:**
- KNN over count-vectorized genres + vote stats.
- Transformer-based embeddings via Hugging Face.
- Cached inference for fast performance.
- Scrollable UI with dynamic filtering.

---
## 📚 QuizGenerator 

(https://github.com/salmacmpeg/QuizGenerator).

RAG-based app for generating contextual quiz questions from course materials.

**Highlights:**
- Embedding with sentence-transformers, generation via llama3.2.
- Modular LangChain pipeline: loading, indexing, querying.
- Gradio UI for interactive quiz generation.
- Local deployment using Ollama for privacy.

---
## 📊 MLflow_customer_churn_prediction  

(https://github.com/salmacmpeg/MLflow_customer_churn_prediction)

MLflow-powered pipeline for tracking, comparing, and registering classical models on customer churn prediction.  

**Highlights:**  
- Registered cleaned datasets as MLflow artifacts via `mlflow.data.from_pandas`.  
- Evaluated Random Forest, SVM, and XGBoost with modular training and metric logging.  
- Tracked Balanced Accuracy, F1, GM, MCC, Recall, Precision, Confusion Matrix.  
- Logged models with inferred input/output signatures and parameter configs.  
- Timestamped runs and datasets with structured experiment tagging.  
- Modular design for reusable experimentation and debugging.

---
## 📚 Emotions_prediction_using_sentiment_analysis

(https://github.com/salmacmpeg/Emotions_prediction_using_sentiment_analysis)

Deep learning-based sentiment classification pipeline from English text.

**Highlights**:
- Data preprocessing, splitting, and batch loading.
- NLP pipeline with vectorization, tokenization, padding, and label encoding.
- XGbbost, CNN, BiLSTM, and transformer-based models trained and evaluated.
- Modular training loop with early stopping and checkpointing.
- Evaluation metrics: Accuracy, F1, Precision, Recall, Confusion Matrix.
- Clean architecture with reusable components for experimentation.
- Interactive Gradio UI for real-time sentiment prediction.

---
## 🚀 What I’m Currently Working Toward

I’m actively building my next wave of skills through focused self-learning and personal projects:

- **AWS deployment** — deploying containerized ML APIs using ECR, ECS, and S3
- **Demand forecasting** — building a retail ML project with MLflow, 
  FastAPI serving, and full experiment tracking
- **LangChain agents** — extending RAG workflows into agentic pipelines
---

## 🎯 My Technical Interests

- Designing insightful modular ML apps.
- NLP, document parsing, and automated knowledge extraction using OCR + regex.
- Bridging the gap between ML research and deployable, maintainable engineering workflows.
- Mentoring students and peers, building intuitive pipelines, and making technical knowledge accessible.

---
## 🎓 Completed & Ongoing Courses

### ✅ Completed
- `Machine Learning in Production: From Data Scientist to ML Engineer` – Udemy (2024-9).
- `Natural Language Processing in Python (2025 Edition)` – Udemy (2025-5).
- `Python Automation Testing with Pytest` – Udemy (2023-12).
- `PyTorch for Deep Learning with Python Bootcamp` – Udemy (2019-9).
- `PyTorch  Natural Language Processing NLP With Transformers in Python` – Udemy (2022-8).
- `Machine Learning in Production` – Coursera - Ongoing Exp. July 2025.
- `Master AI, Large Language Models \& Agents` – Udemy - April 2025.
- `Generative AI with Large Language Models` – Coursera - Feb. 2025.
- `Deep Learning Specialization` – Coursera (by Andrew Ng) - April 2020.
- `Machine Learning for Intelligent Systems CS4780` – Cornell Class - Sep. 2019.
- `From Zero to Hero GitHub Actions` – Dometrain.
- `Ultimate Guide to FastAPI and Backend Development` – Udemy.
---

## 💡 Let’s Connect

If you're working on **AI systems**, **MLOps**, or **LLM-powered apps**, I'd love to collaborate, share, or geek out over clean architectures and quirky edge cases.

- Reach out via [LinkedIn](https://www.linkedin.com/in/salma-abdelmotaleb-27911692/) or [Email](mailto:salmacmpeg@gmail.com)
- Check out my pinned repositories for real-world projects in ML, NLP, and LLM engineering.

---
> _If apps had personalities, mine would be a curious introvert with a relentless drive to learn and apply._
