### Hi, I'm Hossein Hooshmand

I work where machine learning meets optimization. Most of my projects start with a real decision problem, like routing vehicles, sizing bets, or redacting a clinical conversation, and try to answer it with methods that come with a correctness check.

I care about results that hold up. My repos include tests against independent ground truth, and when an idea doesn't work on real data, I report the negative result.

---

#### Optimization and operations research

**[vrptw-branch-and-price](https://github.com/Hussmart/vrptw-branch-and-price)**
Exact solver for the Vehicle Routing Problem with Time Windows. Extends an LP-only column generation codebase with ng-route pricing, dual stabilization, and a branch-and-bound layer, so it returns a certified optimum instead of a lower bound. Validated against an independent bitmask-DP brute-force solver.
`Python` `column generation` `branch-and-price` `Solomon benchmarks`

**[robust-kelly-prediction-markets](https://github.com/Hussmart/robust-kelly-prediction-markets)**
Bertsimas–Sim robust Kelly allocation, written as a MILP (Pyomo + HiGHS), on calibrated probabilities from Polymarket and Kalshi. Walk-forward tested on 2,623 out-of-time predictions. The honest answer is negative: market prices are already well calibrated. The repo also documents two look-ahead biases that had produced a fake +22% edge.
`robust optimization` `LP duality` `calibration` `backtesting`

**[truewind](https://github.com/Hussmart/truewind)**
Reimplements the graph-theoretic consensus relaxation from CLIPPER (MIT ACL, a robotics data-association method) in NumPy and applies it to financial anomaly detection. Compared against a naive z-score baseline on real BTC-USD data and validated across 8 assets.
`graph optimization` `anomaly detection` `NumPy`

#### Machine learning for healthcare

**[openmed-ambient-graph](https://github.com/Hussmart/openmed-ambient-graph)**
Extends the [OpenMed](https://github.com/maziyarpanahi/openmed) SDK with ambient speech redaction (faster-whisper streamed through `deidentify()`), McAdams voiceprint anonymization, and a local entity graph with GraphRAG retrieval.
`clinical NLP` `de-identification` `speech` `GraphRAG`

**[caremesh-ai](https://github.com/Hussmart/caremesh-ai)**
Multi-agent platform for healthcare workflows, adapted from MIT-licensed Microsoft code. Covers patient-record retrieval from FHIR and Fabric, care-status summaries, and clinical-trial search.
`multi-agent` `Semantic Kernel` `FHIR` `Azure`

---

#### Tools I use

`Python` · `NumPy / SciPy` · `Pyomo` · `HiGHS` · `scikit-learn` · `Hugging Face` · `pytest` · `GitHub Actions`
