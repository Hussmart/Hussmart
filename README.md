<h1 align="center">Hi, I'm Hossein Hush</h1>

<p align="center">
I build AI and machine learning tools for financial markets. My current work combines robust optimization, probability calibration, anomaly detection, and graph-based consensus methods to study how markets price risk and where models break.
</p>

<p align="center">
My research interest is optimization across different fields, with healthcare first on the list — clinical privacy, care coordination, and resource allocation are the problems I keep coming back to. After that, anything where a good model can improve a real decision.
</p>

<p align="center">
I love reading papers and keeping up with new methods. A lot of what ends up in these repos started as a paper I couldn't stop thinking about.
</p>

---

### AI and machine learning in financial markets

**[robust-kelly-prediction-markets](https://github.com/Hussmart/robust-kelly-prediction-markets)**
Bertsimas–Sim robust Kelly allocation, written as a MILP (Pyomo + HiGHS), on calibrated probabilities from Polymarket and Kalshi. Walk-forward tested on 2,623 out-of-time predictions. The honest answer is negative: market prices are already well calibrated. The repo also documents two look-ahead biases that had produced a fake +22% edge.
<br><sub>`robust optimization` · `LP duality` · `calibration` · `backtesting`</sub>

**[truewind](https://github.com/Hussmart/truewind)**
Reimplements the graph-theoretic consensus relaxation from CLIPPER (MIT, a robotics data-association method) in NumPy and applies it to financial anomaly detection. Compared against a naive z-score baseline on real BTC-USD data and validated across 8 assets.
<br><sub>`graph optimization` · `anomaly detection` · `NumPy`</sub>

### Healthcare

**[openmed-ambient-graph](https://github.com/Hussmart/openmed-ambient-graph)**
Extends the OpenMed SDK with ambient speech redaction (`faster-whisper` streamed through `deidentify()`), McAdams voiceprint anonymization, and a local entity graph with GraphRAG retrieval.
<br><sub>`clinical NLP` · `de-identification` · `speech` · `GraphRAG`</sub>

**[caremesh-ai](https://github.com/Hussmart/caremesh-ai)**
Multi-agent platform for healthcare workflows, adapted from MIT-licensed Microsoft code. Covers patient-record retrieval from FHIR and Fabric, care-status summaries, and clinical-trial search.
<br><sub>`multi-agent` · `Semantic Kernel` · `FHIR` · `Azure`</sub>

### Optimization research

**[vrptw-branch-and-price](https://github.com/Hussmart/vrptw-branch-and-price)**
Exact solver for the Vehicle Routing Problem with Time Windows. Extends an LP-only column generation codebase with ng-route pricing, dual stabilization, and a branch-and-bound layer, so it returns a certified optimum instead of a lower bound. Validated against an independent bitmask-DP brute-force solver.
<br><sub>`Python` · `column generation` · `branch-and-price` · `Solomon benchmarks`</sub>

---

### Skills and tools

**Languages and data**
<br>
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

**Machine learning and AI**
<br>
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Semantic Kernel](https://img.shields.io/badge/Semantic%20Kernel-5C2D91?style=flat-square)
![GraphRAG](https://img.shields.io/badge/GraphRAG-6A5ACD?style=flat-square)

**Optimization**
<br>
![Gurobi](https://img.shields.io/badge/Gurobi-EE3524?style=flat-square)
![Pyomo](https://img.shields.io/badge/Pyomo-2E5C8A?style=flat-square)
![HiGHS](https://img.shields.io/badge/HiGHS-4B8BBE?style=flat-square)

**Engineering and deployment**
<br>
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
