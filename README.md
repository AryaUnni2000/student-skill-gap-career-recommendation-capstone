# Student Skill Gap Analysis & Career Recommendation System

### NLP-Powered Career Recommendation with Hybrid Matching, Skill-Gap Analysis & RAG

This capstone project develops an explainable career decision-support system that integrates candidate skills, semantic similarity, educational alignment, Canadian labour-market demand, prescriptive skill-gap analysis, and Retrieval-Augmented Generation (RAG).

---

## 🌐 Live Career Recommendation System

**Streamlit Application:**  
https://career-skill-gap-recommender.streamlit.app

The deployed application provides personalized career recommendations, Top-5 occupation rankings, skill-gap analysis, labour-market insights, and grounded RAG explanations.

---

## 📁 Complete Project Materials

### 📄 Final Report
The final academic project report will be available in the **Report** folder.

### 💻 Code & Jupyter Notebooks
The **Code_and_Notebooks** folder contains the complete analytical workflow:

- Data collection and exploration
- Data quality assessment
- Descriptive analytics
- Occupation filtering and selection
- Canadian labour-market analysis
- O*NET and CIP integration
- Candidate profiling
- NLP and skill extraction
- Semantic similarity analysis
- Hybrid career recommendation
- Prescriptive skill-gap analysis
- FAISS-based RAG
- Deployment preparation
- Human evaluation

### 📊 Data & Data Sources
The **Data_and_Data_Sources** folder contains available project datasets and documentation for:

- Government of Canada Job Bank
- O*NET occupational data
- Classification of Instructional Programs (CIP)
- Occupational crosswalks
- Processed project datasets

Large source datasets are documented in `DATA_SOURCES.md` when repository size limitations prevent direct hosting.

### 🧪 Evaluation Results
The **Evaluation_Results** folder contains human-reviewed evaluation outputs covering:

- Skill extraction
- Career recommendation ranking
- Skill-gap identification
- RAG explanation quality

### 📈 Power BI
The **PowerBI** folder contains the project's Power BI analytics/dashboard materials.

### 🖼️ Poster & Presentation
The **Poster_and_Presentation** folder will contain the final academic poster and presentation materials.

### 📐 Additional Materials
The **Additional_Materials** folder contains supporting project diagrams, including:

- Data-flow architecture
- Data preprocessing workflow
- End-to-end system architecture

---

## 🧠 Core Methodology

The project combines:

**NLP → Skill Extraction → Semantic Matching → Hybrid Career Ranking → Skill-Gap Analysis → RAG → Explainable Career Guidance**

The final hybrid recommendation incorporates:

- **35% Skill Match**
- **35% Semantic Similarity**
- **20% Canadian Labour-Market Demand**
- **10% Education Alignment**

Missing occupational skills are identified using O*NET requirements and prioritized to provide actionable skill-development recommendations.

RAG uses **Sentence Transformers and FAISS vector retrieval** to connect career recommendations with relevant occupational evidence and generate grounded explanations.

---

## 📊 Project Scope

- **63** candidate profiles
- **15** selected occupations
- **945** candidate–occupation combinations
- **315** Top-5 recommendation records
- **63/63** deployment-ready candidate profiles
- **63/63** RAG explanations generated

---

## 📈 Human Evaluation Highlights

| Evaluation | Result |
|---|---:|
| Skill Extraction F1 | 88.42% |
| Recommendation Precision@5 | 88.00% |
| Recommendation NDCG@5 | 97.82% |
| Skill-Gap Accuracy | 83.50% |
| Skill-Gap Expert Rating | 4.84 / 5 |
| RAG Mean Rating | 5.00 / 5 |

RAG evaluation results reflect the reviewed sample and should not be interpreted as universal system performance.

---

## 🛠️ Technologies

**Python • NLP • scikit-learn • Sentence Transformers • FAISS • Jupyter Notebook • Databricks • Streamlit • Power BI • GitHub**

---

## 🎯 Project Outcome

The system moves beyond answering:

**“Which career fits this candidate?”**

to answering:

**“Which career fits, why does it fit, what skills are missing, and what should the candidate develop next?”**

---

## ⚠️ Limitations

The system is intended as a career decision-support tool rather than a guarantee of employment or career success. Labour-market conditions may change over time, and recommendations depend on the quality and coverage of the available candidate, occupational, educational, and labour-market data.

---

## 🎓 Academic Project

**Program:** Master of Data Analytics  
**Course:** DAMO630 – Advanced Data Analytics  
**Institution:** University of Niagara Falls Canada  
**Year:** 2026
