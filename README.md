# GROVER Model Test

## GROVER Tutorial – Fine-tuning with 2 Epochs

This repository contains a Jupyter Notebook tutorial for fine-tuning the **GROVER** (Graph Representation frOm self-superVised mEssage passing tRansformer) model using 2 training epochs. GROVER is a pre-trained model for molecular property prediction.

---

## 📘 Notebook Features

This notebook demonstrates:

- ✅ Loading and setting up the GROVER model environment  
- ✅ Preparing molecular datasets for fine-tuning  
- ✅ Training the model for 2 epochs to illustrate the tuning process  
- ✅ Evaluating the performance using appropriate metrics  

---

## 📚 Reference

If you use this notebook or build upon it, please consider citing the following work:

> Sanabria, M., Hirsch, J., Joubert, P.M. et al. *DNA language model GROVER learns sequence context in the human genome*.  
> **Nature Machine Intelligence**, 6, 911–923 (2024).  
> [https://doi.org/10.1038/s42256-024-00872-0](https://doi.org/10.1038/s42256-024-00872-0)

---

## 📂 File

- `GROVER_Tutorial_2_epochs.ipynb` – Main tutorial notebook

---

## 🔧 Setup & Requirements

Install dependencies using pip:

```bash
pip install torch dgl rdkit-pypi pandas scikit-learn tqdm
