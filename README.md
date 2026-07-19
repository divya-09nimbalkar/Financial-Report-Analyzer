
```markdown
# Financial Report Analyzer

[![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)](https://python.org)
[![Google Gemini](https://img.shields.io/badge/Google_Gemini-2.5--flash-blueviolet.svg)](https://aistudio.google.com/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Production_Ready-brightgreen.svg)]()

>  An interactive automated quantitative financial validation engine combining mathematical matrix evaluations, polyfit trend indicators, and Google Gemini 2.5-Flash structured JSON blueprints to deliver balance sheet extractions, ratio scoring grids, accounting anomaly tracking registries, and buy/hold/sell risk thesis outputs.

---

##  System Architecture


Financial Text Streams / Raw Corporate PDF Filename Input
│
▼
┌─────────────────────────────┐
│   pdfplumber Extract Layer  │ ← Local Document Data Scrubbing
└──────────────┬──────────────┘
│
▼
┌─────────────────────────────────────────────────────────────┐
│            Gemini 2.5-Flash Core Evaluation Layer           │
│  ┌──────────────────────────┐ ┌──────────────────────────┐  │
│  │ JSON Schema Basic Extractor│ │ Investment Thesis Drafter│  │
│  └──────────────────────────┘ └──────────────────────────┘  │
└────────────────────────┬────────────────────────────────────┘
│
▼
┌─────────────────────────────────────────────────────────────┐
│            Local Analytical Matrix Pipelines Module         │
│  ┌──────────────────────────┐ ┌──────────────────────────┐  │
│  │ Ratio Benchmarking Block │ │ polyfit Trend Tracker    │  │
│  └──────────────────────────┘ └──────────────────────────┘  │
│  ┌──────────────────────────┐ ┌──────────────────────────┐  │
│  │ Anomaly Tracker Systems  │ │ 4-Panel Subplots Renderer│  │
│  └──────────────────────────┘ └──────────────────────────┘  │
└────────────────────────┬────────────────────────────────────┘
│
▼
┌─────────────────────────────────────────────────────────────┐
│                Interactive Browser Dashboard UI             │
│  ┌──────────────────────────┐ ┌──────────────────────────┐  │
│  │ Scorecard Summary Grid   │ │ Matplotlib Chart Plots   │  │
│  └──────────────────────────┘ └──────────────────────────┘  │
└─────────────────────────────────────────────────────────────┘

```

---

##  Key Features

* **Multimodal JSON Data Extractor:** Converts raw tabular PDF string vectors into fully typed, standardized data blueprints seamlessly via the Gemini API.
* **Algorithmic Fundamental Benchmarker:** Computes margins, return-on-equity indices, operational liquidity bounds, and interest coverage rates automatically.
* **Polyfit Trajectory Tracker:** Implements multi-year linear regressions and CAGR calculus layers to flag accelerating margins or contracting revenues.
* **Accounting Anomaly Watchdog:** Reviews cash reserves and shifts in liability profiles, triggering prompt notifications for leverage expansions or drops in working capital.
* **4-Panel Analytics Visualizer:** Generates comprehensive corporate dashboard charts tracking operational indicators, leverage bars, and EBITDA shifts saved directly to `output/`.

---

##  Tech Stack

* **AI Processing Engine:** Google Gemini 2.5-Flash (`google-generativeai`)
* **Document Extraction Core:** Local text extraction parsing engine via `pdfplumber`
* **Data Processing Models:** Pandas DataFrames, NumPy Arrays, and SciKit-Learn modules
* **Visual Presentation Interface:** Gradio Blocks Dashboard Layout (Gradio 6.0+ compatible)
* **Graphical Representation Layer:** Matplotlib Plotting Subplots

---

##  Jupyter Cell Sequence Blueprint

| Cell # | Type | Target Context Module | Technical Core Purpose |
| :--- | :--- | :--- | :--- |
| **Cell 1** |  Markdown | **Project Introduction** | System summary badges, feature indices, and blueprint architectures. |
| **Cell 2** |  Code | **Package Downloads** | Silent environments hydrations (`%pip install`) of GenAI, pdfplumber, and dependencies. |
| **Cell 3** |  Code | **Global Setup** | Library imports, configuration dictionaries, and data classes blueprints definition fields. |
| **Cell 4** |  Code | **Document Parsing** | Implements `FinancialDocParser` extracting balance sheets metrics. |
| **Cell 5** |  Code | **Ratio Calculations** | Implements `RatioAnalyzer` with internal benchmarks tracking logic matrices. |
| **Cell 6** |  Code | **Pipeline Orchestration** | Defines `FinancialReportAnalyzerAgent` managing subplots visualizers and CAGR trends. |
| **Cell 7** |  Code | **Diagnostics Execution** | Validates the pipeline using a try-except layer protecting against external endpoint caps. |
| **Cell 8** |  Code | **Gradio App Layout** | Launches the complete interactive investment matrix platform dashboard right inside browser view windows. |

---

##  Installation & Environment Setup

### 1. Build Local Workspace Target
```bash
cd Financial_Report_Analyzer
python -m venv venv
source venv/bin/activate # Windows Terminal: .\venv\Scripts\activate

```

### 2. Deploy Dependencies Manifest

```bash
pip install -r requirements.txt

```

### 3. Setup Gemini Access Token

Get a free API access key directly from [Google AI Studio](https://aistudio.google.com/). Paste your secret key parameter inside **Cell 3** configuration rows:

```python
os.environ["GEMINI_API_KEY"] = "AIzaSyYourSecretKeyStringHere"

```

---

##  Project Directory Architecture

```text
Financial_Report_Analyzer/
├── notebooks/
│   └── Financial_Report_Analyzer.ipynb  # Main interactive development notebook workspace
├── output/
├── .gitignore                           # Git configuration element tracking blocks
├── README.md                            # Comprehensive system documentation (This file)
└── requirements.txt                     # Pinned application dependencies manifest

```

---

##  Author

**Divya** — AI/ML & FinTech Developer | B.Tech Electronics & Telecom

```

```
