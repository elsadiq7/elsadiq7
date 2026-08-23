from pathlib import Path

readme = r'''<h1 align="center">Hi, I'm Abdulrahman Elsadiq 👋</h1>

<h3 align="center">Machine Learning Engineer · AI for EDA · Efficient AI</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/elsadiq/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:abdelrhmanelsadiq53@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <img src="https://komarev.com/ghpvc/?username=elsadiq7&style=flat" alt="Profile Views"/>
</p>

---

### 👨‍💻 About me

I build AI systems that connect **machine learning with real engineering workflows**.

Right now, I am especially interested in:

- 🤖 **LLM agents for EDA and hardware verification**
- ⚡ **Efficient ML and FPGA acceleration**
- 🧠 **Spiking / neuromorphic neural networks**
- 🔎 **RAG, fine-tuning, and reliable LLM systems**
- 🛠️ Turning research ideas into working tools and reproducible experiments

Currently working as a **Machine Learning Engineer at Alpinum Systems**, where I develop agentic AI tooling for hardware verification.

---

### 🚀 What I'm building

#### 🤖 AlpinumDV
Agentic AI tooling for RTL and UVM verification.

`LLMs` `Python` `SystemVerilog` `UVM` `SVA` `QuestaSim` `VCS`

- Specification → verification plan → testbench → simulation
- Automated debugging and self-correcting LLM loops
- Coverage and mutation-based evaluation
- Multi-simulator workflows
- LLM-assisted requirements ↔ SVA translation

#### ⚡ FPGA AI Acceleration
Hardware/software co-design for efficient neural-network inference.

`PyTorch` `Verilog` `Vivado` `Quantization` `FPGA`

- Fixed-point neural-network deployment
- FPGA inference pipelines
- Hardware/software validation
- Edge AI and resource-aware optimization

#### 🧠 Spiking Neural Networks
Exploring efficient temporal models for event-based and video perception.

`PyTorch` `snnTorch` `Tonic`

- LIF-based SNN architectures
- Temporal learning and spike analysis
- Accuracy/efficiency trade-offs
- Neuromorphic perception

#### 🔎 LLM Systems
Experiments with model adaptation and grounded generation.

`Transformers` `PEFT` `TRL` `RAG` `Weaviate`

- LoRA / QLoRA
- Reward modeling and PPO
- Hybrid BM25 + semantic retrieval
- Reciprocal Rank Fusion
- Evaluation and token-cost tracking

---

### 📄 Research

I have worked on research spanning **FPGA AI acceleration** and **spiking neural networks**.

- **IEEE SMACD 2025** — *FPGA-Based Neural Network for Arabic and English Handwritten Digit Recognition*
- **IEEE SEEDA-CECNSM 2026** — *Spiking Neural Networks for Traffic Accident Detection* — accepted

---

### 🧰 Toolbox

**AI / ML**

![Python](https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)

**LLM / ML Systems**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

`Transformers` `PEFT` `LoRA` `QLoRA` `RAG` `RLHF` `PPO` `Weaviate`

**Hardware / EDA**

`Verilog` `SystemVerilog` `UVM` `SVA` `Vivado` `QuestaSim` `VCS` `RISC-V` `FPGA`

---

### 🌱 Currently exploring

- LLMs for **EDA and verification**
- Hardware-aware and **efficient AI**
- Agentic engineering workflows
- Neuromorphic computing
- Research collaborations in **AI × hardware**

---

### 📊 GitHub

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=elsadiq7&show_icons=true&hide_border=true&count_private=true" alt="GitHub Stats"/>
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=elsadiq7&layout=compact&hide_border=true&langs_count=8" alt="Top Languages"/>
</p>

---

<p align="center">
  <b>Always happy to discuss research, AI systems, FPGA acceleration, or AI for EDA.</b>
</p>
'''

path = Path("/mnt/data/README_github_profile.md")
path.write_text(readme, encoding="utf-8")
print(path)
