Hi, I'm Hossein Hush
I build AI and machine learning tools for financial markets. My current work combines robust optimization, probability calibration, anomaly detection, and graph-based consensus methods to study how markets price risk and where models break.

My research interest is optimization across different fields, with healthcare first on the list. Clinical privacy, care coordination, and resource allocation are the problems I keep coming back to. After that, anything where a good model can improve a real decision.

I love reading papers and keeping up with new methods. A lot of what ends up in these repos started as a paper I couldn't stop thinking about.

AI and machine learning in financial markets
robust-kelly-prediction-markets Bertsimas–Sim robust Kelly allocation, written as a MILP (Pyomo + HiGHS), on calibrated probabilities from Polymarket and Kalshi. Walk-forward tested on 2,623 out-of-time predictions. The honest answer is negative: market prices are already well calibrated. The repo also documents two look-ahead biases that had produced a fake +22% edge. robust optimization LP duality calibration backtesting

truewind Reimplements the graph-theoretic consensus relaxation from CLIPPER (MIT ACL, a robotics data-association method) in NumPy and applies it to financial anomaly detection. Compared against a naive z-score baseline on real BTC-USD data and validated across 8 assets. graph optimization anomaly detection NumPy

Healthcare
openmed-ambient-graph Extends the OpenMed SDK with ambient speech redaction (faster-whisper streamed through deidentify()), McAdams voiceprint anonymization, and a local entity graph with GraphRAG retrieval. clinical NLP de-identification speech GraphRAG

caremesh-ai Multi-agent platform for healthcare workflows, adapted from MIT-licensed Microsoft code. Covers patient-record retrieval from FHIR and Fabric, care-status summaries, and clinical-trial search. multi-agent Semantic Kernel FHIR Azure

Optimization research
vrptw-branch-and-price Exact solver for the Vehicle Routing Problem with Time Windows. Extends an LP-only column generation codebase with ng-route pricing, dual stabilization, and a branch-and-bound layer, so it returns a certified optimum instead of a lower bound. Validated against an independent bitmask-DP brute-force solver. Python column generation branch-and-price Solomon benchmarks

Skills and tools
Languages and data<br> <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square" alt="SQL"> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL"> <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="pandas"> <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy">

Machine learning and AI<br> <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch"> <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn"> <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Hugging Face"> <img src="https://img.shields.io/badge/Semantic%20Kernel-5C2D91?style=flat-square" alt="Semantic Kernel"> <img src="https://img.shields.io/badge/GraphRAG-6A5ACD?style=flat-square" alt="GraphRAG">

Optimization<br> <img src="https://img.shields.io/badge/Gurobi-EE3524?style=flat-square" alt="Gurobi"> <img src="https://img.shields.io/badge/Pyomo-2E5C8A?style=flat-square" alt="Pyomo"> <img src="https://img.shields.io/badge/HiGHS-4B8BBE?style=flat-square" alt="HiGHS">

Engineering and deployment<br> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"> <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" alt="Kubernetes"> <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git"> <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions"> <img src="https://img.shields.io/badge/Azure-0078D4?style=flat-square" alt="Azure"> <img src="https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white" alt="pytest">
