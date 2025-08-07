
---

##Tech Stack

- Python 3.x
- PyTorch
- PyTorch Geometric (PyG)
- NumPy, Pandas
- Scikit-learn
- NetworkX
- Matplotlib

---

##How to Run

1. Clone this repository and install dependencies (see cell imports in notebooks).

2. Launch Jupyter Notebook or JupyterLab.

3. Run the following notebooks:

- `DGI and GraphSage .ipynb`  
  → Trains and evaluates GraphSAGE and DGI on a citation network (e.g., Cora or Pubmed).

- `elliptic_gnn_model_with_explainer.ipynb`  
  → Trains a GNN on the Elliptic dataset and visualizes node-level explanations using GNNExplainer.

---

##Results

- Performance metrics (e.g., accuracy, loss curves) are plotted inside each notebook.
- GNNExplainer reveals node feature importance and local subgraph structures behind model decisions.

---

##Dataset Info

- **Citation datasets** such as Cora or Pubmed are likely loaded via PyTorch Geometric.
- **Elliptic dataset** is a real-world graph of Bitcoin transactions labeled as illicit or licit.

> Note: You may need to manually download the Elliptic dataset and adjust paths in the notebook.

---

##License

This project is licensed under the MIT License.

---

##Author

Created by Yiyun Xia 
Feel free to fork, star, and contribute!

