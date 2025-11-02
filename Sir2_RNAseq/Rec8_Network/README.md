# Rec8 Protein Interaction Network

This analysis visualizes the **protein–protein interaction (PPI) network** of **Rec8**, a key cohesin subunit required for proper meiotic chromosome segregation.

---

##  Objective
To identify Rec8-related genes involved in cohesin stability and sister chromatid cohesion during meiosis.

---

##  Tools
- STRING Database (https://string-db.org)
- Cytoscape or NetworkX (Python)
- Data sources: S. cerevisiae protein interaction datasets

---

##  Workflow
1. Retrieve Rec8-related interactions (confidence > 0.7)
2. Construct adjacency matrix in Python
3. Visualize network graph highlighting key interactors

---

##  Output Files
| File | Description |
|------|--------------|
| `rec8_network.ipynb` | Network analysis notebook |
| `rec8_network.png` | Visualization of Rec8 interaction network |

---

##  Result Summary
Rec8 shows high connectivity with Scc1, Smc3, and Sgo1 — supporting its role in maintaining cohesion and chromosome pairing during meiosis.
