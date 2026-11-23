<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2F6DB5,100:7B5CD6&height=150&section=header&text=Rishav%20Singh&fontColor=ffffff&fontSize=44&fontAlignY=38&desc=AI%20%2F%20GenAI%20Engineer&descAlignY=60&descSize=18" alt="header" />

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&pause=1200&color=2F6DB5&center=true&vCenter=true&width=620&lines=RAG+%7C+Agentic+AI+%7C+Vision-Language+Pipelines;Local-first+LLM+apps+that+keep+data+private;Final-year+B.Tech+(AI+%26+DS)+%40+MIT-WPU%2C+Pune)](https://git.io/typing-svg)

[![Portfolio](https://img.shields.io/badge/Portfolio-rishavsingh408.in-2F6DB5?style=flat-square&logo=firebase&logoColor=white)](https://rishavsingh408.in/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/rishav408)
[![Email](https://img.shields.io/badge/Email-rishav4805@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:rishav4805@gmail.com)

</div>

---

## 👋 About

I build GenAI applications that are **grounded, measurable, and often fully local**: RAG assistants, tool-calling agents, and vision-language pipelines in Python.
I'm a final-year B.Tech student (AI & Data Science) at MIT World Peace University, Pune, **open to fresher roles and internships in AI/GenAI engineering and data.**

---

## 🚀 Featured Projects

| Project | What it does | Highlights |
|---|---|---|
| 🤖 **[VeeraServe AI](https://github.com/Rishav408/VeeraServe)** | Agentic AI waiter for a restaurant: text, voice, and image input; adds to cart, places orders, checks status | LangGraph agent with **12 validated tools**, Chroma RAG, **6 evaluation suites**, **0% hallucinated prices** in measured runs, runs locally on LM Studio |
| ⚖️ **[Jurista](https://github.com/Rishav408/Jurista)** | Indian legal research copilot grounded in statutes, with document analysis | LangChain + Gemini, grounded in **4 legal texts** (BNS, IPC, CrPC, Constitution), dynamic search router, parses **PDF / DOCX / TXT** |
| 🚗 **[AI Dashcam Incident Explainer](https://github.com/Rishav408/Local-AI-Dashcam-Incident-Explainer)** | Fully offline incident detection and explanation from dashcam footage (team project, led) | YOLO11 + SORT + optical flow, MiniCPM-V and Mistral 7B via Ollama, **~80% fewer VLM calls**, face and plate blurring, PDF reports |
| 🗣️ **[Justify-AI](https://github.com/Rishav408/justify-ai)** | Explainable hate-speech analysis, no black-box transformers | **5 languages** (English, Hindi, Marathi, Bhojpuri, Marwari), Naive Bayes + lexical, causal, and demographic-bias scoring, FastAPI dashboard |

<details>
<summary><b>🔍 How the Dashcam pipeline works</b></summary>

```mermaid
flowchart LR
    A[Video] --> B[Keyframe extraction]
    B --> C[YOLO11 + SORT + optical flow]
    C -->|flagged segments only| D[MiniCPM-V + Mistral 7B via Ollama]
    D --> E[Face / plate blurring]
    E --> F[PDF report]
```

Running the VLM only on flagged segments is what cuts inference calls by about 80%.
</details>

<details>
<summary><b>More projects</b></summary>

- 🩺 **[VaniCure](https://github.com/Rishav408/vanicure)**: offline-first respiratory audio screening (PANNs CNN14, YAMNet, CNN-BiLSTM ensemble; FastAPI + React)
- 📊 **[IndianPulse](https://github.com/Rishav408/india-economic-dashboard)**: interactive India economic dashboard, 11 indicators (Streamlit, Plotly, Pandas)
- 🏘️ **[Urban Hive](https://github.com/Rishav408/urbanhive-web)**: housing society platform with role-based dashboards (Node.js, MongoDB, JWT)
- 🧑‍💼 **[FaceMark](https://github.com/Rishav408/facemark)**: lightweight face-recognition attendance system (OpenCV, LBPH, Flask)
</details>

---

## 🧰 Tech Stack

**AI / GenAI**
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![HuggingFace](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)

**Backend, Data & Tools**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## 🎓 Certifications

- Anthropic: AI Fluency for Students; Claude Code in Action (2026)
- LangChain Academy: Introduction to LangChain, Python (2026)
- IBM SkillsBuild: Artificial Intelligence Fundamentals (2025)

---

## 📈 GitHub Activity

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Rishav408&show_icons=true&hide_border=true&theme=transparent&title_color=2F6DB5&icon_color=7B5CD6" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Rishav408&layout=compact&hide_border=true&theme=transparent&title_color=2F6DB5" />

</div>

---

<div align="center">

💬 *Open to AI / GenAI engineering, data, and full-stack internships and fresher roles. Reach me at* **[rishav4805@gmail.com](mailto:rishav4805@gmail.com)**

</div>
