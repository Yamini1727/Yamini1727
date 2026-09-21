<h1 align="center">Hi 👋, I'm Yamini</h1>
<h3 align="center">M.Sc Data Science Student | B.Sc Statistics Graduate | Turning data into decisions</h3>

<p align="center">
<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=20&pause=1000&color=2B90D9&center=true&vCenter=true&width=500&lines=Data+Science+%7C+Statistics+%7C+Python;Currently+exploring+AI+%26+ML/DL+DSA;Turning+raw+data+into+real+insights" alt="Typing SVG" />
</p>

MSc Data Science student 
· Statistics · Forecasting · Machine Learning · EDA · AI Agents
Open to internships, research collaborations, jobs, and freelance work in data science, ML, and AI

---

### 📊 Project 

### Domain-Adaptable, Noise-Robust Speech-to-Text — LoRA Fine-Tuned Whisper Pipeline
*An end-to-end ASR pipeline: synthetic data generation → noise augmentation → LoRA fine-tuning → benchmarked evaluation → served API + UI*
 
- Engineered a synthetic ASR data pipeline — domain-specific prompt generation, multi-accent TTS synthesis (edge-tts), and machinery/industrial noise augmentation (ESC-50 + audiomentations) — to build a labeled clean/noisy dataset from scratch, entirely with free/open tools
- Fine-tuned Whisper-small using LoRA (PEFT) on a free Colab T4 GPU, adapting the model to manufacturing data-logging vocabulary and numeric readings while training under 1.5% of total model parameters
- Benchmarked baseline vs. fine-tuned Word Error Rate across clean and noise-augmented test conditions, reducing WER on noisy audio from 42.3% to 12.4%
- Served the fine-tuned model via a FastAPI `/transcribe` endpoint and a Streamlit UI (file upload + live microphone recording), with a modular, reproducible repo structure
**Tech:** Python, PyTorch, Hugging Face Transformers, PEFT (LoRA), FastAPI, Streamlit, edge-tts, audiomentations
  
**Status:** Complete 

---

### Urban Air Quality & Health Impact Prediction

*A leakage-free AQI forecasting pipeline translating pollution data into actionable health-risk categories*

- Built forecasting models (**ARIMA, Random Forest, ANN, XGBoost**) using lagged features across **5 Chennai monitoring stations**
- Engineered the pipeline to be **leakage-free**, ensuring forecasts reflect real predictive performance rather than data leakage artifacts
- Added a **CPCB-standard health-risk classification layer** on top of raw AQI forecasts, translating numbers into interpretable health-risk categories
- Designed for practical, real-world interpretability — bridging statistical forecasting with public health relevance

**Status:** Complete

---

## 🔬 Case Studies
 
### Store Item Demand Forecasting
- Built statistical forecasting models in Python to predict item-level retail demand from historical sales data, supporting inventory and business planning decisions
- Applied data cleaning and preprocessing to prepare time-series data, then created an interactive Power BI dashboard to visualize demand forecasts and trends for business stakeholders
**Tech:** Python, Pandas, Power BI, Statistical Forecasting
**Status:** Complete
 
### The Role of Parental Support in Shaping Career Choices Among College Students
- Designed and ran a survey-based research study, applying exploratory and confirmatory statistical analysis in R and SPSS to uncover patterns in student career decision-making
- Presented actionable, data-driven recommendations based on the findings
**Tech:** R, SPSS, Excel, Survey Methodology
**Status:** Complete
 
---

## 🛠 Skills & Tools
 
**Languages:** Python · R · C++ · SQL
 
**Machine Learning & AI:** Scikit-learn, ARIMA, Random Forest, ANN, XGBoost, Predictive Analytics, Recommendation Systems, NLP Basics, Large Language Models, K-Means, PCA, Regression
 
**Speech & Deep Learning:** PyTorch, Hugging Face Transformers, PEFT (LoRA), Whisper (ASR fine-tuning)
 
**Backend & Deployment:** Flask, FastAPI, Docker, Gunicorn, Streamlit, Pytest
 
**Data Analysis:** Pandas, NumPy, Exploratory Data Analysis (EDA), Statistical Modeling, Information Retrieval
 
**Data Visualisation:** Matplotlib · Seaborn · Tableau · Power BI
 
**Database:** SQL — complex queries, joins, aggregations, data cleaning & analytics
 
**Excel:** Pivot Tables · VLOOKUP · IF Functions · Data Cleaning · Dashboard Creation
 
**Time Series:** ARIMA, Exponential Smoothing, ADF Testing
 
**Other Tools:** Jupyter Notebook · SPSS
 
---
 
## 📚 Currently Working On

- Exploring AI, ML, DL Data Structures & Algorithms, Big Data
- Building backend/Python fundamentals to complement my data science skillset
- Applying statistical modeling and forecasting techniques (ARIMA, XGBoost) to new datasets

---

## 🌐 Connect with me

<p align="left">
<a href="https://www.linkedin.com/in/yaminid-126a36290" target="_blank">
<img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white" />
</a>
<a href="mailto:yaminiduraisamy14@gmail.com">
<img src="https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white" />
</a>
</p>

## 📊 GitHub Stats

<p align="center">
<img src="https://github-readme-stats.shion.dev/api?username=Yamini1727&theme=dark&hide_border=false&include_all_commits=false&count_private=false" width="48%" />
<img src="https://github-readme-stats.shion.dev/api/top-langs/?username=Yamini1727&theme=dark&hide_border=false&include_all_commits=false&count_private=false&layout=compact" width="48%" />
</p>
<p align="center">
<img src="https://streak-stats.demolab.com/?user=Yamini1727&theme=dark&hide_border=false" width="70%" />
</p>
<p align="center">
<img src="https://komarev.com/ghpvc/?username=Yamini1727&icon=0&color=0" alt="profile views" />
</p>
