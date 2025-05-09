# 🧪 QIHO++ (Prototype) – Quantum-Intelligent Hybrid Optimizer

From chest X-rays to deep financial models — one universal AI optimizer

---

⚙️ **About the Project (Prototype Stage)**

**QIHO++** is a prototype-level experimental optimizer built to explore what happens when you blend quantum-inspired metaheuristics, chaotic momentum, and hybrid evolution strategies into one optimization engine. This project tests its potential in two areas:

- 🏥 **Medical Imaging (Pneumonia Detection)**
- 💸 **Finance (Credit Risk Prediction)**

It’s still early-stage, but the results so far are promising—especially on medical classification tasks.

---

🌐 **See Output Results (Reference Links)**

You can view actual screenshots and demo visualizations from this prototype on LinkedIn:

🔬 [Chest X-ray + QIHO++ Results](https://www.linkedin.com/posts/manish050_from-chest-x-rays-to-the-edge-of-ai-optimizing-activity-7319085997533671426-gak7)

🧠 [Finance + Real Optimizer Examples](https://www.linkedin.com/posts/manish050_ibm-google-stanford-activity-7318148350103441408-_tuy)

---

🔍 **Key Capabilities (Prototype-Level)**

- Intelligent hyperparameter search for real-world models
- Combines ideas from:
  - DE, PSO, CMA, GA
  - Quantum tunneling
  - Chaotic turbulence
- Adaptable to any supervised learning task (PyTorch preferred)
- Integrates with real datasets (medical, finance)

---

📁 **Project Structure**

```
QIHO/
├── core_v13.py                # Main QIHO_GodKiller optimizer (prototype)
├── run_pneumonia_qiho.py     # Medical X-ray optimizer run
├── run_finance.py            # Finance classification run
├── finance_credit.py         # MLP model for credit data
├── credit_data.csv           # Finance dataset (current)
├── credit_data_old.csv       # Legacy dataset
├── utils.py                  # Logging, plotting, GPU utils
```

---

🏥 **Medical Dataset Setup**

Make sure this structure is present:

```
datasets/
└── pneumonia/
    └── chest_xray/
        ├── train/
        ├── val/
        └── test/
```

(Download from public sources like Kaggle)

---

## 🧠 How to Run

### 🩺 Medical (Chest X-ray Classification)

```bash
python run_pneumonia_qiho.py
```

| Feature                  | Status     |
|--------------------------|------------|
| Medical AI Optimization | ✅ Working |
| Tabular MLP Optimization| ✅ Working |
| Optimizer Core Logic    | ✅ Functional |
| Web UI / Deployment     | ❌ Not yet |
| Model Export            | ❌ Planned |
| Logs (CSV / Console)    | ✅ Available |

---

### 🛠️ Requirements

Create `requirements.txt` with:

```
torch
numpy
matplotlib
pandas
scikit-learn
opencv-python
tqdm
```

Install with:

```bash
pip install -r requirements.txt
```

---

🔮 **Vision**

The long-term idea is to evolve **QIHO++** into a true model-agnostic AI optimizer, usable in:

- Healthcare diagnostics (X-rays, ECG, pathology)
- Financial risk models
- Scientific simulations
- Deep reinforcement learning

But for now, it’s just a functional prototype with a few real examples.
