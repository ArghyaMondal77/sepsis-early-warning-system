# sepsis-early-warning-system

Hybrid PyTorch Transformer + XGBoost Early Warning System for Sepsis Triage



\# Echo Influence: Dynamic Relative Ranking based Sepsis Early Warning System



An intelligent, resource-aware clinical triage pipeline combining a PyTorch Temporal Transformer (Perception Layer) and an XGBoost Classifier (Decision Layer) to predict septic shock 6–9 hours prior to clinical onset.



\## 🚀 Key Highlights

\- \*\*Architecture\*\*: Hybrid Deep Learning + Gradient Boosted Decision Trees.

\- \*\*Resource-Aware Triage\*\*: Dynamic bed allocation under strict physical capacity constraints (e.g., 4 beds for 6 critical patients).

\- \*\*Validation\*\*: 50,000-run Monte Carlo triage simulation demonstrating >90% early-warning recall.

\- \*\*Full Trajectory Contextualization\*\*: Transformer attention mechanism captures the complete sequence of physiological decay.



\## 📁 Repository Structure

\- `sepsis\_master\_pipeline.ipynb`: Full training, feature engineering, and 50k Monte Carlo validation pipeline with printed logs.

\- `models/`: Exported XGBoost model artifacts and feature mapping schemas.

