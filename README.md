# SecPATE – Secure Aggregation of Teacher Ensembles (Implementation)

This repository provides a minimal implementation of the aggregation mechanism proposed in:

> **Anh-Tu Tran & Thi Hong Ha Nguyen (2025).  
> SecPATE: A Novel Approach for Aggregation of Teacher Ensembles with Secure Multi-Party Computation.  
> Proceedings of the 2nd International Conference on Cryptography and Information Security (VCRIS 2025).**

The implementation focuses on the **secure vote aggregation step** in the PATE framework.  
Teacher model predictions are aggregated using privacy-preserving computation techniques while preventing disclosure of individual teacher outputs.

---

## 📄 File Included

- **`PATEVOTE_Final.ipynb`**  
  A Jupyter Notebook implementing the SecPATE vote aggregation procedure.

The notebook demonstrates:

- loading teacher vote data  
- performing secure aggregation  
- applying differential-privacy noise  
- generating student training labels  

This code is intended primarily for **educational and research reference**.

---

## ▶️ How to Run

1. Install Python 3.10+
2. Install dependencies (NumPy, etc.)
3. Open the notebook:

```bash
jupyter notebook PATEVOTE_Final.ipynb
```
4. Run all cells in order.

---
## 🎯 Purpose

This implementation illustrates the core concept of PATE-style secure aggregation, where:

✔ multiple teacher models produce votes

✔ votes are aggregated securely

✔ privacy of each teacher is preserved

✔ only aggregated outputs are revealed

---
## 🔒 Ethical Notice

This repository is intended solely for academic research and privacy-preserving ML education.
Please ensure responsible and lawful use.

---
## 📚 Citation

If you reference this work, please cite:
```
@inproceedings{tran2025secpate,
  title        = {SecPATE: A Novel Approach for Aggregation of Teacher Ensembles with Secure Multi-Party Computation},
  author       = {Anh-Tu Tran and Thi Hong Ha Nguyen},
  booktitle    = {Proceedings of the 2nd International Conference on Cryptography and Information Security (VCRIS 2025)},
  year         = {2025}
}
```
