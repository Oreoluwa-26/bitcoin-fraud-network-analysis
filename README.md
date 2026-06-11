# bitcoin-fraud-network-analysis

# Bitcoin Fraud Network Analysis
> Detecting suspicious financial activity in 203,769 real-world Bitcoin transactions using network graph analysis.

## Overview
Analysed the Elliptic Bitcoin Dataset to identify money laundering patterns 
using graph theory, centrality metrics, and fraud detection algorithms.

## Key Findings
- 321 suspicious transactions flagged across 7,880-node subgraph
- Node 89273 identified sending funds to 288 unique destinations
- 164 unlabelled nodes exhibiting active laundering behaviour patterns

## Tools & Libraries
Python · NetworkX · Pandas · PyVis · Plotly · Scikit-learn · Matplotlib

## Project Structure
- `notebook/` — Full Jupyter analysis
- `outputs/` — Dashboard, compliance report, network visualisation

## Dataset
[Elliptic Bitcoin Dataset](https://www.kaggle.com/datasets/ellipticco/elliptic-data-set) 
— available on Kaggle (not included due to size)

## How to Run
pip install -r requirements.txt
jupyter notebook HNG14_Stage7_Ibukun_Owolabi_Mercy_HNG.ipynb
